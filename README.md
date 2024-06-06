# NEXT-BASKET-Technical-Assessment
NEXT BASKET Technical Assessment for Senior PHP Developer (Pakistan) 

# Symfony-Based Microservices Example

## Setup

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Start the services**:
    ```sh
    docker-compose up --build
    ```

3. **Run the tests**:
    ```sh
    cd users
    php bin/phpunit
    cd ../notifications
    php bin/phpunit
    ```

## Endpoints

- **Users Service**:
  - `POST /users`: Create a new user.

## Technologies

- Symfony
- Docker
- RabbitMQ
- PHPUnit

