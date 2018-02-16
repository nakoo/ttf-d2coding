pkgname=ttf-d2coding
pkgver=1.3.1
_pkgver=Ver1.3.1-20180115
_pkgname=D2Coding-${_pkgver}
pkgrel=1
pkgdesc="D2Coding Fixed Width TrueType fonts"
arch=('any')
url="https://github.com/naver/d2codingfont"
license=('OFL')
depends=('fontconfig' 'xorg-font-utils')
provides=('ttf-font')
install=ttf.install
source=(https://github.com/naver/d2codingfont/releases/download/VER${pkgver}/${_pkgname}.zip)
md5sums=('SKIP')

package() {
  install -d "${pkgdir}/usr/share/fonts/${pkgname}"
  install -t "${pkgdir}/usr/share/fonts/${pkgname}" -m644 ${_pkgname}/D2Coding/${_pkgname}.ttc
}

