---
title: Local Kubernetes & Cloudflare ZeroTrust
pubDate: 26/08/2024 10:30
author: "Joe McGinley"
tags:
  - Kubernetes
  - k3s
  - Cloudflare
  - Zero Trust
imgUrl: ../../../src/assets/k3s_logo.png
description: A brief overview of setting up a local Kubernetes cluster using k3s and securing it with a Cloudflare Zero Trust tunnel.
layout: '../../layouts/BlogPost.astro'
---

### Local Kubernetes & Cloudflare ZeroTrust

Aim:

* Local Kubernetes development environment
* Secure access from any location
* Simulated production-like testing

Result:

* Local k8s cluster setup using k3s
* Cloudflare ZeroTrust enables authenticated remote access


This setup combines local development capabilities with secure remote access, providing a flexible platform for Kubernetes projects.