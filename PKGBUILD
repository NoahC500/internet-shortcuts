# Maintainer: Noah Craig <noahdcraig@outlook.com>
pkgname=internet-shortcuts
pkgver=1.0
pkgrel=1
pkgdesc="Installs a number of .desktop files which open websites I use"
arch=(any)
license=('GPL')
source=('Google Messages.desktop' 'Snapchat.desktop' 'WhatsApp.desktop')
sha256sums=('57fbcf66900ca0f6940a8599f6b4caef131ec8e055a14f67d51de08690f662b0' '8c4a0065cdc91fd633f6551deb657fbe800eeade544ee936644f60d1d9f7c204' '648f610d6152239c1feb023746b88a204f8c0ddce15885f0a3280135a7518d38')

package() {
	cd $srcdir
	mkdir "$pkgdir/usr/"
	mkdir "$pkgdir/usr/share/"
	mkdir "$pkgdir/usr/share/applications/"
	install './Google Messages.desktop' "$pkgdir/usr/share/applications/"
	install './Snapchat.desktop' "$pkgdir/usr/share/applications/"
	install './WhatsApp.desktop' "$pkgdir/usr/share/applications/"
}
