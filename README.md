# How to use for build custom ROM?

```bash
.repo/local_manifests
git clone https://github.com/SenseiDEVLinux/local_manifests -b <your branch> .repo/local_manifests
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```