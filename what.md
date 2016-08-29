# What?

Example 1:

Load testing a custom schema:

`cql-stress-example-1.yaml`

Simple time series model where we want to test a schema for tracking staff
activities over time.

// Insert table

Now we could randomly generate data but this won't be like the real data.

We could also try and take data from production, but wait this application
hasn't been made yet :-/

What is important is that the distribution of our test data is similar to the
distribution of the data in production.

This is important for all databases but especially cassandra when you expect to
scale out your application.

The important numbers:

* How many staff members do we have?
* What is the rate of the activities each staff member does?
* What is the size of the payload that we want to store?

This can validate our schema by checking:

* How big are our partitions over time going to be?
* How will this affect ready performance?
