# Install Kubernetes Cluster by Ansible

install ansible in yout leptop/pc.

`pip install ansible`

ensure you can run `ansible`

`ansible --help`

clone this repository

`git@github.com:mosleim/ansible-install-kubernetes-cluster.git`

edit hosts file

Insert all your IP Server to install to hosts file. One for kubernetes master and one or more for worker.

run ansible

`cd ansible-install-kubernetes-cluster && ansible -h hosts install-kubernetes-cluster.yml`

type `yes` and enter if needed. :-)

wait

test

`ssh devoper@ip_master`

`kubectl get nodes`

