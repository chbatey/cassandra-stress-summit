# Intro

## Scenario 1: Application developer 

You're building an application you are expecting to scale out. Cassandra is the
natural choice.

Cassandra projects succeed or fail based on their schema. No more normalisation.
You have to get this right and once you have TBs of user data it is hard to
change.

Option 1: Give data modelling a go, build your application  and then monitor :(
Option 2: Design a schema and then load it up front with realistic data

This talk will show you how to do number two.

## Scenario 2: Cassandra ops hero

You're building out a cluster and want to work out the best hardware, linux and
cassandra configuration for your needs.

Option 1: Pick something and wait for the application teams to load test their
applications :(
Option 2: Load test your cluster with realistic data before the app teams even
create a repo.

This talk will show you how to do number two.
