# Docker inside docker
Today I was told that you can run the `docker` from inside a docker container if you bind a volume to the docker socket of the host system typically located in `/var/run/docker.sock`. You have to be careful to get the permissions right. An example for this is
```sh
docker run -v /var/run/docker.sock:/var/run/docker.sock -it rwxrob/workspace --rm
```

----
#docker #docker-cli #volumes #mounts #socket #container
