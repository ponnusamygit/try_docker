FROM debian

MAINTAINER ponnusamy.gac@gmail.com

RUN apt-get update

RUN DEBIAN_FRONTEND=noninteractive apt-get install -yq curl unzip less

RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" && unzip awscliv2.zip && ./aws/install

RUN curl -o- -L https://slss.io/install | bash
