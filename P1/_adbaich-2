FROM frrouting/frr:latest

RUN sed -i 's/^\(bgpd\|ospfd\|isisd\)=no$/\1=yes/' /etc/frr/daemons && \
    echo 'service integrated-vtysh-config' > /etc/frr/vtysh.conf

