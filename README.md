
# Description

A docker image for running  [serverless](https://serverless.com) commands.

The Dockerfile references a global variable called `RELEASE` that references a version from [serverless releases](https://github.com/serverless/serverless/releases)

# Example

```
docker build --build-arg RELEASE=1.41.1 -t ajorpheus/serverless .
```

