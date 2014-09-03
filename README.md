# standalone-hbase-0.94

The container [tobegit3hub/standalone-hbase-0.94](https://registry.hub.docker.com/u/tobegit3hub/standalone-hbase-0.94/) is based on Ubuntu 14.04, Oracle Java 7 and HBase 0.94.11.

You can check out the hbase trunk in [standalone-hbase](https://github.com/tobegit3hub/standalone-hbase).

## Usage

1. Build the image or not, `docker build -t tobegit3hub/standalone-hbase .`
2. `docker run -d --name standalone-hbase-0.94 -p 2181:2181 -p 60000:60000 -p 60010:60010 -p 60020:60020 -p 60030:60030 tobegit3hub/standalone-hbase-0.94`
3. Go to <127.0.0.1:60010> or `docker logs standalone-hbase-0.94`

