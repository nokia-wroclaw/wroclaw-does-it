FROM ubuntu:wily

RUN apt-get update
RUN apt-get install -y make cmake clang g++ gcc valgrind git wget vim htop libboost-all-dev
RUN apt-get clean

ENTRYPOINT ["/bin/bash"]
