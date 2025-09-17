#base image
FROM nginx:alpine

WORKDIR /usr/share/nginx/html

#remove default nginx files
RUN rm -f ./*

COPY . .

EXPOSE 80

CMD ["nginx", "-g", "daemon off:"]


#docker build -t <name of the image> .
#docker run -d -p 8080:80 <name of the image>

