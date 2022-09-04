# tetrio_flatpak
A flatpak build of tetr.io

# Build instructions:

### Install flatpak-builder

    flatpak install org.flatpak.Builder

### Install dependincies

    flatpak install org.electronjs.Electron2.BaseApp/x86_64/21.08 org.freedesktop.Sdk/x86_64/21.08

### Build/install

    flatpak run org.flatpak.Builder --user --install build-dir io.tetr.tetr.io.yml
