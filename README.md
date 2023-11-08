<p align="center">
  <img src="https://i.imgur.com/32ihEhr.png"/>
</p>

### Initiate ###
```bash
        repo init -u https://github.com/VoltageOS-staging/manifest.git -b 14
```

### Sync ###
```bash
        repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
```

### Setup Build ###
```bash
	. build/envsetup.sh
```

### Build ###
```bash
        brunch device
```
[![TG chat](https://img.shields.io/badge/Support-Telegram-%23e52c5f.svg?style=for-the-badge&logo=telegram&&labelColor=121217)](https://t.me/voltageos)
