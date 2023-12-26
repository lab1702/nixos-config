# nixos-config

My NixOS configuration files

Initial config on fresh installation of NixOS

    cd
    nix-env -i git
    git clone https://github.com/lab1702/nixos-config.git
    cd nixos-config
    sudo cp configuration.nix /etc/nixos/configuration.nix
    cd /etc/nixos
    sudo nixos-rebuild switch
