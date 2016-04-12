# Pai Galinha WebSite Docker Repository 

This Project contains the Docker Pai Galinha`s Compose files that orchestrate all the website ecosystem.

This project can be used for development and production workflow.

For production, I use a private docker-compose.yml override file, with diferent configurations like restart policy (e.g., restart: always) to avoid services downtile.

See docker-compose.yml and docker-compose.override.yml files for more details.

TODO

Explain how to start project with docker