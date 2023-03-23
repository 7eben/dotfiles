Ubuntu 22
=================

- Use Xorg instead Wayland to share screen without browser special settings

- Switch from PulseAudio to Pipewire

https://gist.github.com/the-spyke/2de98b22ff4f978ebf0650c90e82027e?permalink_comment_id=3976215
 -> Install from the PPA if you want aptX


SLimBook
=================

sudo apt-get remove --purge libreoffice\*

sudo apt-get clean
sudo apt-get autoremove



Manual software
==================

> Autofirma:
	    sudo apt install libnss3-tools
		sudo dpkg -i /home/zeben/Downloads/AutoFirma_Linux/AutoFirma_1_7_1.deb


	If some broken after install:
    #https://linuxhint.com/apt_get_fix_missing_broken_packages/

	sudo apt-get update --fix-missing
    sudo apt-get install -f

> Global prettier java for watcher plugins (nodejs installed with asdf)
  npm install -g prettier prettier-plugin-java --save-dev


> PG client
  Download (postgresql-client) .deb for a given version, extract and get de bin in order to set Local Client in Dbeaver
  See: ~/apps/postgres/Readme.md

Customizations
===================
 Setting > Power > Show Battery Percent


Terminal
===================

- Create profile
- Change color
- Change Custom Font: FiraCode Nerd Font Mono
