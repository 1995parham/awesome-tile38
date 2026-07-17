# Awesome Tile38 [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

<p align="center">
  <a href="https://tile38.com"><img
    src="/.github/images/logo.png"
    width="284" height="108" border="0" alt="Tile38"></a>
</p>

> A curated list of awesome Tile38 software and resources.

Tile38 is an open source, in-memory geolocation data store, spatial index, and
real-time geofencing server.

## Contents

- [Official](#official)
- [Clients](#clients)
  - [Go](#go)
  - [Python](#python)
  - [Node.js](#nodejs)
- [Deployment](#deployment)
- [Tools](#tools)
- [Articles](#articles)

## Official

- [Tile38](https://github.com/tidwall/tile38) - The server itself: real-time geospatial and geofencing.
- [Client Libraries](https://tile38.com/topics/client-libraries) - Official list of client libraries maintained by the project.
- [Blog](https://tile38.com/blog/) - Official blog with release notes and announcements.

## Clients

### Go

- [t38c](https://github.com/xjem/t38c) - Feature-rich Go client (archived).
- [t38c (cjkreklow)](https://github.com/cjkreklow/t38c) - Maintained Go client with a smaller command set.

### Python

- [pyle38](https://github.com/iwpnd/pyle38) - Async, fully typed Python client.

### Node.js

- [tile38-client](https://github.com/tobilg/tile38-client) - Node.js client with a fluent query interface and live geofencing.
- [tile38](https://www.npmjs.com/package/tile38) - Client for Node.js published on npm.

## Deployment

- [tile38-chart](https://github.com/1995parham/tile38-chart) - Helm chart to deploy Tile38 on Kubernetes with a leader-follower topology for read scaling.
- [tile38-ha](https://github.com/RashadAnsari/tile38-ha) - Docker image for high availability with Redis Sentinel.

## Tools

- [tiles](https://github.com/1995parham/tiles) - Shard utility, the controller and query router for sharded clusters.
- [tile38-viewer](https://github.com/leighghunt/tile38-viewer) - Tool to visualise the state of events in Tile38.

## Articles

- [Creating Geofences in .NET with Tile38](https://intodot.net/creating-geofences-in-net-with-tile38/) - Walkthrough of geofencing with Tile38 from a .NET application.
- [Create Geo-aware System: Detecting Whether a User Is Inside the City](https://yusufs.medium.com/create-geo-aware-system-how-to-better-detect-whether-user-is-inside-the-city-bonus-implement-3107292cbc6f) - Comparing approaches to point-in-city detection, with a Tile38 polygon geofencing implementation.
