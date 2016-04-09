# kubehttpbin

[![Build Status](https://travis-ci.org/arschles/kubehttpbin.svg?branch=master)](https://travis-ci.org/arschles/kubehttpbin)
[![Go Report Card](http://goreportcard.com/badge/arschles/kubehttpbin)](http://goreportcard.com/report/arschles/kubehttpbin) [![Docker Repository on Quay](https://quay.io/repository/arschles/kubehttpbin/status "Docker Repository on Quay")](https://quay.io/repository/arschles/kubehttpbin)

An [httpbin.org](http://httpbin.org) clone that you can host on your own Kubernetes cluster. This is a clone of [gohttpbin](https://github.com/arschles/gohttpbin), but designed to run on a Kubernetes cluster instead of Google App Engine.

Note: currently this server only supports the below endpoints. See http://httpbin.org for a description of what each does.

- `GET /ip`
- `GET /get`
- `POST /post`
- `PUT /put`
- `DELETE /delete`
- `HEAD /head`
- `PATCH /patch`
- `HEADERS /headers`
