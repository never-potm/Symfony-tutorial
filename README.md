Symfony Standard Edition
========================

### How to generate entity ?
php .\bin\console doctrine:generate:entity

### How to generate controller ?
php .\bin\console generate:controller

### How to seed data in Symfony ?
[RUN] composer require doctrine/doctrine-fixtures-bundle
[RUN] php .\bin\console doctrine:fixtures:load
[RUN] php .\bin\console doctrine:schema:update

### How to update databasae ?
[RUN] php .\bin\console doctrine:schema:update --force



