# Contributor: Sven Schober <sven dot schober at uni dash ulm dot de>

pkgname=inkscape-palette-corporate-design-uni-ulm
pkgver=0.1
pkgrel=1
pkgdesc="An inkscape palette following the corporate design of Ulm University"
arch=('i686' 'x86_64')
url="http://www-vs.informatik.uni-ulm.de/DE/dept/staff/spann/vorlagen"
license=('GPL')
groups=()
depends=('inkscape')
makedepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
source=("http://www-vs.informatik.uni-ulm.de/DE/dept/staff/spann/download/vorlagen/Uni-Ulm-Corporate.gpl")
noextract=()
md5sums=('7b6fb761b58cb1aa9800c53071d6a05c')


build() {
	targetDir=$pkgdir/usr/share/inkscape/palettes
	mkdir -p $targetDir
	cp Uni-Ulm-Corporate.gpl $targetDir
}
