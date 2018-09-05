# docker
curl https://get.docker.com > /tmp/install.sh
chmod +x /tmp/install.sh
/tmp/install.sh
sestatus
setenforce 0
systemctl start docker
systemctl enable docker
docker version
