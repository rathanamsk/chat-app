# Slecret

Backend API for Slerect project.

### Built With

- [Node.js v14](https://nodejs.org/)
- [Sequelize v6](https://sequelize.org/)
- [PostgreSQL v13](https://www.postgresql.org/)

### Project Structure

```
.

[desquiz root directory]
├── bin
│   └── www ----------------------- (generate by express)
├── common ------------------------ (define our general logic)
├── config
│   └── config.js ----------------- (generate by sequelize)
├── controllers ------------------- (define our app logic here)
├── db
│   ├── migrations ---------------- (generate by sequelize)
│   ├── models -------------------- (generate by sequelize)
│   └── seeders ------------------- (generate by sequelize)
├── public ------------------------ (static files)
├── routes ------------------------ (define our routers)
├── scripts
│   └── start.sh ------------------ (define our entrypoint script)
├── views ------------------------- (view templates)
├── .dockerignore ----------------- (ignore copy local files to image)
├── .gitignore
├── .sequelizerc ------------------ (define sequelize structure)
├── app.js ------------------------ (core components)
├── docker-compose.yml ------------ (use to start docker services)
├── Dockerfile -------------------- (use to build docker image)
└── package.json
```

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- [Docker & Docker Compose](https://docs.docker.com/)
- [Node.js installed (for development only)](https://nodejs.org/)

### NOTE: I will update more . . .
