wildfly-install
===============

Role to install wildfly

Requirements
------------

- java-1.8-openjdk on the managed node

Role Variables
--------------

https_uri: https://download.jboss.org/wildfly/24.0.1.Final/wildfly-24.0.1.Final.zip
wildfly_user: wildfly
server_url: <server_url>
wildfly_version: wildfly-24.0.1.Final
mgmt_user: <management_username>
mgmt_user_pass: <management_user_password> 
war_download_url: https://github.com/vimallinuxworld13/jboss-sample-war-Dockerfile/blob/master/jboss-as-helloworld.war?raw=true
deploy_war_name: hello-world.war


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - wildfly-install

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
