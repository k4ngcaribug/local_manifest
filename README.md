# Clone Source:

```bash
git clone -b master https://github.com/k4ngcaribug/local_manifest --depth=1 .repo/local_manifests
```
# Then to sync up:
```
repo sync -c --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune
