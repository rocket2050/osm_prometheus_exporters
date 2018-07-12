# osm_prometheus_exporters

osm_prometheus_exporters contains exporter roles for:
- Node
- Apache
- Mysql
- MongoDB
- Nginx



Role Name
=========

A brief description of the role goes here.

Requirements
------------
None

Role Variables
--------------

Available variables are listed below, along with default values(see defaults/mail.yml):

# vars file for prometheus_exporter

exporter_name: "node"

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: "{{ host }}"
      roles:
         - { role: osm_prometheus_exporters }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).

