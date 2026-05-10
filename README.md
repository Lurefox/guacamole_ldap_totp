# Guacamole Ldap Totp

### Copiar repositorio GIT
```bash
git clone "https://github.com/Lurefox/guacamole_ldap_totp.git"
```

```bash
cd guacamole_ldap_totp
```

---

### Ejecutar script de inicialización para la base de datos PostgreSQL 
```bash
chmod +x prepare.sh && ./prepare.sh
```

---

### Crear archivo ENV
```
touch .env && nano .env
```

### .ENV
```.env
POSTGRES_PASSWORD=password_sql
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

### Iniciar sesión con:
```
User: guacadmin
Pass: guacadmin

```

### Este repositorio esta basado de 

https://github.com/boschkundendienst/guacamole-docker-compose