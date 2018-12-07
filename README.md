# cerebral

[![Build Status](https://api.travis-ci.org/containership/cerebral.svg?branch=master)](https://travis-ci.org/containership/cerebral)
[![Go Report Card](https://goreportcard.com/badge/github.com/containership/cerebral)](https://goreportcard.com/report/github.com/containership/cerebral)
[![codecov](https://codecov.io/gh/containership/cerebral/branch/master/graph/badge.svg)](https://codecov.io/gh/containership/cerebral)

Kubernetes cluster autoscaler with pluggable metrics backends and scaling engines

# Overview

Containership's cluster autoscaler is a provider agnostic method by which to increase or decrease pools of nodes in your Kubernetes cluster in response to alerts generated by user-defined policies. Increasing the number of nodes is important in order to meet resource demand, while decreasing the number is helpful in controlling cost.
