## dockerfiles

[![make test](https://github.com/jessfraz/dockerfiles/workflows/make%20test/badge.svg)](https://github.com/jessfraz/dockerfiles/actions?query=workflow%3A%22make+test%22+branch%3Amaster)

This is a repo to hold various Dockerfiles for images I create.

## Contributing

I try to make sure each Dockerfile has a command at the top to document running it,
if a file you are looking at does not have a command, please
pull request it!


### Using the `Makefile`

```
$ make help
build                          Builds all the dockerfiles in the repository.
dockerfiles                    Tests the changes to the Dockerfiles build.
image                          Build a Dockerfile (ex. DIR=telnet).
latest-versions                Checks all the latest versions of the Dockerfile contents.
run                            Run a Dockerfile from the command at the top of the file (ex. DIR=telnet).
shellcheck                     Runs the shellcheck tests on the scripts.
test                           Runs the tests on the repository.
```
