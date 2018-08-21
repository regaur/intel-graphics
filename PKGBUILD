# Maintainer: Jan Boelsche <jan@lagomorph.de>

pkgname='intel-graphics'
pkgver=1.1
pkgrel=1
pkgdesc="Drivers and tests for Intel's embedded graphics"
packager='Jan Boelsche'
arch=('x86_64')
license=('GPL')
groups=()
depends=(
  'mesa'
  'mesa-demos'
  'xf86-video-intel'
  'vulkan-intel'
)
source=('20-intel.conf')
sha256sums=('d58507524fb878c3ee802d26b6ebaa31e26989e6ac87dc16084cef4b97651e52')

package () {
  install -Dm 644 -t ${pkgdir}/etc/X11/xorg.conf.d 20-intel.conf
}
