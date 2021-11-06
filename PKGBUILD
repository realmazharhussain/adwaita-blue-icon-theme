# This is an example PKGBUILD file. Use this as a start to creating your own,
# and remove these comments. For more information, see 'man PKGBUILD'.
# NOTE: Please fill out the license field for your package! If it is unknown,
# then please put 'unknown'.

# Maintainer: Your Name <youremail@domain.com>
pkgname=adwaita-blue-icon-theme
pkgver=1.0.0
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
