# docker-bitbucket

[![Build Status](https://travis-ci.org/h0tbird/docker-bitbucket.svg?branch=master)](https://travis-ci.org/h0tbird/docker-bitbucket)

Containerized Bitbucket server.

```
docker run -it --rm \
--volume /data/bitbucket:/var/atlassian/application-data/bitbucket \
--publish 80:80 \
h0tbird/bitbucket
```
