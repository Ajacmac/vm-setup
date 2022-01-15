**My Setup Steps for New VM's**

*WIP*

- Run updates
- Setup fail2ban
- Change SSH Port to 50000
- Setup firewall to only allow incoming on ports in use, assigned to the following ranges
    - System services (like SSH) from       50000-50009
    - User-facing services                  50010-50019
    - Machine-facing services               50020-50029
    - DB's                                  50030-50039




**Todo**

Write 2 scripts
- one to execute the steps above
- the other to generate this README.md from the comments in that script
