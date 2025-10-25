# Maintainer: @Derpitron <aadhithyanm@protonmail.com>
pkgname=cyber0day-wallpapers
pkgver=1.0
pkgrel=1
pkgdesc="Cyber-0-Day CTF competition wallpapers"
arch=('any')
license=('GPL3')
depends=()
source=()
install=cyber0day-wallpapers.install

prepare() {
    # where $startdir is just our current directory
    cp -r "$startdir/usr" "$srcdir/"
}

package() {
    install -d "$pkgdir/usr/share/backgrounds/cyber0day/"
    cp -a "$srcdir/usr/share/backgrounds/cyber0day/." "$pkgdir/usr/share/backgrounds/cyber0day/"
}
