# Maintainer: Edoardo Maria Elidoro <edoardo.elidoro@gmail.com>
# Contributor: SiD/sidious <miste7@web.de>

pkgname=slim-theme-archgreenglow
pkgver=1.0
pkgrel=2
pkgdesc="Slim theme for ArchLinux"
license=('custom')
arch=('i686' 'x86_64')
url="https://sourceforge.net/projects/archgreenglow/"
depends=('slim' 'ttf-freefont')
install='archgreenglow.install'
source=(http://sourceforge.net/projects/archgreenglow/files/$pkgname-$pkgver.tar.gz)


package() {
  cd $srcdir/$pkgname/$pkgver
  
  install -m 644 -D background.png $pkgdir/usr/share/slim/themes/archgreenglow/background.png
  install -m 644 -D panel.png $pkgdir/usr/share/slim/themes/archgreenglow/panel.png
  install -m 644 -D slim.theme $pkgdir/usr/share/slim/themes/archgreenglow/slim.theme

  install -m 755 -d $pkgdir/usr/share/licenses/$pkgname
  install -m 644 -D LICENSE $pkgdir/usr/share/licenses/$pkgname/
}

md5sums=('b0c2c8d2d612b1e215ff6907fb8b66ec')
