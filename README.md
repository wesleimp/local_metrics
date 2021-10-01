# Local metrics

This is a simple repository with some basic configurations for collect metrics with Prometheus and display with Grafana.

**Dev environment only**

## Running

```sh
$ docker compose up -d
```

### Endpoints

- Prometheus: `http://localhost:9090`
- Grafana: `http://localhost:3000`

The default `/metrics` is `localhost:4000`. If you need to modify or add a new address, edit the `config.yml` file inside `config` folder.
