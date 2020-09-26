# DBA

#### Setup

`git clone git@github.com:gwmoura/dba.git`
`git submodule init`
`git submodule update`

#### Iniciando

`docker-compose up -d`
`docker-compose exec mysql /bin/bash`

* Importando a base emplyees
    * `cd test_db/`
    * `mysql -u root -proot < employees.sql`
* Importando a base sakila
    * `cd test_db/sakila`
    * `mysql -u root -proot < sakila-mv-schema.sql`
    * `mysql -u root -proot < sakila-mv-data.sql`
