The `pandoc-sidenote` was manually compiled on an Ubuntu 20.04 machine using:

```sh
sudo add-apt-repository ppa:hvr/ghc
sudo apt-get update
sudo apt install ghc-8.10.3
sudo apt install cabal-install-head
export PATH=/opt/ghc/8.10.3/bin:$PATH
git clone --depth=1 https://github.com/jez/pandoc-sidenote
cd pandoc-sidenote
stack build
stack install
mv ~/.local/bin/pandoc-sidenote assets/
```
