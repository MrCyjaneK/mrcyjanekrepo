# mrcyjanek's repo

[![Build Status](https://ci.mrcyjanek.net/badge/apt-update-repository.svg)](https://ci.mrcyjanek.net/jobs/apt-update-repository)

To install my repo, execute the following commands

```shell
# wget 'https://static.mrcyjanek.net/laminarci/apt-repository/cyjan_repo/mrcyjanek-repo-latest.deb' && \
  apt install ./mrcyjanek-repo-latest.deb && \
  rm ./mrcyjanek-repo-latest.deb && \
  apt update
```

# List of packages

<!-- architectures: amd64, arm64, i386, armhf -->
| Name \| Status | Supported Architectures      | Provides |
| -------------- | ---------------------------- | -------- |
| [![Build Status](https://ci.mrcyjanek.net/badge/build-btnet.svg)](https://mrcyjanek.net/projects/btnet/) | amd64, arm64, i386, armhf | btnet, btnet-createsite, btnet-pgpgen |
| [![Build Status](https://ci.mrcyjanek.net/badge/build-tor_file_server.svg)](https://mrcyjanek.net/projects/simple-tor-file-server) | amd64, arm64, i386, armhf | tor-file-server |
| [![Build Status](https://ci.mrcyjanek.net/badge/build-jwapi.svg)](https://mrcyjanek.net/projects/jwapi) | amd64, arm64, i386, armhf | jwstudy |
| [![Build Status](https://ci.mrcyjanek.net/badge/build-phosh_screenshot.svg)](https://git.mrcyjanek.net/mrcyjanek/phosh-screenshot/) | all | phosh-screenshot |
| [![Build Status](https://ci.mrcyjanek.net/badge/build-cyjan_repo.svg)](https://git.mrcyjanek.net/mrcyjanek/mrcyjanekrepo/) | all |  |
