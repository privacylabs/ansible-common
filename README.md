# Overview
The common role handles basic system tasks like ensuring packages are up to date
on the host its running on and installing basic tools like git, zip and ntp. As
a general precaution, fail2ban is installed as well to help secure hosts from
remote brute force attacks.

# Dependencies
None

# Variables
```yaml
- vars:
  fail2ban_postfix: [true|false] #enable for postfix
  fail2ban_nginx: [true|false] #enable for nginx
  fail2ban_dovecot: [true|false] #enable for dovecot
```
