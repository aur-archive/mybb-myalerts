# Maintainer: Stefan Tatschner <stefan@sevenbyte.org>

pkgname=mybb-myalerts
_pkgname=MyAlerts
pkgver=1.05
pkgrel=2
pkgdesc="A simple notification/alert system for MyBB similar to IPB and XenForo's core implementations of user notifications"
install=mybb-myalerts.install
arch=('any')
url=('https://github.com/euantorano/MyAlerts')
license=('GPL')
depends=('mybb' 'mybb-pluginlibrary')
source=("git+https://github.com/euantorano/MyAlerts.git#commit=6c78d452ad1f09ad6bd79d6dba849dc736bed438")
md5sums=('SKIP')

package() {
  mkdir -p ${pkgdir}/usr/share/webapps/mybb/

  cp -ra ${srcdir}/${_pkgname}/{images,inc,jscripts} ${pkgdir}/usr/share/webapps/mybb/
}
