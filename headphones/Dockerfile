FROM linuxserver/headphones

# MOFIFY DATA PATH
RUN sed -i "s|config|data|g" /etc/services.d/headphones/run

VOLUME [ "/data" ]
