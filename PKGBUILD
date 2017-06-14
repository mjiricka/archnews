pkgname=archnews2
pkgver=0.0.1
pkgrel=1
pkgdesc="Utility for displaying Arch news feed in console"
arch=("any")
url="https://github.com/mjiricka/archnews"
license=("MIT")
depends=("python")
conflicts=("archnews")
source=("https://github.com/mjiricka/archnews/archive/v${pkgver}.tar.gz")
md5sums=("5c2c81c5880d6851dd0f150cdea572ab")

package() {
    cd "${srcdir}/${pkgname%2}-${pkgver}"

    # Binaries.
    mkdir -p ${pkgdir}/usr/bin/
    install archnews archnews_wrap ${pkgdir}/usr/bin/

    # Man pages.
    mkdir -p ${pkgdir}/usr/share/man/man1/
    install archnews.1 ${pkgdir}/usr/share/man/man1/archnews.1
}

