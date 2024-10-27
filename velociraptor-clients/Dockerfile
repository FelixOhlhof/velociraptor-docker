FROM ubuntu:22.04

COPY ./velociraptor_client /usr/local/bin/velociraptor_client
RUN chmod +x /usr/local/bin/velociraptor_client

COPY ./client.config.yaml /etc/client.config.yaml

CMD ["/usr/local/bin/velociraptor_client", "--config", "/etc/client.config.yaml", "client"]

