# Business Management · Client

The client side of an appointment booking system for a small business.
Customers can browse the business services, view a gallery and book a meeting.
The business owner gets an admin area to manage the business details, services, meetings and users.

The server is in [business-management-api](https://github.com/rutofen/business-management-api).

## 👥 Team project

Built together with [leahssss](https://github.com/leahssss).
We both worked on the whole project, client and server.
The code was uploaded from her account at the end of the project.

## Features

- Sign up and sign in, with the session kept in a React context
- Customer area: home page, services, gallery and meeting booking with a date and time picker
- Admin area: business details, services, meeting list and users
- API calls with Axios

## Tech

React 18 · TypeScript · Vite · React Router · Axios · ESLint

## Run locally

```bash
git clone https://github.com/rutofen/business-management-client.git
cd business-management-client
npm install
npm run dev
```

Set `VITE_APP_URL` in `src/.env` to the address of the server.
