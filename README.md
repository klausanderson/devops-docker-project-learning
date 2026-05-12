Project destined to showcase the learning path in my DevOps Journey

It implies a Tier 3 Web Application, with 2 APIs - one made using NodeJS and the other one using Golang with Gin framework
The APIs query a PostgreSQL database for the current time and then providing that value to the React frontend served through an NGINX server.

In the folders there will be Dockerfiles with improvements in every version and comments that reflect the changes 
After that, docker-compose.yml files are also present to build and run the containers in a defined and controlled way
At the end, the topics of Development Workflow and Deployment are showcased through 
1. Implementing:
  - debugging,
  - testing,
  - Continuous Integration with GitHub Actions, 
2. Creating Ephemeral Environments with Shipyard
3. Deploying the application using Kubernetes
