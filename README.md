Role Name
=========

Configure the Jenkins

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

# vars for RPM based
* epel_url: 
* java8_rpm
* jenkins_key_rpm
* jenkins_repo_yum

# vars for Debian based
* java8_apt
* Jenkins_key_deb
* jenkins_repo_deb

Supported OS
--------------
* Redhat8
* Redhat7
* Centos8
* Centos7
* Ubuntu-20.04
* Ubuntu-18.04
* Ubuntu-16.04
* Fedora

Dependencies
------------
* Python2 or Python3
* Ansible

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }


Detailed Explanation
------------
[Detailed Explanation](https://rootritesh.medium.com/ansible-jenkins-role-58088247b4bd)
