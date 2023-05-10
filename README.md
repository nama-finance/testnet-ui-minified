# Nama protocol UI

Your can host this repo on any web hosting server, like Netlify, Vercel, and Firebase etc.

Alternatively, you could also deploy this app by using Docker, either follow the below steps to build and run or pull the image from [Dockerhub](https://hub.docker.com/repository/docker/namafinance/nama/general)

## Docker build

`docker build -t nama:prod .`

## Spin up the container on your local port `8000`

`docker run -it -p 8000:80 nama:prod`
