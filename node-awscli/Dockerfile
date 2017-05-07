FROM node:6.10.3

RUN apt-get update && \
    apt-get install -y python-dev && \
    curl -O https://bootstrap.pypa.io/get-pip.py && \
    python get-pip.py && \
    pip install awscli==1.11.83
