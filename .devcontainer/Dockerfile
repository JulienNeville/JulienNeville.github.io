FROM ruby:3.3

RUN apt-get update && apt-get install -y --no-install-recommends \
    build-essential \
    git \
    nodejs \
    && rm -rf /var/lib/apt/lists/*

RUN gem update --system && gem install bundler

WORKDIR /workspaces/app