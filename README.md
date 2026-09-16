# Drone

## Overview

This project deploys drone and gitea behind traefik as a reverse-proxy using docker-compose.

## Purpose

This project was created to unerstand container orchestration, proxies, and infrastructure management in a self-hosted set up.

## Architecture

    client 
    | HTTPS
    v
    Traefik Forward Auth Proxy
    |
    v
    |
    |
    |   
    ____________________________        |           |               |
    v           v               v
    Service A   Service B   Service C

## Technologies

- Docker

- Docker Compose

- Docker Networking

- Traefik

- Gitea

- HTTPS/TLS

- Linux

- Persistent Volumes

## What I Learned

- Docker

- Container Orchesration

- Reverse Proxying

- OAuth

- Persistent Storage

- Service Discovery

## Licence

This project is for educational purposes only.
