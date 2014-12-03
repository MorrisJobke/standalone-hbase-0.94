# standalone-hbase-0.94

The image [tobegit3hub/standalone-hbase-0.94](https://registry.hub.docker.com/u/tobegit3hub/standalone-hbase-0.94/) is based on Ubuntu 14.04, Oracle Java 7 and HBase 0.94.11.

You can easily specify the version of OS, Java and HBase in [Dockerfil](Dockerfile).

## Usage

Just one command to run standalone hbase.

```
docker run -d --net=host -p 2181:2181 -p 60000:60000 -p 60010:60010 -p 60020:60020 -p 60030:60030 tobegit3hub/standalone-hbase-0.94
```

Then you can check Web UI in <http://127.0.0.1:60010>. Or run [smoke-hbase](https://github.com/tobegit3hub/smoke-hbase) for test.

