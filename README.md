# Docker is fun 🐳

![image](https://github.com/Rudy45KC/Docker-is-fun/blob/master/dockerImage.png)

# Docker commands -> 
create a docker file in your app directory 

using command ->
touch Dockerfile

add this to your docker file 
<!-- FROM node:18-alpine
WORKDIR /app
COPY . .
RUN yarn install --production
CMD ["node", "src/index.js"]
EXPOSE 3000 -->

now build a docker image using following command 

docker build -t [image_name] .

now run the container using following command --> 
docker run -dp 127.0.0.1:3000:3000 [image_name]

your app should be live on the port no. 3000

command to get the list of images ->
docker images 

command to get the list of running containers
docker ps 
