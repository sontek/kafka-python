# Kafka Python client

[![Build Status](https://api.travis-ci.org/mumrah/kafka-python.png?branch=master)](https://travis-ci.org/mumrah/kafka-python)
[![Coverage Status](https://coveralls.io/repos/mumrah/kafka-python/badge.svg?branch=master)](https://coveralls.io/r/mumrah/kafka-python?branch=master)
[![Full documentation available on ReadTheDocs](https://readthedocs.org/projects/kafka-python/badge/?version=latest)](https://readthedocs.org/projects/kafka-python/?badge=latest)

[Full documentation available on ReadTheDocs](http://kafka-python.readthedocs.org/en/latest/) 

This module provides low-level protocol support for Apache Kafka as well as
high-level consumer and producer classes. Request batching is supported by the
protocol as well as broker-aware request routing. Gzip and Snappy compression
is also supported for message sets.

http://kafka.apache.org/

On Freenode IRC at #kafka-python, as well as #apache-kafka

For general discussion of kafka-client design and implementation (not python specific),
see https://groups.google.com/forum/m/#!forum/kafka-clients

# License

Copyright 2015, David Arthur under Apache License, v2.0. See `LICENSE`

# Status

The current stable version of this package is [**0.9.3**](https://github.com/mumrah/kafka-python/releases/tag/v0.9.3) and is compatible with

Kafka broker versions
- 0.8.2.0 [offset management currently ZK only -- does not support ConsumerCoordinator offset management APIs]
- 0.8.1.1
- 0.8.1
- 0.8.0

Python versions
- 2.6 (tested on 2.6.9)
- 2.7 (tested on 2.7.9)
- 3.3 (tested on 3.3.5)
- 3.4 (tested on 3.4.2)
- pypy (tested on pypy 2.4.0 / python 2.7.8)
