# pcinfo
A light PC resource reporting tool 

On linux place into /user/local/bin/ and change permissions as follows:
  sudo chown root /user/local/bin/pcinfo.sh
  sudo chmod 755 /user/local/bin/pcinfo.sh

Dependancies:
Curl, lspci
  sudo apt-get install curl lspci
This tool is designed to be terminal only and extremely small with few dependencies.
Some components do not work on weyland currently.
