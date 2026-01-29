# Getting Started
To initialize your device trees setup, use command:

```bash
git clone -b Infinity-16 https://github.com/ikwfahmi/local_manifests.git .repo/local_manifests
```

Then sync with ROM source or sync standalone with this command:
```bash
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

**Credit:**
- [Crave](https://foss.crave.io)
- [sounddrill31](https://github.com/sounddrill31)
