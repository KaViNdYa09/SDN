# Adaptive SDN Controller with Intent-Based Networking

## Overview
This project implements a centralized SDN controller using Ryu that supports:
- Intent-based networking
- Context-aware decision making
- DFPS prioritization
- Automatic host discovery
- Dynamic flow rule installation

## Features
- Centralized SDN control plane
- REST API integration
- Real-time host discovery
- Per-switch flow installation
- Context-aware decision engine

## Technologies Used
- Ryu Controller
- Mininet
- OpenFlow 1.3
- Flask API
- Python

## Topology
- 6 switches (Core, Distribution, Access)
- 15 hosts (Web, App, DB tiers)

## APIs

### Submit Intent
