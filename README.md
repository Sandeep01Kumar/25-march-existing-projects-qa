# hao-backprop-test

A simple Node.js HTTP server built with [Express.js](https://expressjs.com/) that exposes greeting endpoints.

## Prerequisites

- [Node.js](https://nodejs.org/) v18 or higher

## Getting Started

Install project dependencies using npm:

```bash
npm install
```

## Running the Server

Start the server with:

```bash
npm start
```

Or run directly:

```bash
node server.js
```

The server binds to `http://127.0.0.1:3000/`.

## Available Endpoints

| Method | Path       | Response           | Content-Type |
|--------|------------|--------------------|--------------|
| GET    | `/`        | `Hello, World!\n`  | text/plain   |
| GET    | `/morning` | `Good Morning`     | text/plain   |
