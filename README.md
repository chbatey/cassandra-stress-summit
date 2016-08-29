# Cassandra stress in action

This repository contains materials for a talk on cassandra stress. A tool
packaged with cassandra to test cassandra under load.

Duration: 35 minutes.
Audience: Experienced Cassandra users.

## Intro

Duration: 5 minutes

## What?

Duration: 15 minutes

Topics covered:

* Basic mode


### User mode

Running:

```
cassandra-stress user profile=./tlp-users.yaml duration=1m "ops(insert=1,latest_event=1,events=1)" truncate=once
```

Graphing

```

```



#### Example 1: Basic example
#### Example 2: Making the data realistic


* Coordinated omission + HDR Histogram
* Distributed mode
* Graphing:

## So What?

Duration: 10 minutes

* Validation of a newly provisioned cluster
* Trying different settings
* Schema validation

## What next?

Duration: 5 minutes
