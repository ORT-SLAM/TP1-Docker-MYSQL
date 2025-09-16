# TP Docker MYSQL

Démarrer les conteneurs

```bash
docker compose up -d
```

Se connecter au conteneur docker

```bash
docker exec -it tp_mysql bash
```

Se connecter au user avec le mdp

```bash
mysql -u user -p
```

Rentrer dans la db
```sql
use tp_db;
```