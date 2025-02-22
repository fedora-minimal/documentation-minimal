# Fedora Minimal Documentation

This is the build repository for the Fedora Minimal Documentation Websites. The published versions of these sites can be found at [Fedora Minimal Docs](https://docs.fedoraproject.org/en-US/minimal/) and [Fedora Minimal SIG Docs](https://docs.fedoraproject.org/en-US/minimal-sig/). Please report issues any issues with the Fedora Minimal documentation, or submit pull requests in this repository.

The latest development versions of these sites (generated from the `main` branch) can be found at [Fedora Minimal Docs](https://fedora-minimal.github.io/documentation-minimal/minimal) and [Fedora Minimal SIG Docs](https://fedora-minimal.github.io/documentation-minimal/minimal-sig).

## Contents

### `minimal-docs`

The `minimal-docs` directory contains the documentation for users and developers of the Fedora Minimal spin.

### `minimal-sig-docs`

The `minimal-sig-docs` directory contains the documentation about the Fedora Minimal SIG.

## Build and Preview

The Fedora Minimal documentation is built using [Antora](https://antora.org). General details for getting started can be found on the main Fedora Project [documentation guide](https://docs.fedoraproject.org/en-US/fedora-docs/contributing-docs/).

### Viewing locally

Building and previewing is done in containers and should work on any machine that has `podman` or `docker` available.

```console
$ ./docsbuilder.sh
```

Will compile and start a webserver that serves content at `https://localhost:8000`. It will automatically watch for any changes and recompile the website for you. `docsbuilder.sh` takes a `-h` argument to see more options.
