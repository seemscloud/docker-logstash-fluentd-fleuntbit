FROM debian:bullseye-slim

RUN apt-get update && \
    apt-get install unzip -y

ENTRYPOINT ["/bin/bash", "/entrypoint.sh"]