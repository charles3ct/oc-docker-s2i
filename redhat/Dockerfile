# simple dockerfile to test OCP s2i using Dockerfile 

FROM registry.access.redhat.com/ubi7:latest

# Adding comment for the sleep infinity and uncommenting sleep 30
# CMD ["/bin/bash", "-c", "sleep infinity"]
 CMD ["/bin/bash", "-c", "--", "while true; do sleep 30; done;"]
