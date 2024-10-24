<h1 align="center" style="border-bottom: none">
    <a href="https://signoz.io" target="_blank">
        <img alt="SigNoz" src="https://github.com/user-attachments/assets/ef9a33f7-12d7-4c94-8908-0a02b22f0c18" width="100" height="100">
    </a>
    <br>SigNoz
</h1>

<p align="center">All your logs, metrics, and traces in one place. Monitor your application, spot issues before they occur and troubleshoot downtime quickly with rich context. SigNoz is a cost-effective open-source alternative to Datadog and New Relic. Visit <a href="https://signoz.io" target="_blank">signoz.io</a> for the full documentation, tutorials, and guide.</p>

<p align="center">
    <img alt="Downloads" src="https://img.shields.io/docker/pulls/signoz/query-service?label=Docker Downloads"> </a>
    <img alt="GitHub issues" src="https://img.shields.io/github/issues/signoz/signoz"> </a>
    <a href="https://twitter.com/intent/tweet?text=Monitor%20your%20applications%20and%20troubleshoot%20problems%20with%20SigNoz,%20an%20open-source%20alternative%20to%20DataDog,%20NewRelic.&url=https://signoz.io/&via=SigNozHQ&hashtags=opensource,signoz,observability"> 
        <img alt="tweet" src="https://img.shields.io/twitter/url/http/shields.io.svg?style=social"> </a> 
</p>
  
  
<h3 align="center">
  <a href="https://signoz.io/docs"><b>Documentation</b></a> &bull;
  <a href="https://github.com/SigNoz/signoz/blob/develop/README.zh-cn.md"><b>ReadMe in Chinese</b></a> &bull;
  <a href="https://github.com/SigNoz/signoz/blob/develop/README.de-de.md"><b>ReadMe in German</b></a> &bull;
  <a href="https://github.com/SigNoz/signoz/blob/develop/README.pt-br.md"><b>ReadMe in Portuguese</b></a> &bull;
  <a href="https://signoz.io/slack"><b>Slack Community</b></a> &bull;
  <a href="https://twitter.com/SigNozHq"><b>Twitter</b></a>
</h3>

## Features


### Application Performance Monitoring

Use SigNoz APM to monitor your applications and services. It comes with out-of-box charts for key application metrics like p99 latency, error rate, Apdex and operations per second. You can also monitor the database and external calls made from your application. Read [more](https://signoz.io/application-performance-monitoring/).

You can [instrument](https://signoz.io/docs/instrumentation/) your application with OpenTelemetry to get started.

![apm-cover](https://github.com/user-attachments/assets/fa5c0396-0854-4c8b-b972-9b62fd2a70d2)


### Logs Management

SigNoz can be used as a centralized log management solution. We use ClickHouse (used by likes of Uber & Cloudflare) as a datastore, ⎯ an extremely fast and highly optimized storage for logs data. Instantly search through all your logs using quick filters and a powerful query builder.

You can also create charts on your logs and monitor them with customized dashboards. Read [more](https://signoz.io/log-management/).

![logs-management-cover](https://github.com/user-attachments/assets/343588ee-98fb-4310-b3d2-c5bacf9c7384)


### Distributed Tracing

Distributed Tracing is essential to troubleshoot issues in microservices applications. Powered by OpenTelemetry, distributed tracing in SigNoz can help you track user requests across services to help you identify performance bottlenecks. 

See user requests in a detailed breakdown with the help of Flamegraphs and Gantt Charts. Click on any span to see the entire trace represented beautifully, which will help you make sense of where issues actually occurred in the flow of requests.

Read [more](https://signoz.io/distributed-tracing/).

![distributed-tracing-cover](https://github.com/user-attachments/assets/9bfe060a-0c40-4922-9b55-8a97e1a4076c)



### Metrics and Dashboards

Ingest metrics from your infrastructure or applications and create customized dashboards to monitor them. Create visualization that suits your needs with a variety of panel types like pie chart, time-series, bar chart, etc.

Create queries on your metrics data quickly with an easy-to-use metrics query builder. Add multiple queries and combine those queries with formulae to create really complex queries quickly.

Read [more](https://signoz.io/metrics-and-dashboards/).

![metrics-n-dashboards-cover](https://github.com/user-attachments/assets/a536fd71-1d2c-4681-aa7e-516d754c47a5)

### Alerts

Use alerts in SigNoz to get notified when anything unusual happens in your application. You can set alerts on any type of telemetry signal (logs, metrics, traces), create thresholds and set up a notification channel to get notified. Advanced features like alert history and anomaly detection can help you create smarter alerts.

Alerts in SigNoz help you identify issues proactively so that you can address them before they reach your customers.

Read [more](https://signoz.io/alerts-management/).

![alerts-cover](https://github.com/user-attachments/assets/03873bb8-1b62-4adf-8f56-28bb7b1750ea)

### Exceptions Monitoring

Monitor exceptions automatically in Python, Java, Ruby, and Javascript. For other languages, just drop in a few lines of code and start monitoring exceptions.

See the detailed stack trace for all exceptions caught in your application. You can also log in custom attributes to add more context to your exceptions. For example, you can add attributes to identify users for which exceptions occurred.

Read [more](https://signoz.io/exceptions-monitoring/).


![exceptions-cover](https://github.com/user-attachments/assets/4be37864-59f2-4e8a-8d6e-e29ad04298c5)


<br /><br />

## Why SigNoz?

SigNoz is a single tool for all your monitoring and observability needs. Here are a few reasons why you should choose SigNoz:

- Single tool for observability(logs, metrics, and traces)

- Built on top of [OpenTelemetry](https://opentelemetry.io/), the open-source standard which frees you from any type of vendor lock-in

- Correlated logs, metrics and traces for much richer context while debugging

- Uses ClickHouse (used by likes of Uber & Cloudflare) as datastore - an extremely fast and highly optimized storage for observability data

- DIY Query builder, PromQL, and ClickHouse queries to fulfill all your use-cases around querying observability data

- Open-Source - you can use open-source, our [cloud service](https://signoz.io/teams/) or a mix of both based on your use case


## Getting Started

### Create a SigNoz Cloud Account

SigNoz cloud is the easiest way to get started with SigNoz. Our cloud service is for those users who want to spend more time in getting insights for their application performance without worrying about maintenance. 

[Get started for free](https://signoz.io/teams/)

### Deploy using Docker(self-hosted)

Please follow the steps listed [here](https://signoz.io/docs/install/docker/) to install using docker

The [troubleshooting instructions](https://signoz.io/docs/install/troubleshooting/) may be helpful if you face any issues.

<p>&nbsp  </p>
  
  
### Deploy in Kubernetes using Helm(self-hosted)

Please follow the steps listed [here](https://signoz.io/docs/deployment/helm_chart) to install using helm charts

<br /><br />

We also offer managed services in your infra. Check our [pricing plans](https://signoz.io/pricing/) for all details.


## Join our Slack community

Come say Hi to us on [Slack](https://signoz.io/slack) 👋

<br /><br />
