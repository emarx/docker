FROM dockerfile/python
MAINTAINER Elliot Marx "elliot.marx@affirm.com"

RUN pip install "moto[server]"
ENTRYPOINT ["moto_server"]
CMD ["-p", "8900", "s3bucket_path"]
