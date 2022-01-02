Lab Module TBA - Creating Storage for PKS + PKS PVC Claims
Estimated Time to Complete:
20-25 Minutes

Lab Summary:
In this lab, the student will create storage LUNS within VMware for PKS to utilize. The student will then create PVC claims for PKS to utilize using Manifest files.

Step 1 - Create Static Disk for PVC within VMware and issue the following commands down below:
SSH into ESX Host (please see lab guide for ESX Host Mapping)
cd /vmfs
cd volumes/
cd DATASTORE/
cd kubevols
vmkfstools -c 2G student-x.vmdk (where student-x equals student number)
Expected output:

TBA TBA TBA TBA TBA TBA TBA

************ This concludes the end of this Lab Module ************
