# emitio

emitio is an agent that accepts streams of unparsed data tagged with metadata.
emitio is meant to be extensible to other forwarding agents that can produce different types of data: logs via rsyslog, logs via file tailing, metrics from statsd, or even a file reader.
Other systems make data available to emitio via this API.
