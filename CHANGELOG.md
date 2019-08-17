# Ansible Role for RBD Volume Provisioner on Kubernetes

## 3.3.0 - TBC

### Major Changes

## 3.2.0 - 2019-07-08

### Major Changes

  - Update LXD test profile for Kubernetes v1.15.0 support
  - Add dummy tasks and vars placeholder for multi OS support
  - Fix molecule `group_vars` with links
  - Replace `with_items` with `loop`
  - Replace `with_dict` with `var`
  - Replace `with_first_found` with `lookup('first_found')`
  - Update Vagrant test with `private_network`
  - Reduce hardcoded `ansible_default_ipv4`

## 3.1.0 - 2019-06-13

### Major Changes

## 3.0.0 - 2019-06-12

  - Initial release for Ansible 2.8 or higher
  - Support both Ubuntu 16.04/18.04 or RHEL/CentOS 7 or openSUSE Leap 15
