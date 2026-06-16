# Jupyter Kernel Client PKGBUILD

The [Jupyter Kernel Client](https://github.com/datalayer/jupyter-kernel-client) allows you to connect to live Jupyter Kernels through HTTP and WebSocket.

## Why this package exists?

This repository provides an [Arch Linux](https://archlinux.org) `PKGBUILD` for software that is not currently available in the [official repositories](https://wiki.archlinux.org/title/Official_repositories).

The goal is to make installation reproducible, auditable, and compatible with standard Arch Linux packaging practices.

## Upstream project

This repository **does not** contain the original software! It contains only the Arch Linux packaging files.

The software itself is maintained by the upstream project.

Upstream source code:

- [datalayer/jupyter-kernel-client: 🪐 Jupyter Kernel Client through HTTP and WebSocket](https://github.com/datalayer/jupyter-kernel-client)

[PyPI](https://pypi.org) package:

- [jupyter-kernel-client · PyPI](https://pypi.org/project/jupyter-kernel-client)

## Installation

```bash
git clone https://aur.archlinux.org/python-jupyter-kernel-client.git
cd python-jupyter-kernel-client
makepkg -si
```

## Maintenance

The `PKGBUILD` tracks upstream releases published on [PyPI](https://pypi.org/project/jupyter-kernel-client).

Issues related to the packaged software itself should be reported [upstream](https://github.com/datalayer/jupyter-kernel-client).

Issues related to Arch Linux packaging can be reported in this repository.
