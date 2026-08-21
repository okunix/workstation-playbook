# Workstation Playbook

workstation configuration playbook

```bash
# create a configuration file and adjust it to your needs
cp config.default.yml config.yml

# run playbook
ansible-playbook -K local.yml
```

Available tags:
- package
- flatpak
- firewall
- sudo
- sshd
