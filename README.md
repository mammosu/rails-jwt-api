
# Simple auth with jwt by API-only rails applications.

User registration, login, get items by logged in user.

Rails version: 5.1.6

---

- POST `/auth/register`, requires `name`, `email` and `password`.

- POST `/auth/login`, requiers `email` and `password`, then returns access_token.

- GET `/items`, requires `access_token` as `Authorization` param.
