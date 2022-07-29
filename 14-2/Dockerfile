FROM postgres:14.4-bullseye

RUN apt-get update && apt-get install -y \
      pgbackrest=2.40-2.pgdg110+1 \
      ca-certificates \
      && rm -rf /var/lib/apt/lists/*
