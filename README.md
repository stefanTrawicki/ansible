Does some common machine configs I like:

- Install a bunch of apt packages
- Add the user to the docker group
- Sets default user shell to zsh
- Installs tailscale VPN

`ansible-playbook -i inventory.txt ubuntu_install.yml -K -u s`