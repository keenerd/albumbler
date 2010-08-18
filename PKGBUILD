# Contributor: Kyle Keen <keenerd@gmail.com>
pkgname=albumbler
pkgver=20100818
pkgrel=1
pkgdesc="Like StumbleUpon for your music, it learns what you don't like."
arch=('any')
url="http://kmkeen.com/albumbler/"
license=('GPL')
depends=('python')
makedepends=()
optdepends=('mocp: for music' 'cmus: for music' 'mpd: for music')
source=(http://kmkeen.com/$pkgname/$pkgname)
md5sums=('c915ed853676cb945ec6b2eac57d9ced')

build() {
  cd $startdir
  install -D -m 0755 albumbler ${pkgdir}/usr/bin/albumbler
}

