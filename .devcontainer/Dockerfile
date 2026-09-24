FROM gcc:4.9

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
        git \
        curl \
        tree \
        less \
        nano \
        man-db \
        manpages \
        lowdown \
    && rm -rf /var/lib/apt/lists/*

RUN useradd -m -s /bin/bash pse 

USER pse 
