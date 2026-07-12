# Maintainer: Ngô Minh Vĩ (ngmvix2010_) <ngo.minhvi.04082010@gmail.com>
pkgname=penfetch
pkgver=1.0.1
pkgrel=1
pkgdesc="A simple and beautiful system fetch utility for PentaxiumOS"
arch=('any')
url="https://github.com/ngmvix2010/penfetch" # Sửa lại URL nếu ông có repo
license=('MIT')
depends=('python')
source=('penfetch')
md5sums=('SKIP')

package() {
    install -Dm755 "${srcdir}/penfetch" "${pkgdir}/usr/bin/penfetch"
}
