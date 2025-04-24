# Project gogogadget

This project was deployed using Go Blueprint, a powerful framework that streamlined the development and deployment process. Leveraging Go Blueprint's modular architecture and built-in tools, the project benefits from efficient code organization, seamless dependency management, and robust performance. The deployment process was simplified with its integrated support for containerization and cloud-native environments, ensuring scalability and reliability. For more details on Go Blueprint, visit its official documentation.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

## MakeFile

Run build make command with tests

```bash
make all
```

Build the application

```bash
make build
```

Run the application

```bash
make run
```

Create DB container

```bash
make docker-run
```

Shutdown DB Container

```bash
make docker-down
```

DB Integrations Test:

```bash
make itest
```

Live reload the application:

```bash
make watch
```

Run the test suite:

```bash
make test
```

Clean up binary from the last build:

```bash
make clean
```

## gogo_gadget
