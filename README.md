# telegram-php-socks5
Very simple php-socks5 proxy server for using in Telegram.
Socks5 proxy written in PHP based on [workerman](https://github.com/walkor/Workerman). 

**This is adapted version of Workerman php-socks5 version that support telegram.**

## Install
1. ```git clone https://github.com/yuseferi/telegram-php-socks5```

2. ```composer install```

## Config
Edit file ```config.php``` if you want to override defaults.
The default port is  `1080`, `authentication` has been disabled` by default.

## Start
```php service.php start -d```

## Stop
```php service.php stop```

## Status
```php service.php status```