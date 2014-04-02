Afra Environment
================
Dockerfile for Trusted Build of the image with the Afra project dependencies.
This is used for development and Continuous Integration of the Afra project.

Build (optional)
----------------
You can build the Docker image using this Dockerfile and then run it, or you can skip the build step and just use the run command to fetch the image from the Docker index.

```bash
docker build -t bmpvieira/afra-environment .
```

Run
---
```bash
docker run -i -t bmpvieira/afra-environment -name afra-environment bash
```

License
-------
[MIT](https://raw.github.com/bmpvieira/afra-environment/master/LICENSE)
