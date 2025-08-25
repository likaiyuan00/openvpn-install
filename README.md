mkdir -p  /etc/openvpn/      &&  cp -a deploy-example/openvpn/openvpn/*  /etc/openvpn/<br>
cp -a deploy-example/openvpn/*.service /etc/systemd/system/<br>
cp -a deploy-example/openvpn/client.ovpn /etc/openvpn/openvpn.conf && cp -a openvpn /usr/sbin/
