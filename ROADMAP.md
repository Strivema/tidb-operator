# TiDB Operator Roadmap

This document defines the roadmap for TiDB Operator development.

## v0.1.0: (2018-08-21)
- [x] Bootstrap multiple TiDB clusters
- [x] Monitor deployment support
- [x] Helm charts support
- [x] Basic Network PV/Local PV support
- [x] Safely scale the TiDB cluster
- [x] Upgrade the TiDB cluster in order
- [x] Stop the TiDB process without terminating Pod
- [x] Synchronize cluster meta info to POD/PV/PVC labels
- [x] Basic unit tests & E2E tests
- [x] Tutorials for GKE, local DinD

## v0.2.0: (2018-09-10)
- [x] Automatic failover for network PV
- [x] Automatic failover for local PV
- [x] Customize the Load Balancer service parameters on public cloud

## v0.3.0: (2018-09-30)
- [x] Gracefully upgrade PD/TiKV/TiDB: evict the Raft leader or DDL owner before upgrade
- [x] Backup via Binlog
- [x] Backup via Mydumper

## v0.4.0: (2018-10-30) (aka. v1.0.0-alpha)
- [x] Extend scheduler for better support local persistent volume

## v1.0.0-beta: (2018-11-20)
- [ ] Improve unit test coverage (80%)
- [ ] Improve e2e test coverage (70%)
- [ ] Basic chaos testing case
- [ ] User guide document

## v1.0.0-ga: (2018-12-30)
- [ ] Stabilize API
- [ ] Stable for production deployment
