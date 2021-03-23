# tanzu-gemfire-observability-sample



## Version Synchornization Notice:

```diff
! This repo may be out of sync with dashboards provided by the GemFire integration.
```
As shown below, the GemFire integration provided within VMware Tanzu Observability™ is the recommended way to create a dashboard.
![gemfire integration](gemfire-integration.png?raw=true "Security analysis of Tanzu-Gemfire-for-Kubernetes's Metrics")


## Overview

This repository contains example dashboards for
[Tanzu Observability by Wavefront](https://tanzu.vmware.com/observability)
as integrated with the Beta 2 release of
[Tanzu GemFire for Kubernetes](http://tgf.docs.pivotal.io/tgf/beta-2).
The dashboards give insight into the operation of
Tanzu GemFire clusters.

## Instantiate a Dashboard

Follow the instructions at
[Collect and View Metrics](https://tgf.docs.pivotal.io/tgf/beta-2/work-with-cluster.html#collect-metrics)
to install a Wavefront Collector and Proxy
and to create a Tanzu GemFire cluster.

Follow the instructions at [Create and Customize Dashboards](https://docs.wavefront.com/ui_dashboards.html) to create a dashboard,
and then [Edit the Dashboard JSON](https://docs.wavefront.com/ui_dashboards.html#edit-the-dashboard-json) to add the content from one of the samples
in the `dashboards` directory.

Your metrics should propagate to your saved dashboard within a few minutes.

## Contributing
The tanzu-gemfire-observability-sample project team welcomes contributions from the community. Before you start working with tanzu-gemfire-observability-sample, please
read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be
signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on
as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License
The code in this repository is licensed with the [MIT license](/LICENSE.txt).
