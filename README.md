# pi-rclone-beta-install

This is a fast install procedure for rclone in the raspberry pi (tested with OSMC on a Pi 2) with support for auth proxy that enable Amazon Cloud drive access.

Install from precompiled binarys (not need to install go-lang):

* Download the relevant binary.

```bash
curl -O https://beta.rclone.org/rclone-beta-latest-linux-arm.zip
```

* unpack:

```bash
unzip rclone-beta-latest-linux-arm.zip
```

* install

```bash
cd rclone-v1.36-235-g51866fbdβ-linux-arm/
sudo cp rclone /usr/bin/
sudo chown root:root /usr/bin/rclone
sudo chmod 755 /usr/bin/rclone
```

* run config

```bash
 rclone config
```

your rclone config file will be at: ~/.config/rclone/rclone-config


links:

[rclone install](https://rclone.org/install/)

[Proxy for Amazon Cloud Drive](https://forum.rclone.org/t/proxy-for-amazon-cloud-drive/28489)
