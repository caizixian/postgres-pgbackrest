FROM postgres:14.6-bullseye

RUN apt-get update && apt-get install -y \
      pgbackrest=2.41-1.pgdg110+1 \
      ca-certificates \
      && rm -rf /var/lib/apt/lists/*
