# CyberArk-Like-Company-Environment




docker run --rm guacamole/guacamole \
/opt/guacamole/bin/initdb.sh --mysql > initdb.sql



docker exec -i guac-sql mysql \
-u root \
-pStrongPassword123! \
guacamole_db < initdb.sql