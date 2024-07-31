## Installation

- If your server's OS: Enterprise Linux 8 / 9
```bash
yum -y install wget git
git clone https://github.com/bibicadotnet/lcmp-teddysun
cd lcmp
chmod 755 *.sh
./lcmp.sh 2>&1 | tee lcmp.log
```

- If your server's OS: Debian 10+ / Ubuntu 20.04+
```bash
apt-get -y install wget git
git clone https://github.com/bibicadotnet/lcmp-teddysun
cd lcmp
chmod 755 *.sh
./lcmp.sh 2>&1 | tee lcmp.log
```
