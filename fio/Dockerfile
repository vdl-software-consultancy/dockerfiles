FROM debian:stretch

RUN apt-get update && apt-get install -y fio=2.16-1 && \
    apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

ENTRYPOINT ["fio"]
