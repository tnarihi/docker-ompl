FROM tnarihi/python

ARG proxy=""
ENV http_proxy $proxy
ENV https_proxy $proxy
ENV HTTP_PROXY $proxy
ENV HTTPS_PROXY $proxy
ENV DEBIAN_FRONTEND noninteractive


RUN apt-get install -y libompl-dev ompl-demos
RUN pip install cython
RUN pip install dubins
RUN apt-get install -y python-skimage
RUN apt-get install -y python-opencv

RUN apt-get install -y cmake
RUN apt-get install -y libopencv-dev
