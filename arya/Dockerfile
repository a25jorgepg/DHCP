FROM debian:13

RUN apt update  && apt install -y \
    procps \
    iproute2 \
    iputils-ping \
    bind9utils \
    dnsutils \
    rsyslog \
    && rm -rf /var/lib/apt/lists/*


CMD ["tail", "-f", "/dev/null"]