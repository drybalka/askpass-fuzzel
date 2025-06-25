pkgname=askpass-fuzzel
pkgver=1.0.0
pkgrel=1
pkgdesc="Simple password entry menu based on fuzzel for SSH askpass"
arch=('any')
url="https://github.com/drybalka/askpass-fuzzel"
license=('MIT')
depends=('fuzzel')

package() {
    cd ..
    install -Dm755 "askpass-fuzzel" "$pkgdir/usr/bin/askpass-fuzzel"
    install -Dm644 "LICENSE" "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
    install -Dm644 "README.md" "$pkgdir/usr/share/doc/$pkgname/README.md"
}
