FROM ubuntu:artful

RUN apt-get update && \
    apt-get -yqq install \
      texlive \
      texlive-lang-japanese \
      texlive-fonts-recommended \
      texlive-fonts-extra \
      texlive-bibtex-extra \
      make \
      ipe \
      pdftk \
      inkscape
RUN apt-get clean && rm -rf /var/lib/apt/lists/*

VOLUME /data
WORKDIR /data
