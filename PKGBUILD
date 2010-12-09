# Contributor: Kyle Keen <keenerd@gmail.com>
pkgname=albumbler
pkgver=20101209
pkgrel=1
pkgdesc="Like StumbleUpon for your music, it learns what you don't like."
arch=('any')
url="http://kmkeen.com/albumbler/"
license=('GPL')
depends=('python2')
makedepends=()
optdepends=('mocp: for music' \
            'cmus: for music' \
            'mpd: for music')
source=(http://kmkeen.com/$pkgname/$pkgname)
md5sums=('00e2bdec9842f628e6d2a5cd6cf8478f')

package	() {
  cd "$srcdir"
  #sed -i 's|/usr/bin/env python|/usr/bin/env python2|' albumbler
  install -D -m 0755 albumbler "$pkgdir"/usr/bin/albumbler
}

