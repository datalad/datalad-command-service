# **Experimental** DataLad Command Service

This repository contains a service for DataLad. It provides a command service
that executes commands on behalf of a client, caches the result and returns the
result to the client. On the next command invocation with identical parameters,
the cached result will be returned.
