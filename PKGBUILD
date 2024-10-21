# Maintainer: Neko-Life <nekolife123579 at gmail dot com>
# See also https://github.com/Neko-Life-aur/dpp-bin
#
# Contributor: Jakub 'Eremiell' Marek <eremiell at eremiell dot net>
# See also https://github.com/eremiell-aur/dpp-bin
pkgname=dpp-bin
pkgver=10.0.33
pkgrel=1
pkgdesc="Lightweight and Scalable C++ Discord API Bot Library - binary version"
arch=('x86_64')
url="https://dpp.dev/"
license=('Apache')
depends=('glibc' 'gcc-libs' 'openssl' 'zlib' 'opus' 'nlohmann-json')
install="${pkgname}.install"
changelog="${pkgname}.changelog"
source=("https://raw.githubusercontent.com/Neko-Life-aur/dpp-bin-artifacts/main/${pkgname%-bin}-${pkgver}-${pkgrel}-x86_64.pkg.tar.zst")
sha256sums=('1d302756ce4ad8f35130ef42f4eb8448059e6d03fd17ed99461d891fff467f6f')
validpgpkeys=('988B124407F072AACFA92D2F52B5096DD205E14A')

package() {
	cd "${srcdir}"
	cp -a --reflink=auto "usr" "${pkgdir}/usr"
}
