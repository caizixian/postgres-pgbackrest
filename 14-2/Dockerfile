FROM postgres:14-bullseye

ENV PGBACKREST_VERSION 2.39-1.pgdg110+1

RUN apt-get update && apt-get install -y \
      pgbackrest=$PGBACKREST_VERSION \
      ca-certificates \
      && rm -rf /var/lib/apt/lists/*
