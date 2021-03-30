#  Build Week - unit 4 - Water My Plants

## Base URL
https://plants-serv.herokuapp.com/

## API endpoints

### login/register

| Auth | Endpoint           | Required                  | Restrictions | Notes                                             |
| -----| ------------------ | --------------------------| -------------| ------------------------------------------------- |
| POST | /api/auth/register | username, password, phone | Username must be unique| Creates a new user with auto Id.        |
| POST | /api/auth/login    | username, password        | None         | Returns a welcome message and the JSON Web Token. |
