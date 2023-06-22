### Kubernetes,

**Getting started ,** https://kubernetes.io/docs/setup/

**Install Tools ,** https://kubernetes.io/docs/tasks/tools/

**Installing Kubernetes with deployment tools ,** https://kubernetes.io/docs/setup/production-environment/tools/


### KUBEADM,

**Bootstrapping clusters with kubeadm ,** https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/

**Installing kubeadm ,** https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/

<br>

### System configuration,

**Keep firewalld and SELinux turned off,**

`anup@ubuntu-22042-08:~$ sudo systemctl status ufw.service `

`anup@ubuntu-22042-08:~$ ufw status `


**For : [WARNING Swap]: swap is enabled; production deployments should disable swap unless testing the NodeSwap feature gate of the kubelet**

`anup@ubuntu-22042-08:~$ sudo swapoff -a `

<br>

**Troubleshoot**

`anup@ubuntu-22042-08:~$ sudo kubeadm reset`

`anup@ubuntu-22042-08:~$ ls -ltra`

`anup@ubuntu-22042-08:~/.kube$ ls -ltr`

<br>
