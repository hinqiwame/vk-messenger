# Maintainer: hinqiwame (https://github.com/hinqiwame)

pkgname=vk-messenger
pkgver=6.0.44
pkgrel=277
pkgdesc="VK Messenger for Linux"
arch=('x86_64')
url="https://vk.com/messenger"
license=('custom')
depends=('alsa-lib' 'expat' 'gtk3' 'libgcrypt' 'libgnome-keyring' 'libnotify' 'libxss' 'libxtst' 'nss' 'xdg-utils')
optdepends=('gnome-keyring')
source=("https://upload.object2.vk-apps.com/vk-me-desktop-dev-5837a06d-5f28-484a-ac22-045903cb1b1a/latest/vk-messenger.rpm")
sha256sums=('da4c6a78067410a80b23fbead4135ba99a153872f553fc70d4bc0d21406e7049')

prepare() {
    rm "${srcdir}/${pkgname}.rpm"
}

package() {
    mv "${srcdir}"/* "${pkgdir}"
}
