# ezPack

A command line tool to package code inside containers.

The goal of this project is to:

- Package code alongside all dependencies in a container image.
- Allow for easy distribution of combined package+dependencies.
- Use existing OCI tools to import and run the container/code.
- Run on multiple platforms and system architectures.

Use cases:

- Run your code in a container with minimal knowledge of Docker.
- Packaging code without requiring Docker to be installed.
- Re-producibility of research data, using an exact copy of the researcher's environment.
