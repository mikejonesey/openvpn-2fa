Role Name
=========

Openvpn with 2fa via google-authenticator.

Role Variables
--------------

Host vars:

  Required:
  EASYRSA_REQ_ORG: Your organisation name for your certificates.
  EASYRSA_REQ_EMAIL: Your email address for your certificates.
  EASYRSA_REQ_OU: Your organisation unit name for your certificates.

  Not Required:
  two_fa: Google # If this var is set, google auth will be installed and setup, I may setup alertnat 2fa providers in ansible soon otherwise this could be bool.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - openvpn

License
-------

BSD

Author Information
------------------

Michael Jones, http://www.mikejonesey.co.uk/