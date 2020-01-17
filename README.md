## Instructions

- clone the repo

- install dependency
    ```
    composer install
    ```

- create database

- create `.env`, copy the value of `.env.example`
    ```dotenv
    # The environment Craft is currently running in ('dev', 'staging', 'production', etc.)
    ENVIRONMENT="dev"
    
    # The secure key Craft will use for hashing and encrypting data
    SECURITY_KEY="Z2Yv2yb6lRpFIfNRud4fwUcoKjcT_8XO"
    
    # The database config ('mysql' or 'pgsql')
    DB_DRIVER="mysql"
    DB_SERVER="localhost"
    DB_USER="root"
    DB_PASSWORD=""
    DB_DATABASE=""
    DB_SCHEMA="public"
    DB_TABLE_PREFIX="ja_"
    DB_PORT="3306"
  
    DEFAULT_SITE_URL="http://jquery-alternative-demo.test"
    ```
  
- adjust the value of `DB_USER`, `DB_PASSWORD`, `DB_DATABASE`

- restart your Laragon/LAMP server

- setup craft cms, select one of the options below to start the installation process :
    - by GUI : open http://jquery-alternative-demo.test/admin/install
    - by CLI : run `./craft setup` 
    
- 