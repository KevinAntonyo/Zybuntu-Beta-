# Zybuntu Beta
This is just a debloated,better looking fork of Ubuntu
(still uses soystemD...)

sudo rm -rf /etc/upstream-release/lsb-release
echo 'DISTRIB_ID=Zybuntu
DISTRIB_RELEASE=1.2
DISTRIB_CODENAME=swift
DISTRIB_DESCRIPTION="Zybuntu 1.2 LTS"' | sudo tee /etc/upstream-release/lsb-release