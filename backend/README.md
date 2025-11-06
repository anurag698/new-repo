# VOCH Backend API

NestJS-based backend API for the VOCH (Voice of Common Human) platform.

## Architecture

- **Framework**: NestJS
- **Database**: PostgreSQL with Prisma ORM
- **Cache**: Redis
- **Authentication**: JWT + Passport
- **Queue**: BullMQ

## Modules

- **auth** - Authentication & Authorization
- **users** - User management
- **posts** - Social posts & content
- **polls** - Polling system
- **campaigns** - Campaign management
- **comments** - Comment system
- **reactions** - Likes, shares, etc.

## Setup

```bash
# Install dependencies
npm install

# Setup environment
cp .env.example .env

# Run database migrations
npx prisma migrate dev

# Start development server
npm run start:dev
```

## API Documentation

Swagger documentation available at `/api/docs` when running locally.
