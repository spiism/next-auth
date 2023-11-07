# Next.js Project with Authentication Example

## Getting Started

To start the development server, use one of the following commands:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev


Testing with Postman
Register User
Endpoint: http://localhost:3000/api/user
Method: POST
Request Body:
json
{
    "name": "test",
    "email": "test@gmail.com",
    "password": "123456"
}


Login
Endpoint: http://localhost:3000/api/login
Method: POST
Request Body:
json
{
    "username": "test@gmail.com",
    "password": "123456"
}


GET API via Authenticated User
Endpoint: http://localhost:3000/api/user/1
Method: GET
Headers:
authorization: {JWT}