# awesome-influxdb

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
* [influxdb-haskell](https://github.com/maoe/influxdb-haskell) - Haskell client library for InfluxDB
* [InfluxDB.NET](https://github.com/ziyasal/InfluxDB.Net) - .NET client for InfluxDB
* [InfluxDB PHP SDK](https://github.com/corley/influxdb-php-sdk) - UDP/IP or HTTP adapters for read and write data
* [influxdbr](https://github.com/dleutnant/influxdbr) - R library for InfluxDB
* [node-influx](https://github.com/node-influx/node-influx) - InfluxDB Node.js Client

## Collecting data into InfluxDB

### Projects

#### Dedicated

Tools whose primary or sole purpose is to feed data into InfluxDB.

* [agento](https://github.com/abrander/agento) - Client/server collecting near realtime metrics from Linux hosts
* [sysinfo_influxdb](https://github.com/novaquark/sysinfo_influxdb) - Collect and send system (linux) info to InfluxDB.
* [Telegraf](https://github.com/influxdb/telegraf) - (Official) plugin-driven server agent for reporting metrics into InfluxDB

#### Non-dedicated

Tools that generate data that feed into multiple backends, InfluxDB included

* [cAdvisor](https://github.com/google/cadvisor) - Analyzes resource usage and performance characteristics of running containers
* [cloudwatch-sender](https://github.com/BBC-News/cloudwatch-sender) - Send metrics to InfluxDB/Graphite from Cloudwatch
* [gatling](https://github.com/gatling/gatling) - Async Scala-Akka-Netty based Stress Tool
* [Graphios](https://github.com/shawn-sterling/graphios) - A program to send nagios perf data to graphite (carbon) / statsd / librato / influxDB
* [heapster](https://github.com/GoogleCloudPlatform/heapster) - Monitor container resource usage of a Kubernetes cluster
* [heka](https://github.com/mozilla-services/heka) - General purpose data collection and processing tool
* [Riemann](https://github.com/aphyr/riemann) - A network event stream processing system, in Clojure
* [statsd-jvm-profiler](https://github.com/etsy/statsd-jvm-profiler) - Simple JVM Profiler Using StatsD

### Libraries

Libraries to collect data and feed into InfluxDB.

* [telemetry](https://github.com/arussellsaw/telemetry) - metric reporting for Go applications

### Plugins

Plugins to allow other standalone tools to send their data into InfluxDB.

* [fluent-plugin-influxdb](https://github.com/fangli/fluent-plugin-influxdb) - A buffered output plugin for fluentd and InfluxDB
* [kafka-influxdb](https://github.com/mre/kafka-influxdb) - A Kafka consumer for InfluxDB written in Python
* [mod-influxdb](https://github.com/savoirfairelinux/mod-influxdb) - Shinken module for exporting data to InfluxDB
* [sensu-plugins-influxdb](https://github.com/sensu-plugins/sensu-plugins-influxdb) - Sensu InfluxDB Plugins

## Consuming data from InfluxDB

### Dashboards and visualization

* [Chronograf](https://influxdb.com/chronograf/index.html) - Official InfluxDB data visualization tool (closed source)
* [facette](https://github.com/facette/facette) - Time series data visualization and graphing software
* [grafana](https://github.com/grafana/grafana) - Gorgeous metric viz, dashboards & editors for Graphite, InfluxDB & OpenTSDB
* [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB

### Other tools

* [Morgoth](https://github.com/nathanielc/morgoth) - Metric anomaly detection

## Provisioning InfluxDB

Tools, libraries, etc. to help you get InfluxDB running without installing it by hand.

* [chef-influxdb](https://github.com/SimpleFinance/chef-influxdb) - Chef cookbook for InfluxDB
* [golja-influxdb](https://github.com/n1tr0g/golja-influxdb) - Puppet module for InfluxDB
* [influxdb-formulaf](https://github.com/saltstack-formulas/influxdb-formula) - Installs and configures the InfluxDB timeseries database
* [palkan-ansible/influxdb](https://github.com/palkan-ansible/influxdb) - Installs InfluxDB 0.9.X on Ansible
* [tutum-docker-influxdb](https://github.com/tutumcloud/influxdb) - Docker image to run an out-of-the-box InfluxDB server

## Queries

* [dbal-influxdb](https://github.com/corley/dbal-influxdb) - Doctrine DBAL for InfluxDB
* [Influxdb::Arel](https://github.com/undr/influxdb-arel) - Influxdb::Arel is a SQL AST manager for InfluxDB dialect. It simplifies the generation of complex SQL queries

## Other awesome lists

### Awesome lists that include links to InfluxDB

* [awesome-bigdata](https://github.com/onurakpolat/awesome-bigdata)
* [awesome-dashboard](https://github.com/obazoud/awesome-dashboard)
* [awesome-db](https://github.com/numetriclabz/awesome-db)
* [awesome-go](https://github.com/avelino/awesome-go)
* [awesome-sysadmin](https://github.com/kahun/awesome-sysadmin)

### Lists of awesome lists that include awesome-influxdb

* [awesome](https://github.com/sindresorhus/awesome)
* [lists](https://github.com/jnv/lists)

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors and contributors have waived all copyright and related or neighboring rights to awesome-influxdb.
