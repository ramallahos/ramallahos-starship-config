# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-starship-config
pkgver=1
pkgrel=1
pkgdesc="Starship prompt config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=('starship')
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -d "${pkgdir}/etc/skel/.config/"
    install -Dm 644 "starship.toml" "${pkgdir}/etc/skel/.config/starship.toml"
}
