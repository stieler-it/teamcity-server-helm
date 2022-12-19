Helm chart to deploy TeamCity server into a Kubernetes cluster.

This chart includes some hardcoded values for our purpose and probably needs some modification to work in other environments.

How to install
--

Checkout the repo and cd to the directory, then:

    helm upgrade --install teamcity-server . --namespace teamcity
