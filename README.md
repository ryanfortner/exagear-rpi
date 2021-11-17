# exagear-rpi
installing Exagear Desktop on the newer Raspberry Pies

thanks to [this guide](https://insrt.uk/post/exagear-install)

### Installation Steps
First install prerequisites with `apt`
```
sudo apt-get update
sudo apt-get install -y bash coreutils findutils curl binfmt-support cron
```

Create a new directory (to download the packages and key)
```
mkdir ~/exagear
cd ~/exagear
```

