# CryptoTicker
Utilizes CryptoCompare's API  and notify-send to pull current spot pricing on Bitcoin, Litecoin, and Ethereal. 

# Compatibility
I wrote this very quickly for my Linux Mint 18.1 box, so I'd assume most other Ubuntu variants will work with it.


# Usage
The program can either be used as a stand-alone PHP script, or you can use the included binary file in the /bin folder.

php ticker.php [interval time in seconds]
php ticker.php 60

Alternatively,

chmod +x bin/ticker
./ticker 60

It can also be set to run as a startup program via method of your choosing.
