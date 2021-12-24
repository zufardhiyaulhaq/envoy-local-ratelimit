# Envoy Local Ratelimit
used for spiking envoy local ratelimit

### Topology
This using 2 service
- envoy, proxy where ratelimit take place
- podinfo, a service that need to be ratelimited

### Usage
- start all services
```
make up
```

- try to curl podinfo
```
curl http://172.19.0.3/
```
