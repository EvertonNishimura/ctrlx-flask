# ctrlx-flask
Minimal hello world with a python flask snap for ctrlx. There might be some mistakes or unecessary things on this code. 
Maybe it can spare some minutes for some of you trying to create your own python snap for ctrlX.

Instructions:

1 - Git clone this repo: git clone https://github.com/EvertonNishimura/ctrlx-flask.git

2 - Run Snapcraft: sudo snapcraft

3 - When it ends you can transfer it to ctrlx core virtual (my core virtual ip is 192.168.1.1): sudo scp flask-snap_0.11_amd64.snap rexroot@192.168.1.1:/home/rexroot/

4 - You can log in virtual core via terminal (password is rexroot): ssh rexroot@192.168.1.1

5 - Install remotely: sudo snap install flask-snap_0.11_amd64.snap --dangerous

6 - Now login via web browser and see the app integrated in the menu bar of ctrlx!

