FROM ubuntu:20.04
RUN apt-get update && apt-get install --yes --no-install-recommends git make
LABEL description="une image contenant un git préconfiguré"
RUN git config --global init.defaultBranch main