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
sha256sums=('289ae38b48cf4bbee00f655d34fb9a2c3bee92d20d12132caa92cc5dc692b714')

prepare() {
    rm "${srcdir}/${pkgname}.rpm"
}

package() {
    mv "${srcdir}"/* "${pkgdir}"
}
