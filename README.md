# The Student Guide to Logs

### What is a Log?

### Why do you want to view your logs?

### How do you modify your logs in New Relic?

### Demo app for Logging

We will be using the Node APM agent's example logging application, [esm-logs-in-context](https://github.com/newrelic/newrelic-node-examples/tree/main/application-logging/esm-logs-in-context), to show you how it works.

But first, a little context:

1. The Node agent is part of New Relic (NR)'s Application Performance Monitoring (APM), one of the first services provided by NR. The agent is called 'Node' because it instruments [Node.js](https://nodejs.org/en), the most popular JavaScript runtime environment, applications.
   1. There are many other APM agents for other popular programming languages, like Java, Python, and .NET.
2. This app requires [Docker](https://www.docker.com/products/docker-desktop/), a platform that will containerize our app, which is running a server on localhost, to be installed on your computer.
3. If you would like to test this out yourself, follow the instructions in the app's [README](https://github.com/newrelic/newrelic-node-examples/blob/main/application-logging/esm-logs-in-context/README.md).

![1724264936119](image/README/1724264936119.png)
