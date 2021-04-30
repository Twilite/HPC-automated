Don't deploy at production site (they barely function)
# Introduction
Environment: CentOS/EL 7.5  
This repo plan to automate:
- dnsmasq
- chrony
- openldap
- slurm
- httpd

# Usage
`ansible-playbook -C target.yml`, It's always recommended to add the check `-C` flag.
# License
MIT

