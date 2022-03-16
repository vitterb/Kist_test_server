# RoboSwarm - Dashboard
RoboSwarm - Dashboard is a custom docker image based on the standard node-red docker
image with the follow plugins installed:

- node-red-dashboard 

Use following commands to build and run the image: 
- `docker build -t rs-dashboard .`
- `docker run -it -p 1880:1880 -v data:/data --name rsd rs-dashboard`
