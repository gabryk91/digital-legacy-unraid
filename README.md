# Digital Legacy for Unraid Community Applications

This repository publishes the Unraid template for the Docker image [`gabryk83/digital-legacy:latest`](https://hub.docker.com/r/gabryk83/digital-legacy). The application is in **beta**: owner sign-in with TOTP, check-in and an isolated dry run are available. The real release flow and beneficiary portal are not implemented. It does not automatically release information to beneficiaries.

The template requires local persistent storage for SQLite and keys, an HTTPS reverse proxy, the public host name, the proxy IP and a random bootstrap token for the first administrator. Review every field before installing. The image has been built and published for `linux/amd64`; installation and restart behavior on Unraid have not yet been verified.

Open [issues](https://github.com/gabryk91/digital-legacy-unraid/issues) for installation support. The application source repository is currently private. The MIT license in this repository covers only the template, metadata, icon and documentation; the container image and application code have separate licensing.
