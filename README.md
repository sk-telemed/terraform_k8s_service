### Module for service

### Provider versions:
      kubernetes min "1.11.1"
#### Set up service as ClusterIP or  NP or LB.
#### Known bugs:
* K8s provider can't switch from NP or LB to clusterIP, because provider don't delete Node Port field.