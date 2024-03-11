# Playground: Node.js API from TypeScript, Express, and MongoDB

This is a modified repository containing the user creation and authenitication API using Node.js, Express, MongoDB and Javascript web tokens and implemented in Typescript

## API endpoints

| Path               | Description     | Method | Accepts               | Returns                                            |
| :----------------- | :-------------- | :----- | :-------------------- | -------------------------------------------------- |
| `/users`           | Base URL        | GET    |                       | Returns all users                                  |
| `/users/:id`       | Individual User | Get    |                       | Returns User of a given ID                         |
| `/users/register/` | Registration    | Post   | `{ email, password }` | Creates new user in database, returns user as JSON |
| `/users/login`     | Login           | Post   | `{ email, password }` | JWT token                                          |
