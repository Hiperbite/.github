# Hiperbite IT Company

Welcome to the Hiperbite IT Company Git repository! This README provides an overview of the repository, how to set up the project, and guidelines for contributing.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Project Overview

Hiperbite IT Company specializes in providing bespoke software development, website and email hosting services, and corporate email management. This repository contains the codebase for our various projects and services.

## Technologies Used

- **Backend:** Node.js, Express, TypeScript, Sequelize, MySQL, Redis
- **Frontend:** React, HTML, CSS, JavaScript
- **Testing:** Jest, Supertest
- **DevOps:** Docker, PM2, CI/CD pipelines
- **Linting & Formatting:** ESLint, Prettier

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- Node.js (>= 14.x)
- npm or yarn
- Docker
- MySQL
- Redis

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/hiperbite-it-company.git
    cd hiperbite-it-company
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env` file in the root directory and configure it with your environment variables. Example:

    ```env
    NODE_ENV=development
    PORT=3000
    DATABASE_URL=mysql://user:password@localhost:3306/hiperbite
    REDIS_URL=redis://localhost:6379
    JWT_SECRET=your_jwt_secret
    ```

4. **Run Docker containers:**

    ```bash
    docker-compose up -d
    ```

## Usage

To start the development server, run:

```bash
npm run dev
