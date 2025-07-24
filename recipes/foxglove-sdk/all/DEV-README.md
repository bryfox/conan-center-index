Following https://docs.conan.io/2/examples/runners/docker/basic.html, but I created a pipenv in the foxglove-sdk/all directory.

In the docker-test branch:

cd recipes/foxglove-sdk/all
pipenv shell
conan create . -pr:h docker_example_host -pr:b docker_example_build --version 0.10.1

