# Camel K Demo

This is a demo that shows how to use [Camel K](https://camel.apache.org/camel-k/latest/).

## Setup

1. You must have access to a Kubernetes or OpenShift Cluster.
2. Set up a Kafka cluster. You can use [Strimzi](https://strimzi.io/quickstarts/) to easily provision a cluster.
3. Install the Camel K binary. ([instructions](https://camel.apache.org/camel-k/latest/installation/installation.html)) If you're on OpenShift, you can use OperatorHub.
4. A Telegram bot ([instructions](https://core.telegram.org/bots))

## Usage

To run the integration:

`kamel run telegram-sightings.js`

For dev mode:

`kamel run telegram-sightings.js --dev`


