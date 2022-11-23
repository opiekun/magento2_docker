FROM        jpillora/dnsmasq:1.1

LABEL       maintainer="zerocool78"

COPY        conf/dnsmasq.conf /etc/dnsmasq/

RUN         rm -f /etc/dnsmasq.conf && \
            ln -sf /etc/dnsmasq/dnsmasq.conf /etc/dnsmasq.conf