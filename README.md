DOCKER-HASKELL-PLATFORM
=======================

Dockerfile to setup the haskell-plattform based on Ubuntu.

Building the Docker image
-------------------------

    $ docker build -t [username]/haskell-platform https://raw.github.com/martinrehfeld/docker-haskell-platform/master/Dockerfile

*Hint*: You need about 1.5 GB of memory to successfully build the Haskell Platform.

Running the Docker image created
--------------------------------

For example to get an interactive session with GHCi:

    $ docker run -i -t [username]/haskell-platform ghci

Or for general purpose use an interactive Bash session:

    $ docker run -i -t [username]/haskell-platform bash

Running pre-built images
------------------------

A pre-built image from this Dockerfile is also available on the
[Docker index](https://index.docker.io/u/martinrehfeld/haskell-platform/):

    REPOSITORY                       TAG          ID            SIZE
    martinrehfeld/haskell-platform   2013.2.0.0   7476be69dadc  63.43 MB (virtual 3.744 GB)
    martinrehfeld/haskell-platform   latest       7476be69dadc  63.43 MB (virtual 3.744 GB)
