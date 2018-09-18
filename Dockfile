FROM python:3.6.2-alpine3.6

WORKDIR "/oracle-cloud-cli"
RUN apk add --update curl && rm -rf /var/cache/apk/*
RUN pip3 install --upgrade oci-cli 

CMD ["/bin/sh"]

