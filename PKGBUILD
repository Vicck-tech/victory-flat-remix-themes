# Maintainer: vicck-tech
pkgname=victory-flat-remix-themes-git
pkgver=1.0
pkgrel=1
_destname="/usr/share/themes/"
pkgdesc="Themes for Arcolinux-Victory Edition"
arch=('any')
url="https://github.com/Vicck-tech/victory-flat-remix-themes"
license=('GPL3')
makedepends=('git')
depends=()
provides=("${pkgname}")
options=(!strip !emptydirs)
conflicts=('flat-remix-gtk')
source=('victory-flat-remix-themes::git+https://github.com/Vicck-tech/victory-flat-remix-themes.git')
sha256sums=('SKIP')
package() {
	install -dm 755 ${pkgdir}${_destname}
	cp -r ${srcdir}/victory-flat-remix-themes/.themes ${pkgdir}${_destname}
}