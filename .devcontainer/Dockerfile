FROM fedora:42
RUN dnf install -y \
    git \
    python3 \
    python3-pip \
    && dnf clean all
RUN useradd -m developer
USER developer
RUN python3 -m pip install -U discord.py