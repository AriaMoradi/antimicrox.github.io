# Installation

### Flatpak

The flatpak version is distributed on Flathub, and runs on most major Linux distributions. See instructions here: [Flathub application page](https://flathub.org/apps/details/io.github.antimicrox.antimicrox)

If you have Flathub [set up](https://flatpak.org/setup/) already:

```
flatpak install flathub io.github.antimicrox.antimicrox
```

### Fedora

```
dnf install antimicrox
```

### Arch Linux or Arch Linux based distributions:

```
trizen -S antimicrox
```
**or**

pre-built version can de downloaded from unofficial repository called [chaotic-aur](https://lonewolf.pedrohlc.com/chaotic-aur/).

Append (one of listed mirrors) to `/etc/pacman.conf`:
```bash
# Brazil
Server = http://lonewolf-builder.duckdns.org/$repo/$arch
# Germany
Server = http://chaotic.bangl.de/$repo/$arch
# USA (Cloudflare cached)
Server = https://repo.kitsuna.net/$arch
# Netherlands
Server = https://chaotic.tn.dedyn.io/$arch
```
To check signature, add keys:
```bash
sudo pacman-key --keyserver hkp://keyserver.ubuntu.com -r 3056513887B78AEB 8A9E14A07010F7E3
sudo pacman-key --lsign-key 3056513887B78AEB
sudo pacman-key --lsign-key 8A9E14A07010F7E3
```
Install package
```bash
pacman -S antimicrox
```

### Debian/Ubuntu-based distributions:

Download from the [release site](https://github.com/AntiMicroX/antimicrox/releases) and install `.deb` package.

### AppImage

Download from the [release site](https://github.com/AntiMicroX/antimicrox/releases).

It is recommended to use [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher) with this package.

### Building Yourself

List of required dependencies and build instructions can be found in [the next article](./building.md).