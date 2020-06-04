# ssh-monitor-ban

Monitors auth.log and auto bans ips

## Files to work with

- /var/log/auth.log
- /etc/hosts.deny

### Idea

Checks auth.log for messages and bans ips with hosts.deny

### Scripts

- reset_ssh_bans - resets hosts.deny file
- ban_ssh - adds ip to the ban list
- monitor_ssh - monitors auto.log
