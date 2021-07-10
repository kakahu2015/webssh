Introduction:
webssh is a simple web application used as an ssh client to connect to an ssh server. It is written in Python and based on tornado, paramiko and xterm.js.


Build image:
docker build -t kakahu2015/webssh:v1.0.1 .

If you don’t want to build the image manually, you can directly pull the built image:
docker pull kakahu2015/webssh:v1.0.1

Run:
docker run -d --privileged --name kaka-webssh -p 80:80 kakahu2015/webssh:v1.0.1

Special thanks to https://pypi.org/project/webssh/



