# Local Manifests #
Just grab the manifest and sync to get device sources

### Tiramissu R-Vendor ###
```bash
git clone https://github.com/AthenaPrjk/local_manifests .repo/local_manifests
```

### SYNC ###
```bash
repo sync -j$(nproc --all) --force-sync
```