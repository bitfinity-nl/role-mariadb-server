# role-mariadb-server
MariaDB Server is the leading open source database.


Example Playbook
----------------

    - hosts: mariadb_servers
      become: true

      vars:
        # -- MariaDB server: override (default settings) --
        mariadb_administrative_password : '{{ def_mysql_pass }}'
      
      roles:
         - role-mariadb-server

License
-------

GPLv3

Author Information
------------------

E: support@bitfinity.nl

I: https://www.bitfinity.nl
