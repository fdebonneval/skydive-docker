# skydive-docker
Docker compose to test Skydive

# Install docker-engine and docker-compose
## Install docker 1.10+

## Install docker-compose 1.6.0+

# Get the stack
Retrieve the docker-compose stack from the Github repository
 # git clone https://github.com/fdebonneval/skydive-docker.git

Then move to the folder and launch the stack. The stack launch has to be done in two steps, for now Skydive-analyzer crashes if Elasticsearch is not ready.
 # docker-compose up -d elasticsearch

Wait a few seconds and then
 # docker-compose up

# Todo
## Use a diferent docker image than "golang" that pulls 800MB
## Add a service discovery to allow nodes to find themselves
