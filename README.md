# Go + Google Cloud SDK Docker Image

This repository provides Docker images with on specific Go versions that include the Gooogle Cloud SDK. The main use case (for me) is CI.

The images are based on the `golang:{VERSION}-bullseye` images.

ARM and AMD64 builds are built weekly (or on commit) for the following Go versions:
- 1.16
- 1.18
- 1.19
