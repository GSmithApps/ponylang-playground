FROM ponylang/ponyc:latest

RUN apt-get update \
  && apt-get install -y --no-install-recommends \
    git \
    curl \
    ca-certificates \
    build-essential \
    bubblewrap \
  && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace