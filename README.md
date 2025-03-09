# docker-20.10

git clone -b 20.10 https://github.com/docker/cli.git
git clone -b 20.10 https://github.com/moby/moby.git

#0.19
git clone https://github.com/krallin/tini.git

cd tini

git checkout  de40ad0

#1.4.3
https://github.com/containerd/containerd

cd containerd

git checkout  269548f

#runc 1.0-rc91
git clone https://github.com/opencontainers/runc

cd runc

git checkout  24a3cf8
