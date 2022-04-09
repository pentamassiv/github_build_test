# Maintainer: Penta Massiv (pentamassiv) <pentamassiv@posteo.de>

pkgname=github_build_test-bin
_pkgname=github_build_test
pkgver=PACKAGEVERSION
pkgrel=1
pkgdesc="Test automating building and publishing with Github Actions"
url="https://github.com/pentamassiv/${_pkgname}"
arch=(x86_64 aarch64)
license=(GPL3)
depends=(gtk4 libadwaita)
optdepends=()
provides=()
conflicts=()
replaces=()
sha256sums=("SKIP")
sha256sums_x86_64=("SKIP")
sha256sums_aarch64=("SKIP")
source=("https://github.com/pentamassiv/${_pkgname}/archive/refs/tags/v${pkgver}.tar.gz")
source_x86_64=("https://github.com/pentamassiv/${_pkgname}/releases/download/v${pkgver}/${_pkgname}_x86_64")
source_aarch64=("https://github.com/pentamassiv/${_pkgname}/releases/download/v${pkgver}/${_pkgname}_aarch64")

package() {
  install -Dm 755 ${_pkgname}_${CARCH} -t "${pkgdir}/usr/bin"
}