#!/usr/bin/env bash
# -*- mode: sh; mode: sh-bash -*-
# shellcheck disable=SC2034,SC2154,SC2164

pkgname=python-jupyter-kernel-client
pkgver=0.9.0
pkgrel=1
pkgdesc="Jupyter Kernel Client allows you to connect to live Jupyter Kernels through HTTP and WebSocket"
arch=('x86_64')
url="https://github.com/datalayer/jupyter-kernel-client"
license=('BSD-3-Clause')
depends=(
    'python'
    'python-jupyter-client'
    'python-jupyter-core'
    'python-jupyter-mimetypes'
    'python-requests'
    'python-traitlets'
    'python-typing_extensions'
    'python-websocket-client'
)
source=(
    "jupyter_kernel_client-$pkgver.tar.gz::https://files.pythonhosted.org/packages/source/g/jupyter-kernel-client/jupyter_kernel_client-$pkgver.tar.gz"
)
sha256sums=('SKIP')

build() {
    cd "jupyter_kernel_client-$pkgver"
    python -m build --wheel --no-isolation
}

package() {
    cd "jupyter_kernel_client-$pkgver"
    python -m installer --destdir="$pkgdir" dist/*.whl
}
