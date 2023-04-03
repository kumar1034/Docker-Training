### ENTRYPOINT

ENTRYPOINT is used to run the container just like CMD.

1. We cannot override ENTRYPOINT, but we can override CMD.
2. We can't override ENTRYPOINT, if you try to do so, it will go and append to the ENTRYPOINT command.
3. If you use CMD and ENTRYPOINT and don't give any command from terminal, CMD acts as argument provider to ENDPOINT.
4. CMD will supply default arguments to ENTRYPOINT.
5. You can always override CMD arguments from runtime.
6. You can STOP misusing image with other commands.

** Interview **

CMD command can be overridden.
ENTRYPOINT cannot be overridden but if you tried to ovverride ENTRYPOINT then it will go and append the ENTRYPOINT command and it will throw an error.

** But the best results: **

In ENTRYPOINT we will mention the command but will pass the default ARGUMENTS through CMD, if we need to override, we can override the CMD arguments from runtime.