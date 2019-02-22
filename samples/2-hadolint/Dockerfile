FROM debian:9.7-slim

RUN apt-get update && apt-get install -y cowsay=3.03+dfsg2-3 --no-install-recommends \
    && rm -rf /var/lib/apt/lists/*

CMD ["/usr/games/cowsay", "Hello,World!" ]
