# joomla-docker-dev
A Docker Compose YAML file for quick Joomla development. It fetches the latest version of Joomla.

# Just ...

- Inside the folder run: docker compose up [to start the stack]
- open your browser to http://localhost:8080 [for the latest Joomla]
- open your browser to http://localhost:8081 [to admin the DB]
- hit: Ctrl+c [to stop the stack]

# Network

If you want to connect the docker in a different network eg. proxy :

- docker network connect proxy <container_id>

# Updating

- docker compose down
- docker compose pull
- docker compose
