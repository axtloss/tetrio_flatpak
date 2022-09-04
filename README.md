# tetrio_flatpak
A flatpak build of tetr.io

# Build instructions:

### Install flatpak-builder

Debian:

    sudo apt install flatpak-builder

Arch:

    sudo pacman -S flatpak-builder

Fedora: 

    sudo dnf install flatpak-builder

### Install dependincies

    flatpak install org.electronjs.Electron2.BaseApp/x86_64/21.08 org.freedesktop.Sdk/x86_64/21.08

### Build/install

    flatpak-builder --install build-dir io.tetr.tetr.io.yml

If you get the error `flatpak system operation ConfigureRemote not allowed for user`, run command above with root perms
