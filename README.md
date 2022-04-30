Does some common machine configs I like:

- Install a bunch of apt packages
- Add the user to the docker group
- Sets default user shell to zsh
- Installs tailscale VPN
- Pulls my dot-files repo
- Runs the linker for .zsh/vim rc

`ansible-playbook -i inventory.txt ubuntu_install.yml -K -u s`
