# awesome-influxdb [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome projects, libraries, tools, etc. related to [InfluxDB](https://influxdb.com/).
This list focuses on libraries, tools, etc. supporting InfluxDB version 0.9 and up.

Want to make this list better?
Take a look at our page on [contributing](CONTRIBUTING.md) and then open a pull request!

## Reference material

If you know of any particularly useful blog posts, talks, slides, etc. that belong in this list, please open a pull request!

* [Official documentation](https://influxdb.com/docs/v0.9/introduction/overview.html)

## Client libraries

### Official

* [Go](https://github.com/influxdb/influxdb/tree/master/client) - Go client for InfluxDB, contained as package within main InfluxDB repo
* [Java](https://github.com/influxdb/influxdb-java) - Java client for InfluxDB
* [PHP](https://github.com/influxdb/influxdb-php) - PHP client for InfluxDB
* [Python](https://github.com/influxdb/influxdb-python) - Python client for InfluxDB
* [Ruby](https://github.com/influxdb/influxdb-ruby) - Ruby client for InfluxDB

### Unofficial

* [capacitor](https://github.com/olauzon/capacitor) - A Clojure client for InfluxDB
* [cl-influxdb](https://github.com/mmaul/cl-influxdb) - Common Lisp interface to the Time Series Database InfluxDB
* [erflux](https://github.com/gossiperl/erflux) - InfluxDB client for Erlang
* [influent.rs](https://github.com/gobwas/influent.rs) - InfluxDB Rust driver
* [InfluxDB-Client-LabVIEW](https://github.com/johanvandenbroek/InfluxDB-Client-LabVIEW) - LabVIEW client for InfluxDB
* [influxdb-haskell](https://github.com/maoe/influxdb-haskell) - Haskell client library for InfluxDB
* [influxdb-lineprotocol](https://github.com/nblumhardt/influxdb-lineprotocol) - A .NET library for efficiently sending points to InfluxDB
* [InfluxDB.NET](https://github.com/ziyasal/InfluxDB.Net) - .NET client for InfluxDB
* [InfluxDB PHP SDK](https://github.com/corley/influxdb-php-sdk) - UDP/IP or HTTP adapters for read and write data
* [influxdbr](https://github.com/dleutnant/influxdbr) - R library for InfluxDB
* [instream](https://github.com/mneudert/instream) - InfluxDB driver for Elixir
* [node-influx](https://github.com/node-influx/node-influx) - InfluxDB Node.js Client
* [scala-influxdb-client](https://github.com/paulgoldbaum/scala-influxdb-client) - Asynchronous InfluxDB client for Scala

## Collecting data into InfluxDB

### Projects

#### Dedicated

Tools whose primary or sole purpose is to feed data into InfluxDB.

* [agento](https://github.com/abrander/agento) - Client/server collecting near realtime metrics from Linux hosts
* [aggregateD](https://github.com/ccpgames/aggregateD) - A dogstatsD inspired metrics and event aggregation daemon for InfluxDB
* [Charmander](https://github.com/att-innovate/charmander) - Charmander is a lab environment for measuring and analyzing resource-scheduling algorithms
* [Influx-Capacitor](https://github.com/poxet/Influx-Capacitor) - Influx-Capacitor collects metrics from windows machines using Performance Counters. Data is sent to influxDB to be viewable by grafana
* [influxsnmp](https://github.com/paulstuart/influxsnmp) - Poll network devices via SNMP and save the data in InfluxDB
* [mesos-influxdb-collector](https://github.com/kpacha/mesos-influxdb-collector) - Lightweight mesos stats collector for InfluxDB
* [mqforward](https://github.com/shirou/mqforward) - MQTT to influxdb forwarder
* [nest_poller](https://github.com/grempe/nest_poller) - A simple hack to retrieve and publish some statistics about Nest devices to an InfluxDB instance
* [ntp_checker](https://github.com/fss1/ntp_checker) - compares internal NTP sources and warns if the offset between servers exceeds a definable (fraction of) seconds
* [sysinfo_influxdb](https://github.com/novaquark/sysinfo_influxdb) - Collect and send system (linux) info to InfluxDB
* [Telegraf](https://github.com/influxdb/telegraf) - (Official) plugin-driven server agent for reporting metrics into InfluxDB
* [tesla-streamer](https://github.com/timdorr/tesla-streamer) - Streams data from Tesla Model S to InfluxDB

#### Non-dedicated

Tools that generate data that feed into multiple backends, InfluxDB included.

* [cAdvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers
* [cloudwatch-sender](https://github.com/BBC-News/cloudwatch-sender) - Send metrics to InfluxDB/Graphite from Cloudwatch
* [crankshaftd](https://github.com/Xorlev/crankshaftd) - Simple Go agent to ingest streaming data from Turbine via SSE and push it into StatsD as a gauge or to InfluxDB
* [gatling](https://github.com/gatling/gatling) - Async Scala-Akka-Netty based Stress Tool
* [Glances](https://github.com/nicolargo/glances) - Glances an Eye on your system
* [Graphios](https://github.com/shawn-sterling/graphios) - A program to send nagios perf data to graphite (carbon) / statsd / librato / influxDB
* [heapster](https://github.com/GoogleCloudPlatform/heapster) - Monitor container resource usage of a Kubernetes cluster
* [heka](https://github.com/mozilla-services/heka) - General purpose data collection and processing tool
* [internet_data_usage](https://github.com/precurse/internet_data_usage) - Python based application to pull data plan usage for different carriers such as Telus and Koodo
* [metrics.sh](https://github.com/pstadler/metrics.sh) - Collect and forward metrics using portable shell scripts
* [Riemann](https://github.com/aphyr/riemann) - A network event stream processing system, in Clojure
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler) - Simple JVM Profiler Using StatsD

### Libraries

Libraries to collect data and feed into InfluxDB.

* [crow-metrics](https://github.com/robey/crow-metrics) - small metrics collector for node servers
* [django-influxdb-metrics](https://github.com/bitmazk/django-influxdb-metrics) - A reusable Django app that sends metrics about your project to InfluxDB
* [metrics](https://github.com/beberlei/metrics) - (PHP) Simple library that abstracts different metrics collectors. "I find this necessary to have a consistent and simple metrics (functional) API that doesn't cause vendor lock-in"
* [pyVsphereInflux](https://github.com/fennm/pyVsphereInflux) - A library and supporting script for pulling data from vSphere and inserting it into InfluxDB
* [telemetry](https://github.com/arussellsaw/telemetry) - metric reporting for Go applications

#### Hooks

Hooks for other logging libraries to output to InfluxDB.

* [go-metrics-influxdb](https://github.com/vrischmann/go-metrics-influxdb) - A reporter for the go-metrics library which will post the metrics to InfluxDB
* [logrus_influxdb](https://github.com/Abramovic/logrus_influxdb) - InfluxDB Hook for Logrus

### Plugins

Plugins to allow other standalone tools to send their data into InfluxDB.

* [exometer_influxdb](https://github.com/travelping/exometer_influxdb) - Exometer reporter for InfluxDB
* [fluent-plugin-influxdb](https://github.com/fangli/fluent-plugin-influxdb) - A buffered output plugin for fluentd and InfluxDB
* [influx-nagios-plugin](https://github.com/shaharke/influx-nagios-plugin) - Nagios plugin for querying monitoring stats from InfluxDB
* [kafka-influxdb](https://github.com/mre/kafka-influxdb) - A Kafka consumer for InfluxDB written in Python
* [logstash-output-influxdb](https://github.com/logstash-plugins/logstash-output-influxdb) - Community-maintained Logstash plugin to output metrics to InfluxDB
* [metrics-influxdb](https://github.com/davidB/metrics-influxdb) - A reporter for dropwizard metrics which announces measurements to an InfluxDB server
* [mod-influxdb](https://github.com/savoirfairelinux/mod-influxdb) - Shinken module for exporting data to InfluxDB
* [sensu-plugins-influxdb](https://github.com/sensu-plugins/sensu-plugins-influxdb) - Sensu InfluxDB Plugins
* [statsd-influxdb-backend](https://github.com/bernd/statsd-influxdb-backend) - A naive InfluxDB backend for StatsD

### Import tools

Tools to import a fixed set of data into InfluxDB.

* [nmon2influxdb](https://github.com/adejoux/nmon2influxdb) - Import nmon file into InfluxDB

## Consuming data from InfluxDB

### Dashboards and visualization

* [Chronograf](https://influxdb.com/chronograf/index.html) - Official InfluxDB data visualization tool (closed source)
* [facette](https://github.com/facette/facette) - Time series data visualization and graphing software
* [grafana](https://github.com/grafana/grafana) - Gorgeous metric viz, dashboards & editors for Graphite, InfluxDB & OpenTSDB
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB

### Other tools

* [hubot-influxdb-alerts](https://github.com/amwelch-oss/hubot-influxdb-alerts) - Create and manage alerts in your chatroom using hubot and influxdb
* [influx-alert](https://github.com/joshrendek/influx-alert) - A tool to query InfluxDB and send alerts based on a YAML config
* [Morgoth](https://github.com/nathanielc/morgoth) - Metric anomaly detection

## Provisioning InfluxDB

Tools, libraries, etc. to help you get InfluxDB running without installing it by hand.

* [chef-influxdb](https://github.com/SimpleFinance/chef-influxdb) - Chef cookbook for InfluxDB
* [golja-influxdb](https://github.com/n1tr0g/golja-influxdb) - Puppet module for InfluxDB
* [influxdb-formulaf](https://github.com/saltstack-formulas/influxdb-formula) - Installs and configures the InfluxDB timeseries database
* [influxdb-release](https://github.com/pivotal-cf-experimental/influxdb-release) - Experimental BOSH release for InfluxDB
* [palkan-ansible/influxdb](https://github.com/palkan-ansible/influxdb) - Installs InfluxDB 0.9.X on Ansible
* [tutum-docker-influxdb](https://github.com/tutumcloud/influxdb) - Docker image to run an out-of-the-box InfluxDB server

## Queries

* [dbal-influxdb](https://github.com/corley/dbal-influxdb) - Doctrine DBAL for InfluxDB
* [Influxdb::Arel](https://github.com/undr/influxdb-arel) - Influxdb::Arel is a SQL AST manager for InfluxDB dialect. It simplifies the generation of complex SQL queries
* [influxer](https://github.com/palkan/influxer) - InfluxDB ActiveRecord-style

## Other awesome lists

### Awesome lists that include links to InfluxDB

* [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata)
* [awesome-dashboard](https://github.com/obazoud/awesome-dashboard)
* [awesome-data-engineering](https://github.com/igorbarinov/awesome-data-engineering)
* [awesome-db](https://github.com/numetriclabz/awesome-db)
* [awesome-go](https://github.com/avelino/awesome-go)
* [awesome-sysadmin](https://github.com/kahun/awesome-sysadmin)

### Lists of awesome lists that include awesome-influxdb

* [awesome](https://github.com/sindresorhus/awesome)
* [lists](https://github.com/jnv/lists)

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors and contributors have waived all copyright and related or neighboring rights to awesome-influxdb.
