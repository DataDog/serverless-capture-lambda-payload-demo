# Serverless-capture-lambda-payload-demo
Serverless demo showing users how they can capture (and obfuscate) their Lambda payloads in Datadog APM

This will capture all Lambda requests and responses, and redact the authorization header.
Incoming request:
![](./redacted_req.png)
The header replacd in datadog:
![](./redacted_dd.png)
