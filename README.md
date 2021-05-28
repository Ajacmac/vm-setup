**My Setup Steps for New VM's**

*WIP*

- Run updates
- Setup fail2ban
- Change SSH Port to 50000
- Setup firewall to only allow incoming on ports in use
    - System services (like SSH) from       50000-50009
    - User-facing services                  50010-50019
    - Machine-facing services               50020-50029
    - DB's                                  50030-50039


