## Minimal Docker image with Java

Basic [Docker](http://www.docker.com/) image to run [Java](https://www.java.com/) applications.
This image is based on [Alpine Linux](http://alpinelinux.org/) to minimize image size.


# Usage

Example:

  docker run -it --rm bfieber/alpine-java:openjdk-jre8 java -version