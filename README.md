Role Name
=========

 A role to create ESXI guest.

Requirements
------------


Role Variables
--------------
```
vmware_vm:
  vms:
  - vm1:
      hostname:
      username:
      password:
      validate_certs:
      folder:
      name:
      state:
      template:
      disk:
      - size_gb:
        type:
        datastore:
      hardware:
        memory_mb:
        num_cpus:
        scsi:
      networks:
      - name:
        mac:
      wait_for_ip_address:

    
 
```
Dependencies
------------


Example Playbook
----------------



License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
