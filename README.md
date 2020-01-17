## Instructions

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
    ```
  
- adjust the value of `DB_USER`, `DB_PASSWORD`, `DB_DATABASE`

- restart your Laragon/LAMP server

- setup craft cms, select one of the options below :
    - by GUI : open http://jquery-alternative-demo.test to start the craft installation
    - by CLI : run `./craft setup`