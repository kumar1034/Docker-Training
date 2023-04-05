FROM almalinux
RUN yum install nginx -y
# when image creator is running this, ONBUILD instruction will not run, if someone else use our image, ONBUILD will run
ONBUILD ADD simple.txt /tmp/