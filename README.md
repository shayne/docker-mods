# linuxbrew - Docker mod for code-server

This mod adds Homebrew/linuxbrew to code-server.

In code-server docker arguments, set an environment variable `DOCKER_MODS=shaynesweeney/mods:linuxbrew`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=shaynesweeney/mods:linuxbrew|linuxserver/mods:code-server-mod2`

## Volume cache

It is recommended to create a volume for container path `/home/linuxbrew`, in order to persist packages between container rebuilds.

**Example:**

```
    docker run \
        ... \
        -v /host/volume/linuxbrew:/home/linuxbrew \
        ...
```
