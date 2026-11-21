# pacman-for-aeryn

A Fish shell wrapper providing `pacman`-style syntax for `moss` on aerynOS.
(It's still WIP I'm sorry, the basic functions are there tho like -S, -Syu, -R and -Rns)

## Installation

Add the repository and install `pacman-for-aeryn`:

``sudo moss repo add pacman-aeryn https://raw.githubusercontent.com/g1ftb0xz/pacman-for-aeryn/main/repo/x86_64/stone.index -p 50``

``sudo moss sync -u``

``sudo moss pkg add pacman-for-aeryn``

## Building from Source

sudo boulder build stone.yaml

# Disclaimers!

This package does **NOT** give you Arch packages. It is merely just a wrapper that translates Arch Linux ``pacman`` syntax into aerynOS ``moss`` syntax.
