# Guacamole Ldap Totp

### Copiar repositorio GIT
```bash
git clone "https://github.com/Lurefox/guacamole_ldap_totp.git"
```

```bash
cd guacamole-docker-compose
```

---

### Ejecutar script de inicialización para la base de datos PostgreSQL 
```bash
./prepare.sh
```

---

### .ENV
```.env
POSTGRESQL_PASSWORD=password_sql
POSTGRES_PASSWORD=password_postgres
LDAP_SEARCH_BIND_PASSWORD=Password_user_ad
LDAP_HOSTNAME=hostname_server
```


### Ejecutar el compose
```bash
docker compose up -d
```

---

### Ingresar por navegador
```
<IP>:8080/guacamole
```

---

### Este repositorio esta basado de 

https://github.com/boschkundendienst/guacamole-docker-compose