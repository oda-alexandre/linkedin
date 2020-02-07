# LINKEDIN

## INDEX

- [LINKEDIN](#linkedin)
  - [INDEX](#index)
  - [INTRODUCTION](#introduction)
  - [INSTALL](#install)
- [](#)
  - [LICENSE](#license)

## INTRODUCTION

This repository contains a script for automated Linkedin

## INSTALL

# 

```git clone https://gitlab.com/oda-alexandre/linkedin.git ~/linkedin```

- Moving the script in the folder /etc/init.d/

```mv -f ~/linkedin/auto-clean /etc/init.d/```

- Make the script executable

```chmod +x /etc/init.d/auto-clean```

- Automatic startup of the script

```update-rc.d -f auto-clean defaults```

- Remove installation residues

```rm -rf ~/linkedin```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/linkedin/blob/master/LICENSE)
