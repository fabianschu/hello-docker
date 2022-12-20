# Getting started

- build doccker container locally: `docker build -t hello-docker .`
- run local container: `docker run hello-docker` (should print "kek" to console)

For publishing the container (on docker hub):

- tag the container: `docker tag hello-docker YOUR-USER-NAME/hello-docker`
- push container to docker hub: `cker push YOUR-USER-NAME/hello-docker`

Running the published container:

- `docker run YOUR-USER-NAME/hello-docker`

Running the container through bacalhau:

- `bacalhau docker run YOUR-USER-NAME/hello-docker`
