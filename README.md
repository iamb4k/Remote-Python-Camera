# Remote-Python-Camera
A bodge to send a webcam video over the network

Required packages:
opencv-python
tk
pillow

Arguments:
./main.py
  -s --server | run as server
  --passwd    | set a password for the server

when running as server:
it will automatically open a socket server listening at the specified listen port and listen address (rserver.py, line 9,10)

when running as client:
it will ask for an IP and a port, and if the server is password protected, a password. After inputted, a window will open showing the camera stream.
