# Instalation
1. clone repository
2. copy .env.original to .env
3. set ldap hostname in .env file `PHPLDAPADMIN_LDAP_HOST=ldap`
4. set web interface port in .env file `PHPLDAPADMIN_PORT=8080`
5. run docker compose up --build

# Maintenance
Thr container starts automatically on boot and restarts unless explicitly stopped
