Ubuntu SRU xenial, artful: 03-29-2018
=====
This Readme hosts the manual SRU verification logs for bugs related to the cloud-init SRU started on 03-01-2018.

Given [cloud-init's exception process](https://wiki.ubuntu.com/CloudinitUpdates), Ubuntu SRUs will from this point forward create an general SRU process bug which will describe related bugs/features fixed in the given cloud-init SRU. A readme like this will exist to capture any manual SRU validation performed for specific bugs or features fixed in the SRU. Generally most of the features and bugs should be covered by cloud-init's conituous integration at https://jenkins.ubuntu.com/server/view/cloud-init/.


03-29-2018 SRU: [launchpad process bug:#1759406](https://pad.lv/1759406)


This SRU is a SRU-regression fix for a single cherry-picked bug affecting only GCE instances.

The links listed below are to bugs fixed in this SRU and the verification of those bugs.

## SRU verification content
| Bug | Verification Script and Output |
| -------- |  -------- |
| EC2 manual xenial, artful | ✗ [verification output](../manual/ec2-sru-18.2-4.txt) |
| GCE manual xenial, artful | ✗ [verification output](../manual/gce-sru-18.2.4.txt) |
| Azure manual xenial, artful | ✗ [verification output](../manual/gce-sru-18.2.4.txt) |
| Nocloud-lxd logs xenial, artful | ✗ [verification output](../manual/nocloud-lxd-sru-18.2.4.txt) |
