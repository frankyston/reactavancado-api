# Strapi application

A quick description of your strapi application

# Create new user and database on PostsgreSQL

1. sudo -u postgres createuser strapi
2. sudo -u postgres createdb reactavancado
3. sudo -u postgres psql
4. alter user strapi with encrypted password 'xxxxx';
5. grant all privileges on database reactavancado to strapi;

# Create new project Strapi

yarn create strapi-app name-project

```
? Choose your installation type Custom (manual settings)
? Choose your default database client postgres
? Database name: reactavancado
? Host: 127.0.0.1
? Port: 5432
? Username: strapi
? Password: ******
? Enable SSL connection: No
```
