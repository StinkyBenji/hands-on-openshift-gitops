# hands-on-openshift-gitops

This demo presents a basic setup of openshift-gitops operator with add-on services like argocd-notifications, HaShiCorp Vault with argocd-vault-plugin.

### Configure HashiCorp Vault

Now we have
Details can be found in [README.md]

### Install openshift-gitops operator

First, we need to install openshift-gitops operator on our OpenShift cluster. The simplest solution is to install it on Operator Hub.

Once it's installed, we can configure the default openshift-gitops (an Argo CD instance) by executing

`oc apply -k gitops-config-manager/overlays`

More details can be found in [README.md]

### Configure HashiCorp Vault

Now we have
Details can be found in [README.md]

### Configure the argocd-notifications controller

Details can be found in [README.md]

### More to read
