# consul-bounce

Attempts to solve the problem of restarting a cluster without bringing down too many nodes at once.

## Problem statement

 - I have a set of instances (nodes, processes, etc).
 - I want to restart all of these instances.
 - I can tolerate failure in some number (>=1) of these instances, but not too many at once.
