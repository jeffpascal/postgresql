# postgresql
 Notes for learning postgres faster

## Creating database

- ```createdb``` will create a database with the name of the current user
- ```dropdb <user>``` will delete the database created

## Connecting to database

- ```psql <dbname>```

## SQL

### Create table

```
CREATE TABLE weather (
    city            varchar(80),
    temp_lo         int,           -- low temperature
    temp_hi         int,           -- high temperature
    prcp            real,          -- precipitation
    date            date
);
```

```
CREATE TABLE cities (
    name            varchar(80),
    location        point
);
```

- The point type is an example of a PostgreSQL-specific data type. ex: (0,1)





