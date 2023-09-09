FROM postgres:14.9-bullseye

# http://apt.postgresql.org/pub/repos/apt/pool/main/p/pgbackrest/
RUN apt-get update && apt-get install -y \
      pgbackrest=2.47-1.pgdg110+1 \
      ca-certificates \
      && rm -rf /var/lib/apt/lists/*
