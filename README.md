# Digital Legacy for Unraid Community Applications

This repository publishes the Unraid template for the Docker image [`gabryk83/digital-legacy:latest`](https://hub.docker.com/r/gabryk83/digital-legacy). The application is in **beta**: owner sign-in with TOTP, check-in and an isolated dry run are available. The real release flow and beneficiary portal are not implemented. It does not automatically release information to beneficiaries.

The template requires local persistent storage for SQLite and keys, an HTTPS reverse proxy, the public host name, the proxy IP and a random bootstrap token for the first administrator. Review every field before installing. The image has been built and published for `linux/amd64`; the container was restarted on the Unraid host with the new icon visible in the Docker list; full release behavior remains under development.

Open [issues](https://github.com/gabryk91/digital-legacy-unraid/issues) for installation support. The application source repository is currently private. The MIT license in this repository covers only the template, metadata, icon and documentation; the container image and application code have separate licensing.

The app icon is published as [icon.png](icon.png). The Docker template and Community Applications profile reference its public raw URL. For an existing Unraid container showing the previous icon, open its edit form, switch to Advanced View, set **Icon URL** to 'https://raw.githubusercontent.com/gabryk91/digital-legacy-unraid/main/icon.png', and apply the change.
