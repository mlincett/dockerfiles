FROM debian:bullseye-slim

RUN apt-get update && apt-get install -y unbound

COPY unbound.conf /etc/unbound/

CMD ["unbound", "-d"]
