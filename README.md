Simple clone

```
git clone --depth=1 https://github.com/topnotchfreaks/local_manifests .repo/local_manifests
```
Then
```
repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j$(nproc --all)
```
