# autoscript

Step 1 : <br>

```shell
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

Step 2 : <br><br>
```shell
rm -rf setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils wget screen curl && wget https://raw.githubusercontent.com/kevindoni/coba/main/kota/setup.sh && chmod +x setup.sh && ./setup.sh
```

# build up
oleh     : KEVIN DONI <br>
whatsapp : wa.me/082243698398 <br>
telegram : t.me/kevindoni
# Fitur
[![Watch the video](vd.gif)

![Screenshot](20211222_150713.jpg)
