# Maintainer: Jonathan Sanfilippo  <jonalinux dot uk at gmail dot com>

pkgname=core-base
pkgver=1.4
pkgrel=1
pkgdesc="base script for core"
arch=('any')
license=('GPL')


package() {
       mkdir -p "$pkgdir/etc/"
       cp -rp os-release "$pkgdir/etc/os-release"
       install -Dm755 -t "$pkgdir/usr/bin/" updates
       install -Dm755 -t "$pkgdir/usr/bin/" core-start 
}
