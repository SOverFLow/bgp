FROM frrouting/frr:latest

# Copy configuration files for FRR
COPY zebra.conf /etc/frr/zebra.conf
COPY bgpd.conf /etc/frr/bgpd.conf
COPY ospfd.conf /etc/frr/ospfd.conf
COPY isisd.conf /etc/frr/isisd.conf

# Start FRR services with custom configurations
CMD ["/usr/lib/frr/frrinit.sh", "start"]

