# podman-compose example

This should test if I can set the podman compose file via `.env` variable `COMPOSE_FILE`[1]:

```
.env: COMPOSE_FILE=container/container-compose.yml
```

Basically, I want to keep the container-related files bundled in one directory (here: `container`) as much as possible.

Currently, however, this does not seem to be possible in my setup.

```bash
podman-compose up
# -> http://localhost:8088
```

---

[1] https://docs.docker.com/compose/environment-variables/envvars/#compose_file
