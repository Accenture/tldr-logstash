# Introduction

This container provides Logstash.

# Building

```
docker build -t tldr/logstash .
```

# Running

```
docker run -d -h logstash --name logstash -p 5000:5000 -p 5000:5000/udp --link elasticsearch tldr/logstash
```

# Testing

TODO