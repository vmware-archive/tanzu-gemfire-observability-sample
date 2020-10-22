
# tanzu-gemfire-observability-sample

## Tanzu Prerequisites
* VMware Tanzu™ GemFire for Kubernetes  
* VMware Tanzu™ Observability by Wavefront

## Overview
These dashboards are for the [Gemfire](https://gemfire.docs.pivotal.io/910/gemfire/about_gemfire.html) integration on [Tanzu Observability by Wavefront](https://tanzu.vmware.com/observability), included as part of the beta2 release of [Gemfire for Kubernetes](http://tgf.docs.pivotal.io/tgf/beta-2).

## Build & Run

### Tanzu Gemfire for Kubernetes
1. [Install](https://tgf.docs.pivotal.io/tgf/beta-2/install) Tanzu Gemfire for Kubernetes.
2. [Create](http://tgf.docs.pivotal.io/tgf/beta-2/create-and-delete.html) a Gemfire cluster.
3. [Install](http://tgf.docs.pivotal.io/tgf/beta-2/work-with-cluster.html#collect-metrics) Wavefront components.
4. Use one of our starter [dashboards](/dashboards) to create and [edit](https://docs.wavefront.com/ui_dashboards_v1.html#edit-and-save-a-dashboard) your own.
5. Your metrics should propagate to your dashboard within a few minutes.

## Contributing
The tanzu-gemfire-observability-sample project team welcomes contributions from the community. Before you start working with tanzu-gemfire-observability-sample, please
read our [Developer Certificate of Origin](https://cla.vmware.com/dco). All contributions to this repository must be
signed as described on that page. Your signature certifies that you wrote the patch or have the right to pass it on
as an open-source patch. For more detailed information, refer to [CONTRIBUTING.md](CONTRIBUTING.md).

## License
The code in this repository is licensed with the [MIT license](/LICENSE.txt).
