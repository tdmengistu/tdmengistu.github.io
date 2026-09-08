FROM ruby:3.2-bookworm

# System packages needed for local Jekyll development and git operations.
RUN apt-get update \
    && apt-get install -y --no-install-recommends git curl build-essential \
    && rm -rf /var/lib/apt/lists/*
