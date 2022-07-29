# VeriFast Builder

Scripts used to build and run the
[VeriFast](https://github.com/verifast/verifast) IDE inside a
[rootless](https://developers.redhat.com/blog/2020/09/25/rootless-containers-with-podman-the-basics)
[podman](https://podman.io/) container which is able to interact with the
host underlying XWindows on amd64 and arm64 architectures.

We need to containerize the VeriFast IDE using podman since it requires
very specific libraries.
