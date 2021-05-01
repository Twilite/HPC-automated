__Don't__ deploy at production site (they hardly function)
## Introduction
Environment: CentOS/EL 7.5  
This repo plans to automate maintenance routines of HPC (High-perf Computing):
- dnsmasq
- chrony
- openldap-clients/servers
- httpd
- nfs-utils
- gcc-c++
- [slurm](https://github.com/SchedMD/slurm)
- manage services by systemctl

## Usage
`ansible-playbook -C target.yml` to first test possible outcome, always recommended to add the "check" `-C` flag.
## License
Playbooks subject to MIT license.
