## Shell Tools

This repo contains a bunch of shell tools that make our lives
easier for things like versioning, git commands, etc..

## Commands

### `git-latest-tag`
This command outputs the latest tag in the git repo for versioning
purposes. Exits `128` if it can't find the tag.

### `docker-prune`
This will run `docker system prune -af --volumes` to clean up after
a Docker build.
