## VMware NSX-T with Kubernetes (K8S) Installation Guide
by Dumlu Timuralp [@dumlutimuralp](https://twitter.com/dumlutimuralp) / [LinkedIn](https://www.linkedin.com/in/dumlutimuralp/)  
by Hakan Akkurt [LinkedIn](https://www.linkedin.com/in/hakkurt/) / [Github](https://github.com/hakkurt)

_**This disclaimer informs readers that the views, thoughts, and opinions expressed in the text belong solely to the author, and not necessarily to the author’s employer, organization, committee or other group or individual.**_

The goal of this series of posts is to outline and explain the steps to integrate VMware NSX-T Platform with Kubernetes. 

Software components used are shown below.

- vCenter 6.7 U1b (Build 11727113)
- ESX 6.7 U2 (Build 13006603)
- NSX-T 2.4.1 (Build 13716579)
- NSX Container Plugin 2.4.1 (Build 13515827)
- Ubuntu Server 16.04.5
- Docker CE 18.09.6
- Kubernetes 1.14.2
- Open vSwitch 2.10.2.13185890

It is highly recommended to check the following resources for compatibility requirements
* VMware Product Interoperability Matrices  
https://www.vmware.com/resources/compatibility/sim/interop_matrix.php#interop&175=&2=&1=
* VMware NSX Container Plugin Release Notes 
https://docs.vmware.com/en/VMware-NSX-T-Data-Center/index.html

This series does NOT provide the 101 level info neither on NSX-T nor on K8S. To have a basic understanding of NSX-T please watch the VMworld 2018 session recordings. For K8S, Pluralsight and A Cloud Guru trainings by Nigel Poulton is highly recommended.  

Below articles focus on the basic integration principles of NSX-T and K8S. Hopefully we will be able to dive into details and troubleshooting in upcoming articles.

### [Part 1](https://github.com/dumlutimuralp/nsx-t-k8s/blob/master/Part%201/README.md)

### [Part 2](https://github.com/dumlutimuralp/nsx-t-k8s/blob/master/Part%202/README.md)

### [Part 3](https://github.com/dumlutimuralp/nsx-t-k8s/blob/master/Part%203/README.md)

### [Part 4](https://github.com/dumlutimuralp/nsx-t-k8s/blob/master/Part%204/README.md)


