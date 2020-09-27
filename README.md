Manning: Kubernetes Microservices.

This file was created to show how to deploy new releases of code.

The book goes from the very beginnings, but this repo is to capture the process of releases.

1. At commit 377eea1  Changed to release 2, it was just a release change. Not a rolling deployment. Also the tracks are stored in memory, so there is no persistance. The next step will be to add persistence.

2. Persistent Storage
    a. adding the history service is next.
    b. Mongo pod