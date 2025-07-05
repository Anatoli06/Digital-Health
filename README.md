# Digital-Health

Digital-Health is an early stage web application that will provide a platform for managing health records, appointments and other clinical data.  The project uses **Node.js** with **Express** for the backend and **React** with **Tailwind CSS** for the client.  Data can be stored in either **MongoDB** or **MySQL** depending on your preferred setup.

## Goals

- Centralise health information in a modern, web‑based system.
- Offer a responsive client built with React and Tailwind CSS.
- Provide a RESTful API powered by Express.
- Support both MongoDB and MySQL as data stores.

## Installation

1. Install [Node.js](https://nodejs.org/) on your machine.
2. Install either [MongoDB](https://www.mongodb.com/) or [MySQL](https://www.mysql.com/) and make sure it is running.
3. Clone this repository:
   ```bash
   git clone <repo-url>
   cd Digital-Health
   ```
4. Install the server dependencies:
   ```bash
   npm install
   ```
5. Install the client dependencies:
   ```bash
   cd client
   npm install
   ```

## Running the development server

From the repository root start the backend and client in development mode:

```bash
# in one terminal for the server
npm run dev

# in another terminal for the React client
cd client
npm start
```

The server will expose the API (by default on port 3000) and the client will run the React development server (typically on port 3001).

## Building the client

To create a production build of the React client run:

```bash
cd client
npm run build
```

The optimised static files will be generated in `client/build`.
