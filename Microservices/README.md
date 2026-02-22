#Application port
 User Service (Port 3000)
- Product Service (Port 3001)
- Order Service (Port 3002)
- Gateway Service (Port 3003)


# setup require
- Docker Desktop installed
- Docker Desktop running
--docker --version
--docker compose version

# Run the application
- Open terminal and navigate to the project directory
- create a docket file for each servces
- Docker file contain 
 # Node
 # Work dir
 # 

- User Service (Port 3000)
- Product Service (Port 3001)
- Order Service (Port 3002)
- Gateway Service (Port 3003)
# create a docker compose file

# run below cppmand
# check for the running container
- docker ps
- docker exec -it <container-name> sh

- docker compose up --build
# validate the urls
    -http://localhost:3000/users
    -http://localhost:3001/products
    - http://localhost:3002/order
    

    project structure
    Microservice/ 
    ├── user-service/ 
    │ └── Dockerfile 
    ├── product-service/ 
    │ └── Dockerfile 
    ├── gateway-service/ 
    │ └── Dockerfile 
    ├── docker-compose.yml 
    
    └── README.md


