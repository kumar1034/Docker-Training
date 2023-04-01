### ENV

ENV is the instruction to provide environment variable to image and container.

`docker run env:v1 env`


We can override env variables at runtime

`docker run -e DURATION=30HRS env:v1 env`