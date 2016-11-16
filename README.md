# Docker Image for Z3 and Java

This [docker](https://www.docker.com/) image is based on the [openjdk image](https://hub.docker.com/_/openjdk/) and comes with:

- [Z3 Theorem Prover](https://github.com/Z3Prover/z3)
- Java bindings for Z3 installed to `/usr/lib/com.microsoft.z3.jar`
- `ant`

You can find the image on [docker hub](https://hub.docker.com/r/sebastian256/z3-java/). If the build there is outdated (new package versions available in Debian) just [flick me a message](mailto:sebastian@schweizer.tel?subject=Please%20rebuild%20docker%20image%20sebastian256%2Fjava) that I can trigger a rebuild.
