# kubernetes
Kubernetes playground

## 国内镜像
vagrant box add https://mirrors.ustc.edu.cn/centos-cloud/centos/7/vagrant/x86_64/images/CentOS-7.box --name centos/7

## Vagrant + Docker set up

https://blog.zenika.com/2014/10/07/setting-up-a-development-environment-using-docker-and-vagrant/

## Virtualbox Guest Additions to my centos7 box.

```shell
vagrant plugin install vagrant-vbguest
vagrant vbguest --do install --no-cleanup
```
