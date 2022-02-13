
---
title: "Documentation"
linkTitle: "Documentation"
weight: 20
menu:
  main:
    weight: 20
---

## Introduction

Bantu is a platform offering services and APIs empowering developers and companies. Bantu allows them to create solutions for their end customers without having to reinvent the wheel while still providing flexibility.

Throughout this documentation, several concrete examples will be provided to illustrate the use and the added value of Bantu.


## Fundamental

Bantu is a solution that combines open-source solutions and internal development. All the development done is basically in Java to allow the greatest number of companies and developers to extend the solution.


## Architecture

Below is the current version of the architecture:


![Bantu Architecture](./assets/images/bantu-archi.png)


| Composant             | Implémentation                                |
|--------------         |-----------                                    |
| BD                    | PostgreSQL                                    |
| Cache                 | Redis                                         |
| Monitoring            | Grafana, Prometheus, Alertmanager, Loki       |
| Analytics             | InfluxDB, Prometheus                          |
| Config                | Vault                                         |
| Service Registry      | Consul                                        |
| MQ                    | RabbitMQ, NATS.io                             |
| Messages Provider*    | Offre cloud (Twilio) - Offre hébergée (varie) |