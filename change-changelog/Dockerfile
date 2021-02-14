# Container image that runs your code
FROM rcmachado/changelog:latest

# Copies your code file from your action repository to the filesystem path `/` of the container
COPY phpstan.sh /phpstan.sh

# Code file to execute when the docker container starts up (`entrypoint.sh`)
ENTRYPOINT ["/phpstan.sh"]