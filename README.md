# based-stack

## OS
- nix: declarative, simple but finicky and unpopular.
- flatcar: all in one sane option but not declarative. Strong emphasis on security, optimized for container workloads.

## VPN/remote access/networking
- tailscale

## k8s distribution
- rke2 - a modern version of k3s

## CNI
- Cilium

## CSI
- Linstor
- OpenEBS
- Longhorn: Simple but annoying and slow. The most annoying tihng is that CPU spikes lead to read only FS which fuck things up.

## DB
- Clickhouse
- Postgres (which operator?)

## Frontend
- React

## Backend
- Nodejs
- PHP

## Systems development (high performance)
- OCaml
- Zig
- Go
- Rust (only if you really really really really need C++...)

## Observability/Metrics
- Store logs in Clickhouse
- Loki is fine too....
- Prometheus
- Grafana
- Sysdig
- Netdata
