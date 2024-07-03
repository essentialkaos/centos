<p align="center"><a href="#readme"><img src=".github/images/card.svg"/></a></p>

<p align="center"><a href="#usage">Usage</a> • <a href="#contributing">Contributing</a> • <a href="#license">License</a></p>

<br/>

> [!CAUTION]
> **This repository has been archived due to the [end-of-life of CentOS 7](https://www.redhat.com/en/blog/centos-linux-has-reached-its-end-life-eol). It should no longer be used.**

This repository contains Dockerfiles for CentOS 7 for automatic image rebuild with the latest packages installed. The resulting images are usually bigger than base images but more secure (due to the very long period between base images rebuild).

### Usage

Using DockerHub:

```bash
docker pull essentialkaos/centos:7
```

Using GitHub Container Registry:

```bash
docker pull ghcr.io/essentialkaos/centos:7
```

### Contributing

Before contributing to this project please read our [Contributing Guidelines](https://github.com/essentialkaos/contributing-guidelines#contributing-guidelines).

### License

[Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0)

<p align="center"><a href="https://essentialkaos.com"><img src="https://gh.kaos.st/ekgh.svg"/></a></p>
