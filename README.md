# Remote-Python-Camera
A bodge to send a video feed over the network

<b>NOTE: this was simply a 1-day bodge I needed to get a remote camera feed. It is buggy and unfinished, and should not be used in a production-like environment.</b>

Required Packages:  
tk  
opencv-python  
pillow  

# Arguments:
./main.py  
  -s --server | run as server  
  --passwd    | set a password for the server  

when running as server:
it will automatically open a socket server listening at the specified listen port and listen address (rserver.py, line 9,10)

when running as client:
it will ask for an IP and a port, and if the server is password protected, a password. After inputted, a window will open showing the camera stream.
