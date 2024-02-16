Prerequisites


sudo mkdir -p /etc/vbox/
echo '* 0.0.0.0/0 ::/0' | sudo tee -a /etc/vbox/networks.conf
