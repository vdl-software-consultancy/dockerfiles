FROM debian:stretch

RUN apt-get update && apt-get install -y pgbouncer=1.7.2-2 && \
    apt-get clean && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

ENTRYPOINT ["pgbouncer"]
CMD ["--user=postgres", "/etc/pgbouncer/pgbouncer.ini"]
