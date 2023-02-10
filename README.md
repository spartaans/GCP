#Kali installed on GCP

Add repo /etc/apt/source.list (https://www.kali.org/docs/general-use/kali-linux-sources-list-repositories/)
apt update
gpg --keyserver pgpkeys.mit.edu --recv-key ED444FF07D8D0BF6
gpg -a --export ED444FF07D8D0BF6 | sudo apt-key add -
apt upgrade
intsall metapackage (https://www.kali.org/docs/general-use/metapackages/)
