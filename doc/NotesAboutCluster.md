
### Adaptive Replica Selection
```
PUT /_cluster/settings
{
  "transient": {
    "cluster.routing.use_adaptive_replica_selection": true
  }
}
```

