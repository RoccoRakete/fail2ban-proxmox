### [Documentation](https://wiki.ubuntuusers.de/fail2ban/)


`apt update`

`apt install fail2ban`

`systemctl restart fail2ban`

`fail2ban-regex systemd-journal /etc/fail2ban/filter.d/proxmox.conf`

use `fail2ban-client unban <IP>` to unban when locked out
