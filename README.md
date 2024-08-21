# The Student Guide to Logs

### What is a Log? And no, we are not talking about a tree...
A log is formally defined as discrete, specific actions with very granular details. Doesn't make much sense, does it? Let's try to put this in other words.

Logs can be considered a fancy type of print statement that is specifially used to inform the *programmer* of the status of an application. We use logs as a way to record and report the events and behaviors of a program in a consistent, text-based format for future reference and tracking. 

Logs can come in the form of error messages, warnings, traces, informational messages, and more to quickly and easily identify the status of any process within an application. These inherently contain more information than a simple print statement and are extremely important for maintaining an application.

*Some examples of where you may have come across logs before include an HTTP status of 200 to signify that our web page is functioning as expected, or even an HTTP status of 404 to signify that an error has occured in finding our web page.*

### Why do you want to view your logs?
Logs can be beneficial in many ways. One of the most common uses of logs is to identify **bugs** in a program. Logs have timestamps attached to each event, which can quickly inform the programmer when an issue occured. By recording and tracking these logs, we are able to identify patterns in our code where errors or warnings may be more frequent, which can reduce the amount of time programmers spend simply finding when and where issues occur.

### What does this have to do with New Relic?
New Relic is able to capture the logs for your application and integrate them into the platform. This means we can create dashboards, alerts, monitoring, and use many other New Relic features using the logs of an application. New Relic also allows you to query for logs within your application using NRQL or NerdGraph to further explore the status of your application.

To find your logs, go to [one.newrelic.com > All capabilities](https://one.newrelic.com/all-capabilities) > Logs, which is located in the left toolbar.

### How do you modify your logs in New Relic?

<!-- Information on how it's used in New Relic -->

### Demo app for Logging

We will be using the Node APM agent's example logging application, [esm-logs-in-context](https://github.com/newrelic/newrelic-node-examples/tree/main/application-logging/esm-logs-in-context), to show you how it works.

![1724264936119](image/README/1724264936119.png)


## Other Resources
[New Relic Docs on Logging Management](https://docs.newrelic.com/docs/logs/get-started/get-started-log-management/)