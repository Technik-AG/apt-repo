# Technik-AG APT-Repository

[![Build Status](https://travis-ci.com/Technik-AG/apt-repo.svg?branch=deploy)](https://travis-ci.com/Technik-AG/apt-repo)

Eine APT-Repository für Pakete der Technik-AG

## Inhalt

* [`wifi-autoconnect`](https://github.com/Technik-AG/wifi-autoconnect)
* [Alle Pakete aus `configuration-packages`](https://github.com/Technik-AG/configuration-packages)

## Installation

Zum benutzen der Repository kann das Paket `t-ag-apt-repository` von [`https://technik-ag.github.io/apt-repo/repo.deb`](https://technik-ag.github.io/apt-repo/repo.deb) herunterladen und installiert werden:

```shell
wget https://technik-ag.github.io/apt-repo/repo.deb
sudo apt install repo.deb
```

Dieses Paket fügt die Repository und die Signatur automatisch hinzu.