# docker

修改docker源
cat > /etc/docker/daemon.json << EOF
{
  "registry-mirrors": ["https://pmyelo.mirror.aliyuncs.com"]
}
EOF

