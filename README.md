# Inofficial Infomaniak Aur Packages

This repo builds packges for AUR.

## Packages

| Application name | AUR | Current version | AppImage path |
|-|-|-|-|
| [kChat](https://www.infomaniak.com/en/kchat) | [kChat](https://aur.archlinux.org/packages/kchat-appimage) | 3.3.2 | https://download.storage5.infomaniak.com/kchat/kchat-desktop-3.3.2-linux-x86_64.AppImage |
| [kDrive](https://www.infomaniak.com/en/kdrive) | [kDrive](https://aur.archlinux.org/packages/kdrive-appimage) | 3.6.3.20240807 | https://download.storage.infomaniak.com/drive/desktopclient/kDrive-3.6.3.20240807-amd64.AppImage |
| [kMeet](https://www.infomaniak.com/en/kmeet) | [kMeet](https://aur.archlinux.org/packages/kmeet-appimage) | 2.0.1 | https://download.storage5.infomaniak.com/meet/kmeet-desktop-2.0.1-linux-x86_64.AppImage |


## Maintain

1. Download new AppImage
1. Get SHA256 sum with `sha256sum package.AppImage`
1. Adjust `pkgver` and `sha256sums_x86_64` in `PKGBUILD`
1. Update `.SRCINFO` with `makepkg --printsrcinfo > .SRCINFO`
1. Push
