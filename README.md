# Docker Image for Z3 and Java

**Image Location**: `registry.gitlab.com/sebastians90/docker-z3-java:latest` (built by [GiltLab CI](https://gitlab.com/SebastianS90/docker-z3-java/pipelines))

This Docker image is based on the [openjdk image](https://hub.docker.com/_/openjdk/) and comes with:

- [Z3 Theorem Prover](https://github.com/Z3Prover/z3)
- Java bindings for Z3, installed to `/usr/lib/com.microsoft.z3.jar`
- [`ant`](https://packages.debian.org/stable/ant) (Java based build tool like make)

## Contributing
The canonical source of this Docker image is [hosted on GitLab.com](https://gitlab.com/SebastianS90/docker-z3-java).
Please file any issues [there](https://gitlab.com/SebastianS90/docker-z3-java/issues).

## License
This Dockerfile and the CI configuration is released into the public domain. Please see the [LICENSE](LICENSE) file for details.
For the license of Z3Prover or other software that is downloaded by this Dockerfile, please refer to their appropriate vendors.
