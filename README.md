# kinetic-docker-compose

Basic example of a [Kinetic](https://github.com/kin-labs/kinetic) setup using Docker Compose. It includes:

- Kinetic API with the Kinetic Manager
- A Postgres database
- A Redis instance

## Requirements

- Docker and Docker Compose

## Usage

1. Clone this repository
2. Edit the `environment` section of the `docker-compose.yml` file to configure the Kinetic API
3. Run `docker-compose up` to start the stack
4. Navigate to `http://localhost:3000`
5. login with the credentials you configured in the `docker-compose.yml` file (admin/Kinetic1 by default)
6. Top stop the process, press `Ctrl+C` or run `docker-compose down`

## Running in the background

To run the stack in the background, run `docker-compose up -d`. To stop the stack, run `docker-compose down`. To see the logs, run `docker-compose logs -f`.

# Support

Please head over to the [Kin Developer Community on Discord](https://kin.org/developerdiscord) to get help using Kinetic.
