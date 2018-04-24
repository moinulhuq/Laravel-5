#To list the process of mac

```
>sudo lsof -nPi -sTCP:LISTEN
```

#TO run laravel on diufferent port

```
>php artisan serve --port=8989

```

#To solve "Failed to listen on 127.0.0.1:8000 (reason: Address already in use)"

```
>ps -ef | grep php

output
------

501  1811  1807   0  9:07am ttys000    0:00.41 /Applications/MAMP/bin/php/php7.1.6/bin/php -S 127.0.0.1:8000 /Users/moinulhuq/Sites/redcrow/server.php

>kill 1811
```

