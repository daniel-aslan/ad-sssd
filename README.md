# SSO configuration. 

# Description
This role is used to setup SSO.

# Variables
Variabes are set under the default directory in main.yaml

  |  NAME                |    Type        | 
  | -------------------  | -------------  |
  | defaults_ad_domain         string
  | defaults_ad_admin          string
  | defaults_ad_password       string
  | defaults_fqn               boolean
  | defaults_fallback_home     boolean          
  | defaults_xxxxx_domain      boolean         
  | defaults_ad_sssd_depends   list
  | defaults_users             list
  | defaults_xxusers           list
  | defaults_groups            list
  | defaults_xxgroups          list
  | defaults_shell             string 
  | sssd_conf                  string
  | sssd_conf_owner            string

## Installation / Usage

To run the playbook update the hosts in the hosts file under inventory > oci > hosts.yaml under the 'Joiners' group and run the playbook.

```bash
ansible-playbook site.yml
```

###### Daniel Aslan 
