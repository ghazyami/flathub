# org.kse.KeyStoreExplorer
Flatpak for [KeyStore Explorer](https://keystore-explorer.org)

## Prerequisite

- `flatpak`, `flatpak-builder` packages
- Runtime `org.freedesktop.Platform` version `24.08`
- Runtime `org.freedesktop.Sdk` version `24.08`
- Runtime Extension `org.freedesktop.Sdk.Extension.openjdk`

### Build and install KeyStore Explorer
```bash
flatpak-builder --user --install --force-clean  flatpakbuildir org.kse.KeyStoreExplorer.yml
```
### Run KeyStore Explorer
```bash
flatpak run org.kse.KeyStoreExplorer
```
### Uninstall KeyStore Explorer
```bash
flatpak uninstall --user org.kse.KeyStoreExplorer
```
