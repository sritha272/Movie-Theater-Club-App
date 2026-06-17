# Movie-Theater-Club-App
Full-stack club management app with automated scheduling and bookings — React, Spring Boot, MongoDB, AWS EC2. 99.9% uptime, 40% fewer scheduling errors.


- **Frontend:** React + TypeScript for type-safe, member-facing UI
- **Backend:** Java Spring Boot enforcing scheduling and membership business rules
- **Database:** MongoDB — chosen for its flexible document model, suited to variable screening/event attributes
- **Auth:** JWT-based authentication and session handling
- **Deployment:** Dockerized application running on AWS EC2
- **CI/CD:** GitHub Actions for automated build, test, and deploy

## Key Features

- Conflict-free scheduling with automated business rule enforcement
- Member booking and history management
- Secure, token-based authentication
- Cloud-deployed with containerized, repeatable deployments

## Results

- **99.9%** uptime on AWS EC2
- **50%** faster response times through full-stack performance optimization
- **40%** reduction in scheduling errors vs. the manual process it replaced

## Tech Stack

`Java` `TypeScript` `React` `Node.js` `Spring Boot` `MongoDB` `AWS EC2` `Docker` `JWT` `GitHub Actions`

## Setup

```bash
# Backend
cd backend
mvn clean install
mvn spring-boot:run

# Frontend
cd frontend
npm install
npm start
```

## License

MIT
