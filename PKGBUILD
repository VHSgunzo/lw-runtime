# Maintainer: VHSgunzo <vhsgunzo.github.io>

pkgname='lw-runtime'
pkgver='0.0.3'
pkgrel='1'
pkgbase="$pkgname"
pkgdesc='Wine runtime libraries for Lux Wine'
url="https://github.com/VHSgunzo/lw-runtime"
arch=('x86_64')
license=('MIT')
source=("https://raw.githubusercontent.com/VHSgunzo/lw-runtime/main/runtime.tar.zst")
sha256sums=('SKIP')

package() { install -Dm644 'runtime.tar.zst' "$pkgdir/opt/lwrap/runtime.tar.zst" ; }
