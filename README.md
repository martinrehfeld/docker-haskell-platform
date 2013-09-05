DOCKER-HASKELL-PLATFORM
=======================

Dockerfile to setup the haskell-plattform based on Ubuntu.

Building the Docker image
-------------------------

    $ docker build -t [username]/haskell-platform https://raw.github.com/martinrehfeld/docker-haskell-platform/master/Dockerfile

Running the docker image created
--------------------------------

For example to get an interactive session with GHCi:

    $ docker run -i -t [username]/haskell-platform ghci

Or for general purpose use an interactive Bash session:

    $ docker run -i -t [username]/haskell-platform bash
