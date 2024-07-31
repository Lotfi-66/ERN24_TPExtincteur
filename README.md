-----Docker-----

docker compose up -d

docker exec -it phpgrp composer install

docker exec -it nodegrp yarn

docker exec -it nodegrp yarn encore dev --watch

docker exec -it phpgrp php bin/console make:migration

