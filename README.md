# homyz-backend
Backend server for the Homyz Real Estate Web App. Handles property listings, user interactions, and API integrations.


## Features

- Built with MERN (MongoDB, Express.js, React, Node.js) stack
- RESTful API for property listings and user interactions
- Connects to MongoDB database using Mongoose
- CORS enabled for frontend-backend communication
- Environment variables support with dotenv

## Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm
- MongoDB instance (local or cloud)
- [Prisma CLI](https://www.prisma.io/docs/getting-started)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ShashiSal98/homyz-backend.git
   cd homyz-backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up your environment variables:
   - Create a `.env` file in the root directory.
   - Add your MongoDB URI and other secrets as needed.

4. Generate Prisma client:
   ```bash
   npx prisma generate
   ```

### Running the Server

```bash
npm start
```

The server will start with `nodemon` for automatic restarts on code changes.

## Scripts

- `npm start` — Start the server with nodemon
- `npm run postinstall` — Generate Prisma client

## Dependencies

- express
- mongoose
- prisma / @prisma/client
- dotenv
- bcryptjs
- cors
- cookie-parser
- express-async-handler
- express-oauth2-jwt-bearer
- nodemon

## License

This project is licensed under the MIT License.


## Author
[Shashi Salwathura](https://github.com/ShashiSal98)

Happy Coding! 🚀
