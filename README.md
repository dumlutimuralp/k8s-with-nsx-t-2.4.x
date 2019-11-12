## VMware NSX-T and Kubernetes (K8S) Guide
by Dumlu Timuralp [@dumlutimuralp](https://twitter.com/dumlutimuralp) / [LinkedIn](https://www.linkedin.com/in/dumlutimuralp/)  
by Hakan Akkurt [LinkedIn](https://www.linkedin.com/in/hakkurt/) / [Github](https://github.com/hakkurt)

Special thanks to Raymond De Jong [LinkedIn](https://www.linkedin.com/in/dejongraymond/) / [His Blog](http://www.cloudxtreme.info/) for his feedback to make this article better.

_**This disclaimer informs readers that the views, thoughts, and opinions expressed in this series of posts belong solely to the author, and not necessarily to the author’s employer, organization, committee or other group or individual.**_

The goal of this series of posts is to outline and explain the steps to integrate VMware NSX-T Platform to Kubernetes control plane. 

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

This series does **NOT** provide the generic intro level information on NSX-T or K8S. To have a basic understanding of NSX-T please watch the VMworld session recordings. Similarly for K8S, Pluralsight and A Cloud Guru trainings by Nigel Poulton is highly recommended.  

Below articles focus on the management and data plane integration principles of NSX-T and K8S. 

### [Part 1](https://github.com/dumlutimuralp/nsx-t-k8s/blob/master/Part%201/README.md)

* Topology Information
* Fabric Preperation
* Host Transport Node
* Edge Transport Node
* Edge Cluster
* Tier 0 Logical Router
* Tier 1 Logical Router
* Tier 0 BGP Configuration
* K8S Node Dataplane Connectivity


### [Part 2](https://github.com/dumlutimuralp/nsx-t-k8s/blob/master/Part%202/README.md)

* Container Network Interface (CNI)
* NSX-T Components in Kubernetes Integration
* NSX-T & K8S Overall Architecture

### [Part 3](https://github.com/dumlutimuralp/nsx-t-k8s/blob/master/Part%203/README.md)

* Ubuntu OS Installation
* Topology
* IPAM and IP Pools
* Reachability
* Tagging NSX-T Objects for K8S
* CNI Plugin Installation
* Open vSwitch (OVS) Installation
* Docker Installation
* Deploy K8S

### [Part 4](https://github.com/dumlutimuralp/nsx-t-k8s/blob/master/Part%204/README.md)

* Current State
* NSX Container Plugin (NCP) Installation
* NSX Node Agent Installation
* Test Workload Deployment


