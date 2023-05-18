Vector  
=========  

This role installs vector  

Role Variables  
--------------------------------------  
|     vars        |    description   |  
+-----------------+------------------+  
|vector_version   |version to install|   
|vector_config_dir|local directory   |  

Example Playbook  
----------------  

    - hosts: servers  
      roles:   
         - { role: vector }  
  
License  
-------  

MIT  

Author Information  
------------------  

Rustam Mulyukov  
