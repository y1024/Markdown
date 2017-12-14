# XMR 
**门罗币**

[xmr](https://github.com/y1024/xmr-stak-cpu)

**centos6.x**

```
yum -y install hwloc libmicrohttpd screen
git clone https://github.com/y1024/xmr-stak-cpu.git && cd ./xmr-stak-cpu/bin/
&& chmod +x xmr-stak-cpu 
sysctl -w vm.nr_hugepages=128
echo "vm.nr_hugepages=128" >> /etc/sysctl.conf
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

#### cmake3

1. [CMake 3.x for Centos 7, Red Hat Linux 7 ( Epel 7 )
](https://www.heliocastro.info/?p=238)

2. [centos安装gcc6](http://shibing.github.io/2017/07/25/centos%E5%AE%89%E8%A3%85gcc6/)