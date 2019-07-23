# nodeJS Express Boilerplate

## Environment

- macOS Catalina
- nodeJS v10.13.0
- MySQL v5.7.24

## Setup

### Install dependencies

    npm i

### Environment Variables

Export the following:

    export DATABASE_HOST="<INSERT HERE>"
    export DATABASE_NAME="<INSERT HERE>"
    export DATABASE_USER="<INSERT HERE>"
    export DATABASE_PASSWORD="<INSERT HERE>"

### Database

Start MySQL locally and run the setup script

  `bash scripts/datbabase/create-database.sh`

## Usage

    npm run start

Open a browser at http://localhost:3000/ 

If all goes well you should see the artists output 🎉

![api output screehnshot](./docs/images/demo.png "api output screenshot")


[demo](./docs/images/demo/jpg)

## TODO

- [x] Basic nodeJS express server with app route
- [x] Database (MySQL)
  - [x] Local setup script
  - [x] Local dummy data (seed)
  - [x] Database helper class
  - [x] Basic helper for a database entity 
  - [x] Update API to return from database 
  - [x] Optmize connections (Connection pool)
  - [ ] Cloud DB (see deployment)
- [x] Update README
- [ ] Promisify the callbacks (using utils)
- [ ] Controllers / pattern for Routing (e.g. MVC))
- [ ] ESLint
- [ ] Unit Tests
- [ ] Integration Tests
- [ ] CI / CD
  - [ ] CircleCI
- [ ] Docker
- [ ] Deploy
  - [ ] Heroku
  - [ ] AWS
  - [ ] GCP