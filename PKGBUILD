# Maintainer: Christian Hesse <mail@eworm.de>
# Contributor: Dariusz Górecki <darek.krk@gmail.com>
# Contributor: Juan Diego Tascon

pkgname=xcursor-comix
pkgver=0.8.2
pkgrel=2
pkgdesc="Comix X Cursor Theme"
url="http://www.kde-look.org/content/show.php/ComixCursors?content=32627"
depends=('libxcursor')
license=('GPL')
arch=(any)
source=("http://www.limitland.de/downloads/comixcursors/ComixCursors-${pkgver}.tar.bz2")

package() {
	mkdir -p ${pkgdir}/usr/share/icons
	cp -R ${srcdir}/ComixCursors-[A-Z]* ${pkgdir}/usr/share/icons/
}

sha256sums=('3109e4d19d930a6a2a5c3422ebaaa2002640169118f9b12c042bb64995f3ec31')
