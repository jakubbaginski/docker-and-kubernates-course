FROM redis

RUN apt-get update && apt-get install -y procps
COPY redis.conf /etc/redis.conf

CMD ["redis-server", "/etc/redis.conf"]
