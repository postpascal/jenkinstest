FROM ubuntu:latest
MAINTAINER Rajdeep Dua "dua_rajdeep@yahoo.com"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
COPY . /test
WORKDIR /test
RUN pip install -r requirement.txt
ENTRYPOINT ["python"]
CMD ["run.py"]
