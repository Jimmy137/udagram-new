# Documentation

# Udagram project
This project is for Full-stack Nanodegree program. It allows a user to post images on their profile and see other users images too.

Link To the app on AWS S3 Hosting: http://udagram-166399236689.s3-website-us-east-1.amazonaws.com/
## Getting Started

1. Clone this repo locally into the location of your choice.
2. Open a terminal and navigate to the root of the repo
3. follow the instructions in the installation step


### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- Install Angular

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

### Installation

Provision the necessary AWS services needed for running the application:

1. Make a '.env' file to store environment variables. The needed environment variables are mentioned in '.\udagram-api\src\config\config.ts'
2. In AWS, make a publicly available RDS database running Postgres. 
3. In AWS, provision a s3 bucket for hosting the uploaded files. 
4. From the root of the repo, navigate udagram-api folder `cd udagram-api` to install the node_modules `npm install`. After installation is done start the api in dev mode with `npm run dev`.
5. Navigate to the udagram-frontend `cd udagram-frontend` to intall the node_modules `npm install`. After installation is done start the api in dev mode with `npm run start`.

## Pipeline process
- Installing the dependencies
- Install dependencies for both backend and frontend
- Build both backend and frontend
- Deploy backend and frontend on AWS Cloud

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework


