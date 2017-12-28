# XMR 
**门罗币**

[xmr](https://github.com/y1024/xmr-stak-cpu)

**锐速**

```
wget --no-check-certificate -O appex.sh https://raw.githubusercontent.com/0oVicero0/serverSpeeder_Install/master/appex.sh && chmod +x appex.sh && bash appex.sh install '2.6.32-642.el6.x86_64'

```

**centos6.x**

```
yum -y install epel-release hwloc libmicrohttpd screen git
git clone https://github.com/y1024/xmr-stak-cpu.git && cd ./xmr-stak-cpu/bin/
chmod +x xmr-stak-cpu
sysctl -w vm.nr_hugepages=128 && echo "vm.nr_hugepages=128" >> /etc/sysctl.conf
screen ./xmr-stak-cpu

```

```
cd /etc/yum.repos.d/ && wget https://copr.fedoraproject.org/coprs/hhorak/devtoolset-4-rebuild-bootstrap/repo/epel-6/hhorak-devtoolset-4-rebuild-bootstrap-epel-6.repo && yum clean all && cd ~ && yum -y update && yum -y install epel-release && yum -y install wget git screen centos-release-scl cmake3 hwloc-devel libmicrohttpd-devel openssl-devel devtoolset-4-gcc*  && scl enable devtoolset-4 bash && git clone https://github.com/y1024/xmr-stak-cpu.git && cd ./xmr-stak-cpu 


```

## 矿池推荐

1. [supportxmr](https://supportxmr.com)



### 参考链接
#### xmr
1. [Monero Mining Hardware](https://www.buybitcoinworldwide.com/mining/hardware/monero/)
2. [xmr](https://github.com/fireice-uk/xmr-stak-cpu)
3. [GCC version must be at least 5.1! but gcc 6.3.0](https://github.com/fireice-uk/xmr-stak-cpu/issues/206)
4. [Best setting and max h/s on Ryzen 7 1700](https://github.com/fireice-uk/xmr-stak-cpu/issues/381)
5. [Monero Mining with xmr-stak-cpu on Ubuntu 16.04](https://www.cryptocurrencyfreak.com/2017/08/22/monero-mining-xmr-stak-cpu-ubuntu-16-04/)
6. [Xeon D-1540 got "Your CPU doesn't support hardware AES. Don't expect high hashrates" issue](https://github.com/fireice-uk/xmr-stak-cpu/issues/152)
7. [GPU & CPU BENCHMARKS FOR MONERO MINING!](http://monerobenchmarks.info/)
8. [minergate](https://minergate.com)

#### cmake3
1. [CMake 3.x for Centos 7, Red Hat Linux 7 ( Epel 7 )
](https://www.heliocastro.info/?p=238)

2. [centos安装gcc6](http://shibing.github.io/2017/07/25/centos%E5%AE%89%E8%A3%85gcc6/)

#### pip
1. [How to install pip on CentOS / RHEL / Ubuntu / Debian](http://sharadchhetri.com/2014/05/30/install-pip-centos-rhel-ubuntu-debian/)
2. [How to install pip and easy_install on CentOS](https://superuser.com/questions/292378/how-to-install-pip-and-easy-install-on-centos)