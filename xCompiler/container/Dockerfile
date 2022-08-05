FROM ubuntu:focal

ARG DEBIAN_FRONTEND=noninteractive
ENV TZ=Etc/UTC


RUN apt-get update && apt-get --no-install-recommends install -y \
  wget curl ca-certificates python bash git gcc g++ patch \
  rsync make unzip mercurial darcs tzdata
