# Elastic Homebrew Tap

## Current Version 6.7.2

* ElasticSearch-oss
* Kibana-oss
* MetricBeat-oss

This tap is for products in the Elastic stack.

## How do I install these formulae?

Install the tap via:

    brew tap PeterSchmiedt/homebrew-skoda-elk-tap

Then you can install individual products via:

    brew install peterschmiedt/skoda-elk-tap/elasticsearch-oss

The following products are supported:

* Elasticsearch `brew install peterschmiedt/skoda-elk-tap/elasticsearch-oss`
* Logstash `brew install elastic/tap/logstash-full`
* Kibana `brew install peterschmiedt/skoda-elk-tap/kibana-oss`
* Beats
  * Auditbeat `brew install elastic/tap/auditbeat-full`
  * Filebeat `brew install elastic/tap/filebeat-full`
  * Heartbeat `brew install elastic/tap/heartbeat-full`
  * Metricbeat `brew install peterschmiedt/skoda-elk-tap/metricbeat-oss`
  * Packetbeat `brew install elastic/tap/packetbeat-full`
* APM server `brew install elastic/tap/apm-server-full`

We fully support the OSS distributions too; replace `-full` with `-oss`
in any of the above commands to install the OSS distribution. Note that
the default distribution and OSS distribution of a product can not be
installed at the same time.

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://github.com/Homebrew/brew/blob/master/docs/README.md).
