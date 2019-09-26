wget -O passbolt-ce-installer-ubuntu-18.04.tar.gz https://www.passbolt.com/ce/download/installers/ubuntu/latest
wget -O passbolt-installer-checksum https://www.passbolt.com/ce/download/installers/ubuntu/latest-checksum
sha512sum -c passbolt-installer-checksum
tar -xzf passbolt-ce-installer-ubuntu-18.04.tar.gz
sudo ./passbolt_ce_ubuntu_installer.sh
