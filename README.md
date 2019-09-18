# gameshell_volume_hotkey

Control sound volume everywhere!
hotkey:

Shift + Select: Volume down
Shift + Start: Volume up


How to install:

1.command line:

sudo pip install evdev

git clone https://github.com/pedrogpimenta/gameshell_volume_hotkey.git

cd gameshell_volume_hotkey

cp volume_hotkey.py ~/launcher/sys.py/

cp -r tools ~/launcher/sys.py/


2.add reboot command shell

"sudo nano /etc/rc.local" open rc.local file and input this to the last line

nohup python /home/cpi/launcher/sys.py/volume_hotkey.py &


3.reboot system
