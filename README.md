# SPANNING-TREE-SECURITY-PROTOCOL
--------------------------------
SW-1
int range fa0/3-10
spanning-tree portfast

Bpdu guard configuration Automatic
-------------------------
spanning-tree bpduguard enable 
end

Bpdu guard Manual configuration
--------------------------------
SW-1
-------
int fa0/4
shutdown 
no shutdown
