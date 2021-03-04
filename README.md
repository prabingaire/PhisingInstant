<!-- Zphisher -->


<p align="center">A beginners friendly, Automated phishing tool with 30+ templates.</p>

##

### Features

- Latest and updated login pages.
- Mask URL support 
- Beginners friendly
- Docker support (checkout `docker-legacy` branch)
- Multiple tunneling options
  - Localhost
  - Ngrok (With or without hotspot)


### Installation

- Just, Clone this repository -
```
$ git clone git://github.com/prabingaire/PhisingInstant.git
```

- Change to cloned directory and run `zphisher.sh` -
```
$ cd PhisingInstant
$ bash zphisher.sh
```

- On first launch, It'll install the dependencies and that's it. `Zphisher` is installed.

### Run on Docker
```
$ docker pull htrtech/zphisher
$ docker run --rm -it htrtech/zphisher
```

### Dependencies

**`Zphisher`** requires following programs to run properly - 
- `php`
- `wget`
- `curl`
- `git`

> All the dependencies will be installed automatically when you run `Zphisher` for the first time.

> Supported Platform : **`Termux`**, **`Ubuntu/Debian/Kali`**, **`Arch Linux/Manjaro`**, **`Fedora`**

##

