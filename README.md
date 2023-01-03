
## Description
Mock server for FE examination.

---

## Instructions:

#### Install dependencies
``` npm install ```

#### Run Server
``` npm run start ```

---

## API Documentation
| Method | Endpoint | Payload | Misc. |
| --- | --- | ---- | ---- |
| POST | /login | ```{ email, password }``` | email: guest@email.com password: Pass123
| GET | /appointment | | |
| POST | /appointment | ```{ name, date, status }``` | status: (pending, completed) |
| PUT | /appointment/:id | ```{ name, date, status }``` | status: (pending, completed) |
| PATCH | /appointment/:id | ```{ status }``` | status: (pending, completed) |
| DELETE | /appointment/:id | | |

