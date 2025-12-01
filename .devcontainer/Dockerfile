FROM archlinux:latest

# Basic system update
RUN pacman -Syu --noconfirm

# Install common tools
RUN pacman -S --noconfirm \
    base-devel \
    git \
    sudo \
    nano \
    wget \
    curl \
    which

# Enable colored pacman
RUN sed -i 's/^#Color/Color/' /etc/pacman.conf

