# envfile - Docker mod for code-server

This mod adds support for defining environment variables via a `.env` file in the code-server container's `abc` user home directory (i.e. `$HOME/.env`)

In code-server docker arguments, set an environment variable `DOCKER_MODS=shaynesweeney/mods:envfile`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=shaynesweeney/mods:envfile|linuxserver/mods:code-server-mod2`

**Example:**

```sh
    # ~/.env
    export GOROOT="$HOME/.my/path/to/go/bin"
    export PATH="$HOME/.local/bin:$PATH"
```
