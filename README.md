# bitbucket

[![Build Status](https://travis-ci.org/katosys/bitbucket.svg?branch=master)](https://travis-ci.org/katosys/bitbucket)

Containerized Bitbucket server.

```
docker run -it --rm \
--volume /data/bitbucket:/var/atlassian/application-data/bitbucket \
--publish 80:80 \
quay.io/kato/bitbucket:latest
```
