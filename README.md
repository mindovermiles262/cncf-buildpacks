# CNCF Buildpacks

This repo is the result of [Buildpacks.io Getting Started](https://buildpacks.io/docs/buildpack-author-guide/create-buildpack/setup-local-environment/) guide.

## Requirements

* `pack`
* `docker`

To build this example application, run:

```bash
$ pack build [IMAGE-NAME] \
    --path app \
    --buildpack buildpack
```

