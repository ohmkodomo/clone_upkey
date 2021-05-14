# From node:12.18.1-alpin AS build
# WORKDIR /app
# COPY package.json ./
# RUN npm install
# COPY . .
# RUN npm run build


# FROM nginx:1.19.0-alpine AS prod-stage
# COPY --from=build /app/hello-world /usr/share/nginx/html
# Expose 80
# CMD ["nginx","-g","daemon off;"]
# build stage
FROM node:lts-alpine as build-stage
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
RUN npm run build

# production stage
FROM nginx:stable-alpine as production-stage
COPY --from=build-stage /app/dist /usr/share/nginx/html
EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

# FROM nginx
# RUN rm /etc/nginx/nginx.conf /etc/nginx/conf.d/default.conf
# COPY content /usr/share/nginx/html
# COPY conf /etc/nginx
