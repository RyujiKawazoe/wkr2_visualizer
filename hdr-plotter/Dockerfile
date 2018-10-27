FROM python:3.7.1

RUN apt-get install -y git
WORKDIR /
RUN git clone https://github.com/BrunoBonacci/hdr-plot.git

RUN pip3 install --user --upgrade hdr-plot
RUN pip3 install --user --upgrade pandas
RUN pip3 install --user --upgrade matplotlib

WORKDIR /hdr-plot/bin/
