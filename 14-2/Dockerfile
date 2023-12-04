FROM postgres:14.10

# http://apt.postgresql.org/pub/repos/apt/pool/main/p/pgbackrest/
RUN apt-get update && apt-get install -y \
      pgbackrest=2.49-1.pgdg120+1 \
      ca-certificates \
      && rm -rf /var/lib/apt/lists/*
