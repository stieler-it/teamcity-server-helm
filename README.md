Helm chart to deploy TeamCity server into a Kubernetes cluster.

This chart includes some hardcoded values for our purpose and probably needs some modification to work in other environments.

How to install & upgrade
--

Checkout the repo and cd to the directory, then:

    helm upgrade --install --namespace teamcity -f chitai4.values.yaml teamcity-server . 

Replace chitai4.values.yaml with your environment specific variables.
