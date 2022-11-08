# helm-charts
## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add jshaktiraj https://jshaktiraj.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
jshaktiraj` to see the charts.

To install the <chart-name> chart:

    helm install cloud-native-weather-nodejs-0.1.0 jshaktiraj/cloud-native-weather-nodejs-0.1.0

To uninstall the chart:

    helm delete cloud-native-weather-nodejs-0.1.0
