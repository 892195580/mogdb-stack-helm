# mogdb-stack-helm
## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add mogdb-stack https://892195580.github.io/mogdb-stack-helm

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the mogdb-stack chart:

    helm install my-mogdb-stack mogdb-stack/mogdb-stack

To uninstall the chart:

    helm delete my-mogdb-stack
