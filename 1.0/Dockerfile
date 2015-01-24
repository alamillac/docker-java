# java
#
# VERSION               0.0.1

FROM     alamilla/base
MAINTAINER Andres F. Lamilla, "alamilla@gmail.com"

# se actualiza la base de datos de apt
RUN apt-get update -qq

# instalacion de los paquetes necesarios para la app
RUN DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends openjdk-7-jdk
