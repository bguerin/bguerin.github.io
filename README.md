bguerin.github.io
============================

This is my personnal site. It mainly contains my personnal [Debian](https://www.debian.net/) [repository](http://bguerin.github.io/debian/).

## Usage

Add source
```
echo "deb http://bguerin.github.io/debian wheezy main" > /etc/apt/sources.list.d/bguerin.list
```

Update sources
```
apt-get update
```

Install my public key
```
apt-get install benoitguerin-keyring
```

Feel free to use any package in my repository !

## CI
[![Build Status Images](https://travis-ci.org/bguerin/bguerin.github.io.svg)](https://travis-ci.org/bguerin/bguerin.github.io)

## License

This is all under [GPL-2](http://www.gnu.org/licenses/gpl-2.0.html)
