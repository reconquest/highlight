pkgname="highlight"
pkgver=autogenerated
pkgrel=1
pkgdesc="easy interface to bash (terminal) escape codes highlighting"
url="https://github.com/reconquest"
arch=('any')
license=('GPL')
makedepends=()
source=(highlight::git://github.com/reconquest/highlight.git)
md5sums=(SKIP)

pkgver() {
    cd "${pkgname}"
    echo $(git rev-list --count master).$(git rev-parse --short master)
}

build() {
    :
}

package() {
    mkdir "$pkgdir/bin/"

    install -DT \
        "$srcdir/$pkgname/highlight" \
        "$pkgdir/bin/highlight"
}