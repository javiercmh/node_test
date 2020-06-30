# node_test
playing around with node

# Installation

## Initial setup

Following [this](https://www.youtube.com/watch?v=G8uL0lFFoN0) tutorial. There's also a [blog](https://getbuzz.io/c/learning-expressjs)

  ```sh
  nvn install --lts
  npx express-generator --view=pug
  yarn add nodemon --dev
  yarn add pg
  yarn add sequelize
  yarn global add sequelize-cli
  ```

### Postgres

psql postgres

  ```sql
  CREATE ROLE "express-mvp-dbuser" WITH LOGIN PASSWORD '123.456';
  CREATE DATABASE "express-mvp-db";
  ```


## Debug

  DEBUG=node-test:* npm start
