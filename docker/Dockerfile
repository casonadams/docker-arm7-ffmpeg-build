FROM arm32v7/ubuntu

RUN apt-get update && \
  DEBIAN_FRONTEND=noninteractive apt-get install -y \
  autoconf \
  automake \
  build-essential \
  cmake \
  git-core \
  libass-dev \
  libfreetype6-dev \
  libsdl2-dev \
  libtool \
  libva-dev \
  libvdpau-dev \
  libvorbis-dev \
  libxcb1-dev \
  libxcb-shm0-dev \
  libxcb-xfixes0-dev \
  pkg-config \
  texinfo \
  wget \
  zlib1g-dev \
  vim \
  git \
  nasm \
  yasm \
  libx264-dev \
  libx265-dev \
  libvpx-dev \
  libfdk-aac-dev \
  libmp3lame-dev \
  libopus-dev 


RUN mkdir /home/ffmpeg_sources 
RUN mkdir /home/bin
RUN mkdir /home/Projects
WORKDIR "/home/Projects"
