# Maintainer: Jon Gjengset <jon@thesquareplanet.com>, Saren Arterius <saren@wtako.net>
pkgname=cpuset
pkgver=1.6
pkgrel=1
pkgdesc="Cpuset is a Python application to make using the cpusets facilities in the Linux kernel easier."
arch=('any')
url="https://github.com/endotronic/cpuset/"
license=('GPL2')
depends=('python2' 'python2-future' 'python2-configparser')
options=('!emptydirs')
source=("https://github.com/endotronic/cpuset/archive/1.6-patch.tar.gz")
md5sums=('SKIP')

package() {
	cd "$srcdir/$pkgname-$pkgver-patch"
	python2 setup.py install --root="$pkgdir/" --optimize=1
}
