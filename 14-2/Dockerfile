FROM postgres:14.11

# http://apt.postgresql.org/pub/repos/apt/pool/main/p/pgbackrest/
RUN apt-get update && apt-get install -y \
      pgbackrest=2.51-1.pgdg120+1 \
      ca-certificates \
      && rm -rf /var/lib/apt/lists/*
