CI Pipeline tools for Java/Maven builds for OpenShift
=====================================================

A docker image with Java, maven and docker/OpenShift packages installed on a Fedora base.
We use it as part of our [GitLab](https://gitlab.com) CI pipeline. It builds automatically using 
[DockerHub](https://cloud.docker.com/u/spatialedge/repository/docker/spatialedge/java-fedora-oc).

If you do need to build it locally, use the following commands:

```bash
docker build --tag=spatialedge/java-fedora-oc:latest .
docker push spatialedge/java-fedora-oc:latest
```

And you are done.
