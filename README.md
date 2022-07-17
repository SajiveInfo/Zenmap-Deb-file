# Zenmap-Deb-file
Kali Linux, Parrot OS and others linux install Zenmap Deb file download.


  mkdir Zenmap
  cd Zenmap

  wget http://archive.ubuntu.com/ubuntu/pool/universe/p/pygtk/python-gtk2_2.24.0-5.1ubuntu2_amd64.deb
  wget http://archive.ubuntu.com/ubuntu/pool/universe/p/pycairo/python-cairo_1.16.2-2ubuntu2_amd64.deb
  wget http://archive.ubuntu.com/ubuntu/pool/universe/p/pygobject-2/python-gobject-2_2.28.6-14ubuntu1_amd64.deb



-------------
  python-cairo_1.16.2-2ubuntu2_amd64.deb
  python-gobject-2_2.28.6-14ubuntu1_amd64.deb
  python-gtk2_2.24.0-5.1ubuntu2_amd64.deb
-----------


  sudo chmod +777 python-*

  sudo apt install ./python-cairo_1.16.2-2ubuntu2_amd64.deb
  sudo apt install ./python-gobject-2_2.28.6-14ubuntu1_amd64.deb
sudo apt install ./python-gtk2_2.24.0-5.1ubuntu2_amd64.deb


  wget https://nmap.org/dist/zenmap-7.92-1.noarch.rpm

  sudo alien --to-deb zenmap-7.92-1.noarch.rpm

  sudo chmod +777 zenmap_7.92-2_all.deb


