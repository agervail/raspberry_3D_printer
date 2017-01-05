# raspberry_3D_printer

To launch the web server :
```
cd flask_app
python web_server.py
```

To launch the timelapse tool
```
raspistill -o /home/pi/pictures/timelapse_%d.jpg -l /home/pi/git/raspberry_3d_printer/flask_app/static/current.jpg -w 320 -h 240 -tl 5000 -t 60000 -v -a 12
```
