DISA STIG for Red Hat Enterprise Linux 7
=========

Ansible remediation role for profile stig-rhel7-disa  
Profile Title:  DISA STIG for Red Hat Enterprise Linux 7  
Profile Description:  
  
This profile contains configuration checks that align to the   
DISA STIG for Red Hat Enterprise Linux V1R1.  
  
In addition to being applicable to RHEL7, DISA recognizes this   
configuration baseline as applicable to the operating system  
tier of Red Hat technologies that are based off RHEL7, such as RHEL  
Server,  RHV-H, RHEL for HPC, RHEL Workstation, and Red Hat   
Storage deployments.  
  
  
Benchmark ID:  RHEL-7  
Benchmark Version:  0.1.38  
  
XCCDF Version:  1.1  
  
This file was generated by OpenSCAP 1.2.16 using:  
	$ oscap xccdf generate fix --profile stig-rhel7-disa --template urn:xccdf:fix:script:ansible sds.xml   
  
This script is generated from an OpenSCAP profile without preliminary evaluation.  
It attempts to fix every selected rule, even if the system is already compliant.  
  
How to apply this remediation role:  
$ ansible-playbook -i "192.168.1.155," playbook.yml  
$ ansible-playbook -i inventory.ini playbook.yml