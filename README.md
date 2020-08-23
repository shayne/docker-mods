# Docker Mods

This repo hosts branches for various "Docker Mods". Docker Mods are a user consumable modification layer for Linuxserver.io containers.

For more information on Docker Mods, visit [linuxserver/docker-mods](https://github.com/linuxserver/docker-mods).

# Mod List

- ## [linuxserver/docker-code-server](https://github.com/linuxserver/docker-code-server)

  - ### [linuxbrew](https://github.com/shayne/docker-mods/tree/linuxbrew)

    `DOCKER_MODS=shaynesweeney/mods:linuxbrew`

    Add [Homebrew on Linux](https://docs.brew.sh/Homebrew-on-Linux) linuxbrew to code-server. Useful for installing Linux packages without sudo and inside user-space. Easily persist packages between rebuilds.

  - ### [envfile](https://github.com/shayne/docker-mods/tree/envfile)

    `DOCKER_MODS=shaynesweeney/mods:envfile`

    Allows custom environment variables to be set via `~/.env` file.
