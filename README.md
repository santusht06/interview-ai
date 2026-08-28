# interview-ai

## Installation

```bash
git clone <repository-url>
cd interview-ai
npm install
```

## Environment Variables

Create a `.env` file in the project root with the following variables:

```
MONGO_URI=your_mongodb_connection_string
PORT=3000
```

## Running the Application

```bash
node server.js
# or, with nodemon for automatic restarts during development
npx nodemon server.js
```

## API Endpoints

- `POST /api/auth/register` – Register a new user.  
- `POST /api/auth/login` – Authenticate an existing user.  

These routes are mounted under the `/api/auth` path.