<!--
SPDX-FileCopyrightText: 'Copyright Contributors to the ORT Container project' 

SPDX-License-Identifier: Apache-2.0
-->

# ORT Container builder

This repository is a **temporary** solution to provide a ORT Container.
Our intention is to work with ORT to publish official images, to this repository can be archived.
This discussion occurs in the [Publish the Docker images to a public repository](https://github.com/oss-review-toolkit/ort/issues/2441) issue.

# Available containers and tags

Containers are provided as GitHub Packages.
Images have a number of tags to help select the correct image and relate it to the upstream code:

- **digest-sha256-xxxxxxxxx** Digest of the resulting container
- **builder-sha-xxxxxxxx** SHA reference of this repository reponsible for building the container 
- **ort-sha-xxxxxxxx** SHA reference of the [ORT repository](https://github.com/oss-review-toolkit/ort) containing the Dockerfile
- **date-YYYYMMDD** Date the container was built
- **latest** Latest container build, **use with caution as it is subject to change!**

# License
The code and documentation in this repository is licensed according to the `Apache-2.0` license for full compatibility with the ORT project - see [LICENSE](LICENSE) for details.

# Contributing
Please read [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) and [CONTRIBUTING](CONTRIBUTING.md) for details on the process 
for submitting pull requests to us.

# Contact
Please read [SUPPORT](SUPPORT.md) for how to connect and get into contact with the ORT Container builder project.
