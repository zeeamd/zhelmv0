# zhelmv0

--Action Required: Tiller & Helm 2 is set for deprecation on November 13th, 2020

--setup kubernetes cluster on Ubuntu 20.04.5 LTS
https://www.letscloud.io/community/how-to-install-kubernetesk8s-and-docker-on-ubuntu-2004

--repo for ubuntu kubernetes
/etc/apt/sources.list
deb https://apt.kubernetes.io kubernetes-xenial main
apt-get update

--setup helm
https://devopscube.com/install-configure-helm-kubernetes/

--crictl cli for kubernetes container runtime
https://iximiuz.com/en/posts/containerd-command-line-clients/

--sample helm charts repo

--https://artifacthub.io/

# karpenter is helm to deploy karpenter node scaler to aws eks
helm install karpenter . -n karpenter --set clusterName="ABC",role="QWE"
