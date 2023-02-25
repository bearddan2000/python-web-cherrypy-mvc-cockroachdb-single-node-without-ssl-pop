# python-web-cherrypy-mvc-cockroachdb-single-node-without-ssl-pop

## Description
Simple web app that serves for a cherrypy project.

Uses sqlalchemy query a table `pop`.

## Tech stack
- python
  - cherrypy
  - sqlalchemy
- cockroachdb

## Docker stack
- python:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [Master node webui](http://localhost:8000)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
