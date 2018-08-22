# NGINX Ingress Controller Releases

We publish Ingress Controller releases on GitHub. See our [releases page](https://github.com/nginxinc/kubernetes-ingress/releases).

The latest stable release is [1.3.0](https://github.com/nginxinc/kubernetes-ingress/releases/tag/v1.3.0). For production use, we recommend that you choose the latest stable release.  As an alternative, you can choose the *edge* version built from the [latest commit](https://github.com/nginxinc/kubernetes-ingress/commits/master) from the master branch. The edge version is useful for experimenting with new features that are not yet published in a stable release.

To use the Ingress Controller, you need to have access to:
* An ingress controller image.
* Installation manifests or a Helm chart.
* Documentation and examples.

It is important that the versions of those things above match. 

The table below summarizes the options regarding the images, manifests, helm chart, documentation and examples and gives your links to the correct versions:

| Version | Description |  Image for NGINX | Image for NGINX Plus | Installation Manifests and Helm Chart | Documentation and Examples |
| ------- | ----------- | --------------- | -------------------- | ---------------------------------------| -------------------------- |
| Latest stable release | For production use | `nginx/nginx-ingress:1.3.0`, `nginx/nginx-ingress:1.3.0-alpine` from [DockerHub](https://hub.docker.com/r/nginx/nginx-ingress/) or [build your own image](https://github.com/nginxinc/kubernetes-ingress/tree/v1.3.0/nginx-controller). | [Build your own image](https://github.com/nginxinc/kubernetes-ingress/tree/v1.3.0/nginx-controller). | [Manifests](https://github.com/nginxinc/kubernetes-ingress/tree/v1.3.0/install). [Helm chart](https://github.com/nginxinc/kubernetes-ingress/tree/v1.3.0/helm-chart). | [Documentation](https://github.com/nginxinc/kubernetes-ingress/tree/v1.3.0/docs). [Examples](https://github.com/nginxinc/kubernetes-ingress/tree/v1.3.0/examples). |
| Edge | For testing and experimenting | `nginx/nginx-ingress:edge`, `nginx/nginx-ingress:edge-alpine` from [DockerHub](https://hub.docker.com/r/nginx/nginx-ingress/) or [build your own image](https://github.com/nginxinc/kubernetes-ingress/tree/master/nginx-controller). | [Build your own image](https://github.com/nginxinc/kubernetes-ingress/tree/master/nginx-controller). | [Manifests](https://github.com/nginxinc/kubernetes-ingress/tree/master/install). [Helm chart](https://github.com/nginxinc/kubernetes-ingress/tree/master/helm-chart). | [Documentation](https://github.com/nginxinc/kubernetes-ingress/tree/master/docs). [Examples](https://github.com/nginxinc/kubernetes-ingress/tree/master/examples). |
