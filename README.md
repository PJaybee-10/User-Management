# User Management

> Full stack demo CRUD app built with Express, React and TypeScript.

## Premise

A simple User Management interface which lists current users in the system. Admins can add a new user, and update or delete existing users.


![demo](demo.gif)

## Technologies Used

- **Frontend:** React, TypeScript, Material UI
- **Backend:** Node + Express, OvernightJS, Mongoose
- **Database:** Docker, MongoDB
- **CI/CD:** GitHub Actions

## Local Development

### Database and Server Setup

- Ensure that `Docker` is installed and running
- In your terminal, `cd` into the `server` directory and run `npm install`
- From the project root, open your terminal and run `docker compose up`
  - Seed data for `admins` and `users` will be populated in the database automatically
  - The server will be running on `http://localhost:3000`

The `server/README.md` provides additional information on build scripts and environment variables.

### Client Setup

- In another terminal window, `cd` into the `client` directory and run `npm install`
- Run `npm start`
  - The application may be accessed in a web browser at `http://localhost:8080`

The `client/README.md` provides additional information on build scripts and environment variables.

## Technical Requirements

> The runtime environment for this application requires `node >= 14.6.0` and `npm >= 6.14.7`.

## Configuration

> This application makes use of `ESLint`, `Stylelint` and `EditorConfig`. Each of these features requires
> an extension be installed in order to work properly with IDEs and text editors such as VSCode.
