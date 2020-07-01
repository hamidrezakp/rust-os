# An Educational OS written in Rust-lang.

## Installation
### Requirements
you need:
- qemu
- rust (nightly)
- cargo xbuild, bootlader

#### Qemu
in Archlinux:
```bash
pacman -S qemu qemu-arch-extra
```
in Ubuntu:
```bash
apt install qemu-kvm
```

#### Rust (nightly)
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
Note: while installation, select rust `Nightly` channel.
After installation is done, add this line to your shell config to load rust toolchain.
for Bash:
```bash
echo 'source $HOME/.cargo/env' >> ~/.bashrc
```

#### Cargo xbuild
```bash
cargo install cargo-xbuild bootimage
```

### Running Project in Qemu
```bash
cargo xrun
```
