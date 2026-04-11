# Software Performance Tools

Performance analysis tools.

## Summary

- **Google Lighthouse** — Automated auditing tool for web pages that reports performance, accessibility, best practices and SEO scores based on lab tests in a real or headless browser.
- **WebPageTest (self-hosted)** — Deep web performance testing and diagnostics tool that runs scripted browser sessions and produces detailed waterfalls, visual metrics and Core Web Vitals.
- **PageSpeed Insights** — Free Google service that combines Lighthouse lab tests with field data from the Chrome User Experience Report to rate page performance on mobile and desktop.
- **Sitespeed.io** — Open-source toolkit that orchestrates browsers and tools such as Browsertime and Lighthouse to collect and store web performance metrics over time.
- **Apache JMeter** — Open-source Java application for load, stress and functional testing of web applications and a wide range of networked services.
- **Grafana k6 (k6 OSS)** — Modern open-source load testing tool and engine where test scripts are written in JavaScript and run via a CLI for HTTP and other protocols.
- **Grafana** — Open-source analytics and visualization platform that builds dashboards and alerts on top of metrics, logs and traces from various data sources.
- **Gatling (Community Edition)** — Open-source load and performance testing tool for web applications and APIs, based on asynchronous non-blocking architecture.
- **Locust** — Open-source load testing framework where user behavior is defined in Python code and executed by a scalable swarm of workers.
- **Prometheus** — Open-source systems monitoring and time-series database used to collect, store and query metrics from applications and infrastructure.

## Google Lighthouse

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_GOOGLE_LIGHTHOUSE`
- **Dimensions covered:** performance (load times, Core Web Vitals), accessibility, best practices, SEO.
- **Description:** Automated auditing tool for web pages that reports performance, accessibility, best practices and SEO scores based on lab tests in a real or headless browser.
- **Link:** https://github.com/GoogleChrome/lighthouse

### Additional properties

- **Category:** web performance audit.
- **Target layer:** web frontend.
- **Target environment:** web application.
- **Resource type measured:** browser loading behavior, DOM rendering, JavaScript execution.
- **Open source:** yes.
- **Delivery model:** CLI tool, browser DevTools integration, Node.js library, CI integrations.
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** JavaScript / JSON configuration.

## WebPageTest (self-hosted)

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_WEBPAGETEST_SELF_HOSTED`
- **Dimensions covered:** performance (page load, rendering, Core Web Vitals), network behavior, caching efficiency.
- **Description:** Deep web performance testing and diagnostics tool that runs scripted browser sessions and produces detailed waterfalls, visual metrics and Core Web Vitals.
- **Link:** https://github.com/catchpoint/WebPageTest

### Additional properties

- **Category:** web performance audit and diagnostics.
- **Target layer:** web frontend.
- **Target environment:** web application.
- **Resource type measured:** HTTP requests, browser resource loading, DNS/SSL negotiation, rendering timeline.
- **Open source:** mixed (Polyform Shield on main branch; Apache 2.0 available via apache branch).
- **Delivery model:** self-hosted web UI and API, optional public SaaS.
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** Tests defined via UI or scripting (JSON, WPT scripting language).

## PageSpeed Insights

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_PAGESPEED_INSIGHTS`
- **Dimensions covered:** performance (Core Web Vitals), UX quality for real users, best practices.
- **Description:** Free Google service that combines Lighthouse lab tests with field data from the Chrome User Experience Report to rate page performance on mobile and desktop.
- **Link:** https://pagespeed.web.dev

### Additional properties

- **Category:** web performance assessment service.
- **Target layer:** web frontend.
- **Target environment:** public web application.
- **Resource type measured:** browser loading behavior, real-user timing data (RUM).
- **Open source:** no (service; uses open-source Lighthouse internally).
- **Delivery model:** web SaaS service.
- **Self-hosted possible:** no.
- **Scripting / configuration language:** Configuration via query parameters or API calls (JSON).

## Sitespeed.io

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_SITESPEED_IO`
- **Dimensions covered:** performance (load times, Web Vitals, visual metrics), network behavior, JavaScript execution cost.
- **Description:** Open-source toolkit that orchestrates browsers and tools such as Browsertime and Lighthouse to collect and store web performance metrics over time.
- **Link:** https://www.sitespeed.io

### Additional properties

- **Category:** web performance monitoring toolkit.
- **Target layer:** web frontend.
- **Target environment:** web application.
- **Resource type measured:** browser loading behavior, HTTP requests, rendering and visual changes.
- **Open source:** yes.
- **Delivery model:** CLI tool with self-hosted web UI and integrations to time-series backends.
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** JavaScript/Node.js configuration files, CLI options, Docker configuration.

## Apache JMeter

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_APACHE_JMETER`
- **Dimensions covered:** performance (latency, throughput), scalability, error rates.
- **Description:** Open-source Java application for load, stress and functional testing of web applications and a wide range of networked services.
- **Link:** https://jmeter.apache.org

### Additional properties

- **Category:** load testing.
- **Target layer:** backend / API, web frontend (HTTP), other protocols.
- **Target environment:** web application, service / API, microservices, databases and messaging systems.
- **Resource type measured:** HTTP endpoints, TCP/UDP services, JDBC, JMS, FTP, and other protocol traffic.
- **Open source:** yes.
- **Delivery model:** desktop GUI, CLI tool, self-hosted test engine.
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** XML-based test plans created via GUI or edited as text; property files for configuration.

## Grafana k6 (k6 OSS)

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_GRAFANA_K_K`
- **Dimensions covered:** performance (latency, throughput), reliability under load, error rates.
- **Description:** Modern open-source load testing tool and engine where test scripts are written in JavaScript and run via a CLI for HTTP and other protocols.
- **Link:** https://k6.io/open-source

### Additional properties

- **Category:** load testing.
- **Target layer:** backend / API, web frontend (HTTP), microservices.
- **Target environment:** service / API, web application, microservices.
- **Resource type measured:** HTTP endpoints and other protocol traffic; custom application metrics via extensions.
- **Open source:** yes (core engine); AGPLv3.
- **Delivery model:** CLI tool with optional SaaS and integrations into CI/CD.
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** JavaScript (ES6) for test scripts, CLI flags, environment variables.

## Grafana

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_GRAFANA`
- **Dimensions covered:** performance visualization (latency, throughput, resource utilization), SLO/SLA tracking, anomaly detection via alerts.
- **Description:** Open-source analytics and visualization platform that builds dashboards and alerts on top of metrics, logs and traces from various data sources.
- **Link:** https://grafana.com/oss/grafana

### Additional properties

- **Category:** monitoring / visualization.
- **Target layer:** full stack???
- **Target environment:** web application, service / API, microservices, infrastructure / cluster.
- **Resource type measured:** any metric or log data from sources such as Prometheus, Loki, Elasticsearch, Graphite, InfluxDB.
- **Open source:** yes.
- **Delivery model:** self-hosted web UI, desktop plugins, optional SaaS version (Grafana Cloud).
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** Dashboard configuration via web UI and JSON, provisioning via YAML/JSON, alert rules via UI or config files.

## Gatling (Community Edition)

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_GATLING_COMMUNITY_EDITION`
- **Dimensions covered:** performance (latency, throughput), scalability, error rates.
- **Description:** Open-source load and performance testing tool for web applications and APIs, based on asynchronous non-blocking architecture.
- **Link:** https://gatling.io/open-source

### Additional properties

- **Category:** load testing.
- **Target layer:** backend / API, web frontend (HTTP).
- **Target environment:** web application, service / API, microservices.
- **Resource type measured:** HTTP(S) traffic and related session behavior.
- **Open source:** yes (community edition).
- **Delivery model:** CLI tool, Maven/SBT/Gradle plugins, HTML reporting.
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** Scala or Gatling Java/Scala DSL for test scenarios.

## Locust

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_LOCUST`
- **Dimensions covered:** performance (latency, throughput), scalability, error rates.
- **Description:** Open-source load testing framework where user behavior is defined in Python code and executed by a scalable swarm of workers.
- **Link:** https://locust.io

### Additional properties

- **Category:** load testing.
- **Target layer:** backend / API, web frontend (HTTP), other protocols via custom clients.
- **Target environment:** service / API, web application, microservices.
- **Resource type measured:** HTTP endpoints or other custom protocol targets implemented in Python clients.
- **Open source:** yes.
- **Delivery model:** CLI tool with web UI for live monitoring.
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** Python for user behavior scripts and configuration settings.

## Prometheus

- **ID:** `SOFTWARE_PERFORMANCE_TOOLS_PROMETHEUS`
- **Dimensions covered:** performance (latency, throughput), resource utilization (CPU, memory, disk, network), error rates, queue lengths.
- **Description:** Open-source systems monitoring and time-series database used to collect, store and query metrics from applications and infrastructure.
- **Link:** https://prometheus.io

### Additional properties

- **Category:** monitoring / metrics.
- **Target layer:** backend / API, infrastructure, data / storage, full stack.
- **Target environment:** service / API, microservices, infrastructure / cluster, databases, message queues.
- **Resource type measured:** numeric metrics exposed via HTTP endpoints or exporters (latency, CPU, memory, etc.).
- **Open source:** yes.
- **Delivery model:** self-hosted server, CLI, HTTP API, integration with visualization tools.
- **Self-hosted possible:** yes.
- **Scripting / configuration language:** Configuration in YAML (scrape configs, alert rules), PromQL for queries.
