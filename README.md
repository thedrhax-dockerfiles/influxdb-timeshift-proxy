# InfluxDB Timeshift Proxy for Docker [![](https://images.microbadger.com/badges/image/thedrhax/influxdb-timeshift-proxy.svg)](https://hub.docker.com/r/thedrhax/influxdb-timeshift-proxy)

This image contains a [proxy](https://github.com/maxsivanov/influxdb-timeshift-proxy) for InfluxDB.

## Exaple:

```
docker run -it --rm -p 8089:8089 -e INFLUXDB="your-server:8086" thedrhax/influxdb-timeshift-proxy
```
