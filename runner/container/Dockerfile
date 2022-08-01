FROM ubuntu:focal

ARG DEBIAN_FRONTEND=noninteractive
ENV TZ=Etc/UTC

RUN apt-get update && apt-get --no-install-recommends install -y \
    tar gzip libgtk2.0 libgtksourceview2.0 libgomp1

COPY ./verifast-nightly.tar.gz /tmp/verifast-nightly.tar.gz

RUN tar xvzf /tmp/verifast-nightly.tar.gz

