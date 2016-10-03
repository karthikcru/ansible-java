Role Name
=========

The role simply install the version of Java that is mentioned and updated the systems Java version to the default version specified

Requirements
------------

Requirements
- minimum ansible verison - 1.9
- OS - Ubuntu

Role Variables
--------------

The version of Java that needs to be installed. Please update the version of Java here (works only for oracle Java for now)

Example:
java_versions:
  - oracle-java8-installer

The default version of Java that needs to be set in the machine

Example:
java_default_version: java-8-oracle

Dependencies
------------

None

Example Playbook
----------------

Updating soon

License
-------

gpl-v2

Author Information
------------------

http://github.com/karthikcru