# Contributor: yack <brayan@yack.com.br>

pkgname=python-mpdclient
_pkgnameorig=py-libmpdclient
pkgver=0.10.0
pkgrel=3
pkgdesc="Python module for interfacing MPD"
arch=('i686' 'x86_64')
url="http://www.musicpd.org/py-libmpdclient.shtml"
license=('LGPL')
depends=('python' 'mpd')
source=("http://mercury.chem.pitt.edu/~shank/$_pkgnameorig-$pkgver.tar.gz")
md5sums=('3a26540b7e057f23187b56e85dc82f95')

build() {
  cd ${srcdir}/$_pkgnameorig-$pkgver
  python setup.py install --root=${pkgdir} || return 1
}
