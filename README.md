# openvpn

apt install -y libnl-genl-3-dev libcap-ng-dev libssl-dev libpam0g-dev
autoreconf -vif
./configure --disable-lzo --disable-lz4
touch .gitignore .gitattributes
make

