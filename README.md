# Pulp 3 Containers

- [Multi-Process Images](multi-process-images) - A single image that runs [Pulp](https://github.com/pulp/pulpcore) or [Galaxy](https://github.com/ansible/galaxy_ng), as well as its third-party
services (nginx, postgresql and redis), in one single Docker/Podman container.
- [Single-Process Images](single-process-images) - These images are currently used by [pulp operator](https://docs.pulpproject.org/pulp_operator/), but they can be used in docker-compose or podman-compose. You can find a compose example [here](https://github.com/pulp/pulp-oci-images/tree/latest/images/compose).

### First-Party Services

The first-party services are services written by the Pulp project itself.

They are pulp-api, pulp-content, and pulp-worker.

### Third-Party Services

The third-party services are services written by other open source projects, but
Pulp depends on them as the middle tier in 3-tier application architecture to
run.

The 2 backends are the PostgreSQL database server and the redis server.

The 1 frontend is the Nginx or Apache webserver, with special config to combine
multiple Pulp services into one.

## Get Help

Documentation: [https://docs.pulpproject.org/pulp_oci_images/](https://docs.pulpproject.org/pulp_oci_images/)

Issue Tracker: [https://github.com/pulp/pulp-oci-images/issues](https://github.com/pulp/pulp-oci-images/issues)

Forum: [https://discourse.pulpproject.org/](https://discourse.pulpproject.org/)

Join [**#pulp** on Matrix](https://matrix.to/#/#pulp:matrix.org)

Join [**#pulp-dev** on Matrix](https://matrix.to/#/#pulp-dev:matrix.org) for Developer discussion.
