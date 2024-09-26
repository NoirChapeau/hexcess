# hexcess
## Description
> [!WARNING]
> Hexcess is still in its early phase, therefore a lot of features are missing
> for now. Please keep that in mind when using Hexcess!

hexcess is a (yet another) Ncurses-based hex viewer, and soon editor as well.
It supports basics VIM keybindings for navigating through the hexdump more
easily, more will be supported soon.

![Screenshot of hexcess](assets/screen.png)

## Build
```bash
git clone https://github.com/jeanmadao/hexcess.git
make
```

## Run
```bash
./hexcess <filename>
```

## Roadmap
- [x] Ncurses interface to view and navigate the hexdump
- [ ] Editing of the file
- [ ] Accept a XOR key for encryption/decryption
