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
- Linstor (via Piraeus operator, possibly with K8S api instead of a separate etcd cluster)
- OpenEBS (very simple and a good option for initial bootstrapping, especially for local/hostpath PVs)
- Longhorn: Simple but annoying and slow. The most annoying tihng is that CPU spikes lead to read only FS which fuck things up.

## DB
- Clickhouse
- Postgres (with CNPG operator that will cover everything from HA to connection pooling to backups via CRDs)

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
- Vector.dev as collection and delivery pipeline for logs, metrics, traces. (VRL is very performant and robust)
- Prometheus
- Grafana
- Sysdig
- Netdata

## Object storage
- MinIO

## GitOps
- Flux
- ArgoCD
- Terraform
