# Mainteiner: Edoardo Maria Elidoro <edoardo.elidoro@gmail.com>
# Contributor: Shawn Dellysse <sdellysse@radford.edu>

pkgname=gtk-theme-clearlooks-bluecurve
pkgver=0.5.2
pkgrel=1
pkgdesc="A GTK2 theme that uses Bluecurve colors"
arch=('i686' 'x86_64')
depends=('gtk-engines')
url="http://www.gnome-look.org/content/show.php?content=22577"
license=('GPL')
source=(http://www.gnome-look.org/CONTENT/content-files/22577-Clearlooks-Bluecurve.tar.gz)
md5sums=('cddd4920907c1e84509354ae919b61ce')

package() {
	install -d -m755 $pkgdir/usr/share/themes
	cp -r $srcdir/Clearlooks-Bluecurve $pkgdir/usr/share/themes
}
