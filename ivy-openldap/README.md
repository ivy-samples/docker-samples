# ivy-openldap

Setup of an Axon Ivy Engine with an external security system (OpenLdap).

The application with the name `ldap` is configured to use the external security system called `OpenLdap`. 

Open the __AdminUI__, navigate to the application `ldap` and synchronize the users that are defined in the OpenLdap server.

You can browse the LDAP tree with the phpldapadmin tool: http://localhost:8090/

* User: `cn=admin,dc=example,dc=org`
* Password: `admin`
