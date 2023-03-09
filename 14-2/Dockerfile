FROM postgres:14.7-bullseye

RUN apt-get update && apt-get install -y \
      pgbackrest=2.44-1.pgdg110+1 \
      ca-certificates \
      && rm -rf /var/lib/apt/lists/*
