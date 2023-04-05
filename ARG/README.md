### ARG

ARG is used to supply few variables at the time of image creation.
* ARG is the only instruction we can use before FROM. ARG declared before cannot be access after FROM instructions

### It cannot be used at the time of RUN.

### Using ENV and ARG for best results
*Create one env variable and assign the value of ARG to that.
*Then we can acccess the ARG values through ENV both image and container.