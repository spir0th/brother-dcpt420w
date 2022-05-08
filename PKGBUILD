# Maintainer: Gian Borcillo <borcillofg2020@gmail.com>

pkgname=brother-dcpt420w
pkgver=3.5.0_1
pkgrel=1
pkgdesc="Driver for Brother DCP T420w printer"
arch=("i686" "x86_64")
url="https://support.brother.com/g/b/downloadend.aspx?c=id&lang=en&prod=dcpt420w_all&os=128&dlid=dlf105168_000&flang=4&type3=10283"
license=("EULA")
depends=('cups')
source=("https://download.brother.com/welcome/dlf105168/dcpt420wpdrv-3.5.0-1.i386.deb")
md5sums=("847ed7d1da03935de6472ab1eb94e434")

package() {
    tar -xf data.tar.gz -C "${pkgdir}"
}
