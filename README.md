faas-swarm
==========

[![Build Status](https://travis-ci.com/openfaas/faas-swarm.svg?branch=master)](https://travis-ci.com/openfaas/faas-swarm)

## Status - 15th December 2020

Whilst faas-swarm may still work, it is no longer being supported by the community. You can ask about commercial support by emailing support@openfaas.com.

No community support or free updates are available.

See alternatives: [Deploying OpenFaaS](https://docs.openfaas.com/deployment/)

## Summary

This is the Docker Swarm provider for OpenFaaS.

The first and canonical implementation of OpenFaaS was tightly coupled to Docker Swarm. This repository aims to decouple the two so that all providers are isomorphic and symmetrical.

## Deployment

To deploy faas-swarm use `deploy_stack.sh` in the main [OpenFaaS repository](https://github.com/openfaas/faas).

## Status

Status: Released

Features:

* [x] Create
* [x] Proxy
* [x] Update
* [x] Delete
* [x] List
* [x] Scale

Docker image: [`openfaas/faas-swarm`](https://hub.docker.com/r/openfaas/faas-swarm/tags/)

## Contributing

The contribution guide applies from the [main OpenFaaS repository](https://github.com/openfaas/faas/blob/master/CONTRIBUTING.md).
