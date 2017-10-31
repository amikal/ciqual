#CIQUALAPI

##HowTo install project back project ?

git clone https://github.com/amikal/ciqual.git

```bash
cd ciqual
cd back
```

Back has been made with apiplatform

```bash
composer install
mysql -u root -p ciqual < sql/ciqual_indexed_003.sql
sudo chmod -R 777 var/cache var/logs var/sessions
php bin/console server:run
```
Goto http://127.0.0.1:8000


##HowTo install project front project ?

Front has been made with React.js

```bash
cd front
yarn (or npm) install
yarn (or npm) start
```
Goto http://localhost:3000