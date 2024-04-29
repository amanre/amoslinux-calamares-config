pkgname=custom-archlinux-calamares-config
_destname1="/etc"
pkgver=24.05
pkgrel=3
pkgdesc="calamares for Custom Archlinux"
arch=('any')
url="https://github.com/amanre"
license=('GPL3')
makedepends=('git')
depends=()
#conflicts=('alci-calamares-config' 'alci-calamares-config-pure' 'alci-calamares-config-btrfs')
provides=("${pkgname}")
options=(!strip !emptydirs)
source=(${pkgname}::"git+${url}/${pkgname}")
sha256sums=('SKIP')
package() {
	install -dm755 ${pkgdir}${_destname1}
	cp -r ${srcdir}/${pkgname}${_destname1}/* ${pkgdir}${_destname1}
}
