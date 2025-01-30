# deb2xbps
changing deb files to xbps

1. Install dependencies: xbps-install binutils tar curl xbps xz
2. Download this repo
3. chmod +x deb2xbps
4. Convert: ./xdeb -Sedf {package}
5. Install: xbps-install -R ./binpkgs {package_name}
