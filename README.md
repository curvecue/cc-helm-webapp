## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add cc-helm-webapp https://curvecue.github.io/cc-helm-webapp

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
cc-helm-webapp` to see the charts.

To install the cc-helm-webapp chart:

    helm install cc-helm-webapp cc-helm-webapp

To uninstall the chart:

    helm delete cc-helm-webapp