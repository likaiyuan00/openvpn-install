mkdir -p  /etc/openvpn/      &&  cp -a deploy-example/openvpn/openvpn/*  /etc/openvpn/
cp -a deploy-example/openvpn/*.service /etc/systemd/system/
cp -a deploy-example/openvpn/client.ovpn /etc/openvpn/openvpn.conf
