# armhf-x2go
Armhf binaries for x2go (ARMv7)

#### Versions

x2go-server: 4.0.1.19

nx-libs: 3.5.0.32

x2go-agent: 3.5.0.32

## Installation

#### Clone the repo

git clone https://github.com/kapolos/armhf-x2go.git

#### Install prereqs

(on a root shell or with sudo)
````
apt-get install libc6 lsof bc openssh-server openssh-client libconfig-simple-perl pwgen libdbd-pg-perl libdbd-sqlite3-perl libfile-basedir-perl libcapture-tiny-perl adduser xauth psmisc net-tools sshfs x11-apps x11-session-utils x11-utils x11-xfs-utils x11-xkb-utils x11-xserver-utils fontconfig xinit xfonts-base x11-common
````

#### Install 

(on a root shell or with sudo)
````
cd armhf-x2go
dpkg -i ./*
apt-get -f install
dpkg -i x2goserver_*.deb x2goserver-xsession_*.deb x2goserver-extensions_*.deb
````
