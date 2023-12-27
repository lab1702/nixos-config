# nixos-config

My NixOS configuration files

## Download file

    curl https://raw.githubusercontent.com/lab1702/nixos-config/main/configuration.nix -o configuration.nix

## Uncomment one of the boot loader options before copying to /etc/nixos

    sudo cp configuration.nix /etc/nixos/configuration.nix
    sudo nixos-rebuild switch
