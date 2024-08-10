version: "3.8"

services:
  server:
    image: nginx:stable-alpine
    ports:
      - '8000:80'
    volumes:
      - ./nginx/nginx.conf:/etc/nginx/nginx.conf:ro
      
  php:
  mysql:
  composer:
  artisan:
  npm:
