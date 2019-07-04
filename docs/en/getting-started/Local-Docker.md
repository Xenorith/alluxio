---
layout: global
title: Local Docker Quick Start Guide
group: Getting Started
priority: 1
---

* Table of Contents
{:toc}

This quick start guide goes over how to launch a stack with Alluxio and Presto on a docker container
to run SQL queries.

## Prerequisites

* [Docker](https://docs.docker.com/install/)
* 4GB of available RAM

## Launching the container

Pull the image alluxio/funhouse:
```bash
docker pull alluxio/funhouse 
```
It may take a few minutes to download the 3GB image, so grab a quick drink or snack!

Launch the container:
```bash
docker run alluxio/funhouse 
```

Open a bash terminal in the launched container:
```bash
docker exec alluxio/funhouse
```

## Running queries
