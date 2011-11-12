# Knockbox

knockbox is an eventual-consistency toolbox for Clojure,
and eventually the JVM in general. It's inspired by
[statebox](https://github.com/mochi/statebox) and
the paper
[A comprehensive study of Convergent and Commutative Replicated Data Types](http://hal.archives-ouvertes.fr/inria-00555588/).


Databases like [Riak](https://github.com/basho/riak) let you trade consistency for availability.
This means that you can have two conflicting values for a particular key. Resolving these conflicts
is up to application-logic in the database clients. Certain data-types and operations are suited
for automatic conflict-resolution. This project is a collection of these data-types and operations.

## Status

knockbox is currently in development and the API will be changing quickly, without notice.
