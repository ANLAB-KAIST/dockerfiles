FROM myoung34/github-runner:debian-bullseye

RUN apt-get update && apt-get install -y \
    curl \
    cmake \
    meson \
    ninja-build \
    clang-format \
    clang-tidy \
    python3 \
    python3-pip \
    python3-venv \
    shellcheck \
    sloccount \
    zip \
    unzip

RUN sed -i 's/deb.debian.org/mirror.kakao.com/' /etc/apt/sources.list