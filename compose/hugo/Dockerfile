FROM klakegg/hugo:0.101.0-ubuntu

RUN apt-get update \
  # dependencies for building Python packages
  && apt-get install -y git \
  # cleaning up unused files
  && apt-get purge -y --auto-remove -o APT::AutoRemove::RecommendsImportant=false \
  && rm -rf /var/lib/apt/lists/*
