# Cognitive Programming Mentor

AI-powered personalized coding mentorship platform for students in tier-2 and tier-3 regions of India.

## Project Structure

```
cognitive-programming-mentor/
├── frontend/          # React + Vite frontend application
├── backend/           # Node.js + Express backend API
├── package.json       # Root package.json for monorepo
└── README.md
```

## Getting Started

### Prerequisites

- Node.js 18.x or higher
- npm 9.x or higher
- AWS account with credentials configured

### Installation

```bash
# Install dependencies for all workspaces
npm install
```

### Development

```bash
# Run both frontend and backend in development mode
npm run dev

# Run frontend only
npm run dev:frontend

# Run backend only
npm run dev:backend
```

### Building

```bash
# Build both frontend and backend
npm run build
```

### Testing

```bash
# Run tests for all workspaces
npm test
```

### Linting and Formatting

```bash
# Lint all workspaces
npm run lint

# Format all files
npm run format
```

## Environment Variables

### Backend

Create a `.env` file in the `backend/` directory:

```
AWS_REGION=ap-south-1
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
PORT=3000
NODE_ENV=development
```

### Frontend

Create a `.env` file in the `frontend/` directory:

```
VITE_API_URL=http://localhost:3000
```

## Technology Stack

### Frontend
- React 18.x
- Vite
- React Router
- Axios
- Framer Motion

### Backend
- Node.js 18.x
- Express.js
- AWS SDK v3 (Polly, DynamoDB)
- fast-check (property-based testing)

### AWS Services
- Amazon Polly (text-to-speech)
- Amazon DynamoDB (data persistence)

## License

MIT
