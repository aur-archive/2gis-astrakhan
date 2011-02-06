# Contributor: stanislaw <i@archuser.pp.ru>

pkgname=2gis-astrakhan
pkgver=63
pkgrel=1
pkgdesc="Map of Astrakhan for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Astrakhan-${pkgver}.orig.zip")
md5sums=('19b25bd5a00c41e2aac86eaf2d8ea3fb')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Astrakhan.dgdat "${startdir}/pkg/opt/2gis/astrakhan.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Astrakhan.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Astrakhan.dglf" || return 1

}
