# Simple Sum Application

## Overview

This project is a simple sum application built with TypeScript and Express. The main goal is to test GitHub Workflow Actions and perform integration testing using Vitest. The application also utilizes Supertest for HTTP assertions and Docker containers for actual database calls, managed by a Docker Compose file.

## Features

- Simple API to perform sum operations
- Integration testing with Vitest
- HTTP assertions with Supertest
- Continuous integration and deployment using GitHub Actions
- Database interactions via Docker containers and Docker Compose

## Tech Stack

- **Backend**: Node.js, Express
- **Language**: TypeScript
- **Testing**: Vitest, Supertest
- **Containerization**: Docker, Docker Compose

## Getting Started


### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/your-repo.git
    cd your-repo
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

### Running Tests

To run integration tests with Vitest and Supertest:

1. Ensure Docker containers are running:
    ```bash
    docker-compose up -d
    ```

2. Run the tests:
    ```bash
    npm run test
    ```

## GitHub Actions Workflow

This project uses GitHub Actions for continuous integration. The workflow is defined in `.github/workflows/test.yml` and includes steps to set up the environment, run tests, and build the application.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Vitest](https://vitest.dev/)
- [Supertest](https://github.com/visionmedia/supertest)
- [Docker](https://www.docker.com/)
- [GitHub Actions](https://github.com/features/actions)
