# craft-migration-guide

- step one check plugins (check if they are still supported for the newer versions
- fix all the depreciated syntax
- composer require craftcms/cms:^4.15.0 --update-with-dependencies
- composer install
- php craft migrate/all
- php craft project-config/apply

  
