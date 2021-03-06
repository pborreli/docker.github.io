+++
title = "stop"
description = "Stop Docker Universal Control Plane containers."
keywords= ["install, ucp, stop"]
[menu.main]
parent = "ucp_ref"
identifier = "ucp_ref_stop"
+++

# docker/ucp stop

Stop UCP components running on this engine

## Usage

```bash
$ docker run --rm -it \
     --name ucp \
     -v /var/run/docker.sock:/var/run/docker.sock \
     docker/ucp \
     stop [command options]
```

## Options

| Option        | Description                                      |
|:--------------|:-------------------------------------------------|
| `--debug, -D` | Enable debug mode                                |
| `--jsonlog`   | Produce json formatted output for easier parsing |
