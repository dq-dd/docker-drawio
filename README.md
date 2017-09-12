[![](https://images.microbadger.com/badges/image/fjudith/draw.io.svg)](https://microbadger.com/images/fjudith/draw.io "Get your own image badge on microbadger.com")
[![Build Status](https://travis-ci.org/fjudith/docker-draw.io.svg?branch=master)](https://travis-ci.org/fjudith/docker-draw.io)

# Supported tags and respective Dockerfile links

[`7.3.6`, `latest`](https://github.com/fjudith/docker-draw.io/tree/7.3.6)
[`7.3.5`](https://github.com/fjudith/docker-draw.io/tree/7.3.5)
[`7.3.1`](https://github.com/fjudith/docker-draw.io/tree/7.3.1)
[`7.2.5`](https://github.com/fjudith/docker-draw.io/tree/7.2.5)

# Introduction

draw.io (formerly Diagramly) is free online diagram software. You can use it as a flowchart maker, network diagram software, to create UML online, as an ER diagram tool, to design database schema, to build BPMN online, as a circuit diagram maker, and more. draw.io can import .vsdx, Gliffy™ and Lucidchart™ files . 

 # Description

The Dockerfile builds from "Tomcat:8-jre7" (see https://hub.docker.com/_/tomcat/)

**This image does not leverage embedded database**

# Roadmap

* [x] Deployment as WAR package
* [x] Use Tomcat instead of apache
* [x] Patch with EmbedServlet2

## Quick Start

Run the container.

```bash
docker run -it --rm --name="draw" -p 8080:8080 fjudith/draw.io
```

Start a web browser session to http://ip:port/?offline=1

> `?offline=1` is a security feature that disables support of cloud storage.


# Reference

* https://github.com/jgraph/draw.io
* https://github.com/mikitex70/redmine_drawio
