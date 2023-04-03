### ENTRYPOINT

ENTRYPOINT is used to run the container just like CMD.

1. We cannot override ENTRYPOINT, but we can override CMD.
2. We can't override ENTRYPOINT, if you try to do so, it will go and append to the ENTRYPOINT command.
3. If you use CMD and ENTRYPOINT and don't give any command from terminal, CMD acts as argument provider to ENDPOINT