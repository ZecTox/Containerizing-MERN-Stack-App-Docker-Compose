## In below image I have created an Dockerfile for frontend and build the image for it.
<img width="800px" src="./images/1 image.png">

## We also created a bridge network named "mern" for all these containers.

## In below image I have pulled an image of mongodb from registry for running the database locally by mounting the volume.
<img width="800px" src="./images/2 image.png">

## In below image I have created an Dockerfile for backend and build the image for it 
<img width="800px" src="./images/3 image.png">

## In this image we can see that all the containers are up and running.
<img width="800px" src="./images/4 image.png">

## Below we can see the demo of the application where all the containers are working just fine.
<img width="800px" src="./images/5 image.png">

## Now here we stop all the containers with the command "docker stop $(docker ps -aq); docker rm $(docker ps -aq)" and start writing the docker-compose.yaml
<img width="800px" src="./images/6 image.png">

## We wrote the docker-compose file and run the command "docker compose up -d" and we can see in terminal that all the services are up.
<img width="800px" src="./images/7 image.png">

## Faced a issue in volume mounting because of the error in directory which was causing the backend container go down.
<img width="800px" src="./images/8 image.png">

## Docker compose up also working just fine.
<img width="800px" src="./images/9 image.png">


# Below is the Application Instruction Document

## A simple MERN stack application

**Note** - To run this project using `docker compose`, follow the below steps.

Switch to the `compose` branch to learn the

1. Implementation of `Dockerfile` for `client` and `server`.
2. Run the containers using `Docker Compose`.

## Run it local without Docker

### Prerequisite

- Install `npm`

#### Start Server:

```
cd mern/server
npm install
npm start
```

#### Start Client

```
cd mern/client
npm install
npm run dev
```

<img width="1790" alt="Screenshot 2024-08-31 at 11 07 58 PM" src="https://github.com/user-attachments/assets/f414230b-8bd6-4393-b8de-6a10444a8dfd">
