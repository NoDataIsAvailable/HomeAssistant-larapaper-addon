FROM ghcr.io/usetrmnl/larapaper

#Switch to root to make 0-start.sh executable
USER root 

COPY ./start.sh /etc/entrypoint.d/0-start.sh
RUN chmod +x /etc/entrypoint.d/0-start.sh

# Switch back to www-data
USER www-data