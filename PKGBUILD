pkgname=2gis-astrakhan
pkgver=103
pkgrel=1
pkgdesc="Map of Astrakhan for 2GIS, June 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/astrahan/products/download#linux"
license=('custom')
depends=('2gis>=3.14.6.0')
source=("http://download.2gis.com/arhives/2GISData_Astrakhan-103.orig.zip")
md5sums=('e78e3ac0b1690fdc434d0fc7b3619ec5')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Astrakhan.dgdat" "${pkgdir}/opt/2gis/2gis-astrakhan.dgdat" || return 1
  
}
