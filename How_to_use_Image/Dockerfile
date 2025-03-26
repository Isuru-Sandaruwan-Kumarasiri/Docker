# Get base image

FROM node:20-alpine

# Set working directory
WORKDIR /app

# copy the package.json file
COPY package.json .

# install the dependencies
RUN npm install

# copy the files
COPY . .

#run the app
# first cration
#CMD ["node","index.js"]

CMD ["npm","start"]

# this command run on the termianal
# <docker build -t my-first-image .> 


# To check the image
# <docker images>

# create a container
# <docker run  my-first-image>


# add the name of the container
# <docker run --name my-first-container my-first-image>

# check run containers
# <docker ps>

# check not running containers
# <docker ps -a>