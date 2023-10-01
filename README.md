# Não utilizei o dominio xpto.local visto que o mesmo não é valido, penso que tem algum bloqueio porque '.local é um dominio reservado. 

# Up and running
docker compose -p mailu up -d

# Admin user settings
INITIAL_ADMIN_ACCOUNT=admin
INITIAL_ADMIN_DOMAIN=xpto.net
INITIAL_ADMIN_PW=admin
INITIAL_ADMIN_MODE=ifmissing

# Credentials for Mailu to access the admin panel
User: admin@xpto.net
Password: password