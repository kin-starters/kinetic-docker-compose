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
5. login with the credentials you configured in the `docker-compose.yml` file (admin/kinetic1 by default)

# Support

Please head over to the [Kin Developer Community on Discord](https://kin.org/developerdiscord) to get help using Kinetic.
