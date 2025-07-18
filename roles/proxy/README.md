Role Name
=========

Role for install Haproxy 3.0 on Ubuntu 22.04


Role Variables
--------------

Create file with variables. Add into file 
ha_cluster_virtual_ip: C.I.D.R # Virtual k8s cluster ip addr
ha_cluster_virtual_port: port number # != 6443 or another control plane k8s ports


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      vars_files:
        - /path/to/var_file
      roles:
         - { role: username.rolename, x: 42 }
