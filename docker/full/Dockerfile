ARG IMAGE
ARG TAG
FROM $IMAGE:$TAG
LABEL maintainer="jakobknutsen@gmail.com"
RUN sed -i -e 's/build-/build-full-/g' version.sh
