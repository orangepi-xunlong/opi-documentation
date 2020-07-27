# OPi Documentation

[Read me online](https://kprasadvnsi.gitlab.io/opi-documentation/)

Documentation for Orange Pi Boards.

## Build Doc


This documentation site is powered by [Hugo](https://gohugo.io/).

You need Hugo Extended v0.73.0 to be able to build the site.

Download Hugo-extended from here.

https://github.com/gohugoio/hugo/releases/tag/v0.73.0

Get Doc source code:
```
sudo apt install git 
git clone https://gitlab.com/kprasadvnsi/opi-documentation.git
```

Install submodules:

```
cd opi-documentation
git submodule init
git submodule update
```

Serve as a website:

```
hugo server
```

Then visit http://localhost:1313
