# Maintainer: Jonathan Sanfilippo  <jonalinux dot uk at gmail dot com>

pkgname=core-base
pkgver=1.0
pkgrel=1
pkgdesc="base script for core"
arch=('any')
license=('GPL')


package() {
       mkdir -p "$pkgdir/etc/"
       mkdir -p "$pkgdir/usr/share/"
       cp -rp core "$pkgdir/etc/core"
       cp -rp os-release "$pkgdir/etc/os-release"
       cp -rp zsh "$pkgdir/etc/zsh"
       cp -rp fonts "$pkgdir/usr/share/fonts"
       install -Dm755 -t "$pkgdir/usr/bin/" updates
       install -Dm755 -t "$pkgdir/usr/bin/" core-start 
}
