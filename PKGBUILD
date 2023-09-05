pkgname=webFinit
pkgver=1.0
pkgdesc="A simple package that helps you to create a frontend project scoff"
url="https://github.com/mohammadrostamiorg/webFinit"
arch=('any')
license=('MIT')
maintainer="Mohammad Rosstami <mohammad.jayant@gmail.com>"
source=("webFinit.sh" "vanila.txt" "tailwind.txt" 'bootstrap.txt')
depends=('bash' 'coreutils' 'tree')
pkgrel=1
sha256sums=('1d77bc1ff53991305760b2a3ce22cce2489932179bfd7f7973b6601613aab9b0'
            '8fc81d63ff86123e889ddffa9fcebb11fe0510bfa301031e57ebbf2e1d34b674'
            'a8fce3460227094d2a4e63044537b09e546ce8c37f6e8358566c27b8934869a0'
            '5930b05e4e60f30f27e6070aa6fde424e4bbe55d22a71a50124700cf7839c740')
package() {
  install -Dm755 webFinit.sh "${pkgdir}/usr/bin/webFinit";
   install -Dm644 vanila.txt "${pkgdir}/usr/share/${pkgname}/vanila.txt"
  install -Dm644 bootstrap.txt "${pkgdir}/usr/share/${pkgname}/bootstrap.txt"
  install -Dm644 tailwind.txt "${pkgdir}/usr/share/${pkgname}/tailwind.txt"
}


