# Maintainer: Bradley S Mayes <bradleymayes@gmail.com>
pkgname=whatsmyip
pkgver=1.0
pkgrel=1
pkgdesc="Script that displays your externally visible IP address"
arch=('any')
url="https://github.com/l1nuxn1nj4/whatsmyip"
license=('GPL')
groups=()
depends=('bash')
makedepends=('git')
provides=("${pkgname}")
conflicts=("${pkgname}")
replaces=()
backup=()
options=()
install=
source=('whatsmyip')
noextract=()
sha256sums=('0a090a8424097f041ac3ecc64a79ea4971f1d924dacff653b79c97f046191f52')

package() {
	cd "$srcdir/"
  mkdir -p "$pkgdir/usr/bin/"
  cp whatsmyip "$pkgdir/usr/bin/"
}
