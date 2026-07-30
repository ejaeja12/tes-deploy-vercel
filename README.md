# Deploy laravel + react + inertia to Vercel

## set :

- ikuti vercel.json
- buat perintah vercel di composer.json
- buat api/lambda.php tarok di root, lambda.php isinya sama dengan index.php
- buat .vercelignore

## DB menggunakan neon

note : matikan centang non pooling pada neon connection

## Set ENV Variable

APP_ENV={production | dev}
<br>APP_DEBUG={true | false}
<br>APP_KEY={appkey}

<br>DB_CONNECTION=pgsql
<br>DB_HOST={hostname}
<br>DB_PORT=5432
<br>DB_DATABASE={db}
<br>DB_USERNAME={user_db}
<br>DB_PASSWORD=endpoint={endpoint_id};{db_password}
<br>DB_SSLMODE=require

## Note

Kalau gagal atau error, jangan pilih opsi redeploy tapi create deployment di dashboard vercel > deployment > carilah opsinya
