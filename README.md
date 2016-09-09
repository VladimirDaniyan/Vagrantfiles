## Vagrantfile.centos7
This uses [vagrant-unison2](https://github.com/dcosson/vagrant-unison2) for bi-directional syncing.

A number of dependencies are installed to aid in kernel development and a setting up the kernel tracing tool, [bcc](https://github.com/iovisor/bcc)[1].

[1] A kernel needs to be compiled with (e)BPF