# Maintainer: vicck-tech
pkgname=victory-flat-remix-icons-git
pkgver=1.0
pkgrel=1
_destname="~/.icons"
pkgdesc="Icons for Arcolinux-Victory Edition"
arch=('any')
url="https://github.com/Vicck-tech/victory-flat-remix-icons"
license=('GPL3')
makedepends=('git')
depends=()
provides=("${pkgname}")
options=(!strip !emptydirs)
conflicts=('flat-remix')
source=('victory-flat-remix-icons::git+https://github.com/Vicck-tech/victory-flat-remix-icons.git')
sha256sums=('SKIP')
package() {
#	mkdir -p "${pkgdir}${_licensedir}${_pkgname}"
#	mv "${srcdir}/${_pkgname}/"LICENSE "${pkgdir}${_licensedir}${_pkgname}/LICENSE"
#	mkdir -p "${pkgdir}${_destname}"
	install -dm 755 ${pkgdir}${_destname}
	cp -r ${srcdir}/victory-flat-remix-icons/.icons ${pkgdir}${_destname}
}