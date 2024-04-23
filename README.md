# Full Stack Application Example

This repository contains a simple yet complete full stack application integrating a suite of technologies for web development. The project is designed as a basic example to demonstrate the integration of front-end, back-end, and database technologies working together within a Dockerized environment.

## Technologies Used

- **Next.js 14 (TypeScript)**: Front-end React framework using TypeScript for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for rapidly building custom designs.
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express (JavaScript)**: Web application framework for Node.js, designed for building web applications and APIs.
- **Prisma**: Next-generation ORM for Node.js and TypeScript, used to manage the database layer.
- **PostgreSQL**: Robust, open-source relational database system.
- **Docker**: Platform for developing, shipping, and running applications inside isolated containers.
- **Docker Compose**: Tool for defining and running multi-container Docker applications.

## Architecture

This project follows a bottom-up approach, starting with the database setup, moving through to the back-end configuration, and finishing with the front-end development. Docker is used to containerize and manage the application components seamlessly.

### Project Layout

- `/database`: Contains SQL scripts and Docker configurations for PostgreSQL.
- `/backend`: Express application setup with Node.js and integrated with Prisma.
- `/frontend`: Next.js application written in TypeScript, styled with Tailwind CSS.

## Prerequisites

- Docker and Docker Compose
- Node.js
- npm or yarn
- Git

## Getting Started

### 1. Clone the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/BlueRacoon/fullstack-PERN.git
cd fullstack-PERN
docker-compose up --build
