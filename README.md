# Raspberripichatserver
a web server chat space running on a raspberry pi
when you run this code you will be running a chat server from your raspberry pi on your network

put the file on your desktop (file is provoded in repositorie)

in your raspberry pi terminal run-

cd Desktop
--------------------------------------
unzip chat_web.zip
--------------------------------------
cd chat_web
--------------------------------------
python3 -m venv venv
--------------------------------------
source venv/bin/activate
--------------------------------------
pip install flask flask-socketio eventlet
--------------------------------------
python app.py
