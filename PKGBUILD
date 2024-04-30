pkgname=amoslinux-calamares-config
_destname1="/etc"
pkgver=24.05
pkgrel=01
pkgdesc="calamares for Amos"
arch=('any')
url="https://github.com/amanre"
license=('GPL3')
makedepends=('git')
depends=()
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${pkgname}::"git+${url}/${pkgname}")
sha256sums=('SKIP')
package() {
	install -dm755 ${pkgdir}${_destname1}
	cp -r ${srcdir}/${pkgname}${_destname1}/* ${pkgdir}${_destname1}
}
