pkgname=chord2html
pkgver=1.3
pkgrel=2
pkgdesc='A small Perl script to convert CHORD input files (the .chopro files in OLGA) to HTML'
arch=('any')
url='http://www.freshports.org/misc/chord2html/'
license=('GPL')
depends=('perl' 'perl-gd')
makedepends=('gzip' 'tar' 'coreutils')
options=('zipman')
source=("ftp://ftp.freebsd.org/pub/FreeBSD/ports/distfiles/$pkgname-$pkgver.tar.gz")
md5sums=('fcbca77921bb1ad03b82416b0b4c3e63')

package() {
   cd $srcdir/$pkgname-$pkgver
   install -Dp -m755 $pkgname $pkgdir/usr/bin/$pkgname
   install -Dp -m644 $pkgname.1 $pkgdir/usr/share/man/man1/$pkgname.1
}
