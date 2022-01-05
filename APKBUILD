# Reference: <https://postmarketos.org/devicepkg>
pkgname=linux-jeka-700rk8
pkgdesc="rockchip Jeka JK700"
pkgver=3.0.36
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="armv7"
options="!check !archcheck"
depends="
	linux-jeka-700rk8
	mesa-dri-gallium
	mkbootimg
	postmarketos-base
"
makedepends="devicepkg-dev"
source="https://github.com/Sai-desu/kernel_rk2926
	deviceinfo"
_repository="kernel_rk2926"
_commit="9784e8ae02b6ad72b3b2b1afb8abfca60e82ef52"
build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="
f0a81d2aa6e3b4e05233e84f87c54cd0d23d44759675af9342ad95bf44ed0c41e6d48f6030ddd0b601aca89a18ac4a63a2ef6f593a849f6c4ad3cc2b77146562  kernel_rk2926
"
