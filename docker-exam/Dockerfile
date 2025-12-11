FROM node:22-alpine

WORKDIR /app

COPY package*.json .

ENV DATABASE_URL=postgresql://user:password@localhost:5432/db?schema=public

COPY /prisma .

ENTRYPOINT
