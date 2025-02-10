This project explores Authentication services like Passport, Google Authentication in, Node.js, to access secrets page.
The user information along with any typed secret is stored in database named secrets and table named as users using postgreSQL.

SQL for Table users:
CREATE TABLE users(
    id SERIAL PRIMARY KEY,
    email varchar(20) NOT NULL, UNIQUE
    password TEXT NOT NULL
    secret_text TEXT
);


Run commands:
npm i,
node index.js