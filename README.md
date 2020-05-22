# rtsp-to-mjpeg
Simple container to provide access to a RTSP stream via MJPEG.

The image requires the following environment variables to be set:
CAMERAUSER=''
CAMERAPASSWORD=''
CAMERAIP=''
CAMERAPORT=''
CAMERASTREAM=''

## Modifications

Modified from original repo:

- Switched to Alpine linux
- Modified the output to work with octoprint