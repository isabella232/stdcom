# gliderlabs/stdcom

Standard components and micro-frameworks for [com](https://github.com/gliderlabs/com)

[![GoDoc](https://godoc.org/github.com/gliderlabs/stdcom?status.svg)](https://godoc.org/github.com/gliderlabs/stdcom)
[![CircleCI](https://img.shields.io/circleci/project/github/gliderlabs/stdcom.svg)](https://circleci.com/gh/gliderlabs/stdcom)
[![Go Report Card](https://goreportcard.com/badge/github.com/gliderlabs/stdcom)](https://goreportcard.com/report/github.com/gliderlabs/stdcom)
[![Slack](http://slack.gliderlabs.com/badge.svg)](http://slack.gliderlabs.com)
[![Email Updates](https://img.shields.io/badge/updates-subscribe-yellow.svg)](https://app.convertkit.com/landing_pages/289455)

This is a collection of re-usable components that can be used with the
[com](https://github.com/gliderlabs/com) component kernel for Go.

## Table of Contents

 * [daemon](https://godoc.org/github.com/gliderlabs/stdcom/daemon) - a service runner for long-running applications
 * [log](https://godoc.org/github.com/gliderlabs/stdcom/log) - a placeholder logging API with components for various loggers
 * [web](https://godoc.org/github.com/gliderlabs/stdcom/web) - a web application harness with TLS and middleware support
 * [web/sessions](https://godoc.org/github.com/gliderlabs/stdcom/web/sessions) - [EXPERIMENTAL] wrapper and helper for github.com/gorilla/sessions
 * [web/auth](https://godoc.org/github.com/gliderlabs/stdcom/web/auth) - [EXPERIMENTAL] orchestrates auth with any of ~40 identity providers
 * [web/console](https://godoc.org/github.com/gliderlabs/stdcom/web/console) - [EXPERIMENTAL] provides simple shell for an admin-style interface

## Dependencies

Good libraries should have minimal dependencies. Here are the ones stdcom
packages use and for what:

 * github.com/thejerf/suture (daemon)
 * go.uber.org/zap (log/zap)
 * github.com/gorilla/sessions (web/sessions)
 * github.com/markbates/goth (web/auth)
 * github.com/CloudyKit/jet (web/console)
 * github.com/dustin/go-humanize (web/console)



## License

BSD
