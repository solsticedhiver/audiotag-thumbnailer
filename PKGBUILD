# Contributor: solsTiCe d'Hiver <solstice.dhiver@gmail.com>

pkgname=audiotag-thumbnailer
pkgver=0.1
pkgrel=1
pkgdesc="A nautilus thumbnailer for MP3 and OGG file"
arch=('any')
url=""
license=("custom:WTFPL")
depends=('mutagen')
install=audiotag-thumbnailer.install
source=('audiotag-thumbnailer' 'audiotag-thumbnailer.schemas')
md5sums=('9c4bbee469176ec3bd4f6e4ab7e886b1'
         '15d1745b817a70515d16586852598315')

build() {
	cd $srcdir
	mkdir -p $pkgdir/usr/{share/gconf/schemas,bin}
	install -m644 audiotag-thumbnailer.schemas $pkgdir/usr/share/gconf/schemas
	install -m755 audiotag-thumbnailer $pkgdir/usr/bin
}

