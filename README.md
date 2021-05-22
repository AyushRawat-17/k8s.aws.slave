## Kubernetes AWS Slave

This Role used to configure the Kubernetes Worker Node on the AWS Linux 2 with the Container Engine **Docker** and CNI **Flannel**.If we use the `ayushrawat_17.k8s_aws_master` role before configuring master for this Worker Node it automatically gets the token from there else we can also provide the token and ca certificate Id manually.

## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

**Example Playbook**
----------------

```yaml
---
    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }
```

## License
BSD

## Author Information
 - **Ayush Rawat** (ayushrawatkv@gmail.com)
     - https://twitter.com/rawatayush17