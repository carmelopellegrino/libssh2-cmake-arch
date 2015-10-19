#$Id$
# Maintainer: Carmelo Pellegrino <carmelo.pellegrino@gmail.com> 
# Contributor: Carmelo Pellegrino <carmelo.pellegrino@gmail.com> 

pkgname=libssh2-cmake-modules
pkgver=1.0.0
pkgrel=1
pkgdesc='libssh2 modules and scripts for CMake'
arch=('any')
url='https://github.com/carmelopellegrino/libssh2-cmake'

license=('LGPL')
depends=('cmake')
#source=("https://github.com/carmelopellegrino/libssh2-cmake.git")
source=("https://github.com/carmelopellegrino/libssh2-cmake/archive/master.zip")

md5sums=('b5472a7591660b073bb61e699be6a5e4')

package() {
  mkdir -p "${pkgdir}/usr/lib/cmake/libssh2"
  cp libssh2-cmake-master/*.cmake ${pkgdir}/usr/lib/cmake/libssh2/
}
