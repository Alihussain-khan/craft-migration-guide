# craft-migration-guide

- step one check plugins (check if they are still supported for the newer versions
- fix all the depreciated syntax
- composer require craftcms/cms:^4.15.0 --update-with-dependencies
- php craft migrate/all
- php craft project-config/apply

  

# updating the db
- docker compose exec database bash -lc "mariadb-upgrade -uroot -p${MARIADB_ROOT_PASSWORD} --verbose --force"
