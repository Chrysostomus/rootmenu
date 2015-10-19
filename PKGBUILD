# Maintainer: Chrysostomus @forum.manjaro.org

pkgname=rootmenu
pkgver=0.1
pkgrel=1
pkgdesc="A wm independent desktop menu"
arch=(any)
url="https://github.com/Chrysostomus/$pkgname"
license=MIT
depends=('dmenu-manjaro'
	'xdotool'
	'wmutils'
	'xev'
	'xdg-open')
makedepends=('git')
source=("git://github.com/Chrysostomus/$pkgname")
md5sums=('SKIP')

package () {
	cd "$srcdir"
	install -dm755 $pkgdir/usr/bin
	cp -r $srcdir/$pkgname/bin $pkgdir/usr
	chmod a+x $pkgdir/usr/bin/*
}
