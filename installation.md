Download the source code: [click here](https://github.com/NetSys/bess/releases/download/v0.3.0/bess-x86-64-linux.tar.gz).

```
$ sudo apt-get install -y python python-pip python-scapy libgraph-easy-perl
$ pip install grpcio
$ sudo sysctl vm.nr_hugepages=1024  # For single NUMA node systems
$ tar -xf bess-core2-linux.tar.gz
$ cd bess/
$ make -C core/kmod # Build the kernel module
$ bessctl/bessctl
```
