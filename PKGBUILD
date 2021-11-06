# Maintainer: Mazhar Hussain <mmazharhussainkgb1145@gmail.com>
pkgname=adwaita-blue-icon-theme
pkgver=1.0.1
pkgrel=1
pkgdesc="Adwaita icon theme with blue folder icons"
arch=(any)
url="https://github.com/realmazharhussain/adwaita-blue-icon-theme"
license=('GPL')
depends=(adwaita-icon-theme)

package() {
   mkdir -p "$pkgdir"/usr/share/icons
   cp -Rt "$pkgdir"/usr/share/icons ../Adwaita-Blue
}
