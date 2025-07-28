# Librefox

A browser that intends to be a sweet spot for people that seek the maximum amount of privacy that can be achieved by a web browser without seriously breaking any websites.

I have always been looking for a perfect web browser, for me, but I have found none that are what I perceive as a perfect browser. Thus I decided to build my own fork of web browser. And this is how I build Librefox.

## Installation

Add librefox repo, the following lines, to /etc/pacman.conf

```
[librefox_arch]
SigLevel = Optional DatabaseOptional
Server = https://github.com/librefox05/$repo/raw/refs/heads/main/$arch
```

then run

```
sudo pacman -Syy librefox
```

## Contribute

To contribute, open a pr. Read our commiting [guide](./COMMIT.md) beforehand

## Credits

- [Librewolf](https://librewolf.net): For patches and idea
- [Mozilla](https://www.mozilla.org): For making such an easy-to-customize browser
