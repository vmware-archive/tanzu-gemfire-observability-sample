
# tanzu-gemfire-observability-sample

## Overview

This repository contains example dashboards for
[Tanzu Observability by Wavefront](https://tanzu.vmware.com/observability)
as integrated with the beta2 release of
[Tanzu GemFire for Kubernetes](http://tgf.docs.pivotal.io/tgf/beta-2).
The dashboards give insight into the operation of
Tanzu GemFire clusters.

## Instantiate a Dashboard

Follow the directions at
[Collect and View Metrics](https://tgf.docs.pivotal.io/tgf/beta-2/work-with-cluster.html#collect-metrics)
to install a Wavefront Collector and Proxy
and to create a Tanzu GemFire cluster.

Follow the instructions at [Create and Customize Dashboards](https://docs.wavefront.com/ui_dashboards.html) to first create a dashboard,
and then edit the dashboard to add the content from one of the samples
in the `dashboards` directory.

Your metrics should propagate to your saved dashboard within a few minutes.

## Contributing
The tanzu-gemfire-observability-sample project team welcomes contributions from the community. Before you start working with tanzu-gemfire-observability-sample, please
read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be
signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on
as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License
The code in this repository is licensed with the [MIT license](/LICENSE.txt).
