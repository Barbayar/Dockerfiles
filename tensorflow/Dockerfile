FROM ubuntu

RUN apt update
RUN apt -y upgrade
RUN apt -y install python3-pip
RUN pip3 install --upgrade pip
RUN pip3 install --upgrade tensorflow

WORKDIR /home

CMD ["/bin/bash"]
