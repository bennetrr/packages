# bennetrr packages
A repository for package repositories

## APT
The apt repository (on https://bennetrr.github.io/packages/apt) holds the debian packages. Currently in this repository:
- bupdate

### Add this repository
Run the following commands:
```
curl -s --compressed "https://bennetrr.github.io/packages/apt/KEY.gpg" | sudo apt-key add -
echo "deb https://bennetrr.github.io/packages/apt ./" | sudo tee /etc/apt/sources.list.d/bennetrr.list >/dev/null
sudo apt update
```
