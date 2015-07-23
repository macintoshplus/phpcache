# phpcache

[![Build Status](https://travis-ci.org/Mactronique/phpcache.svg?branch=master)](https://travis-ci.org/Mactronique/phpcache)

## Supported driver

- xCache
- WinCache
- Predis
- Redis
- Memcached
- Null (special for instanciate no effect cache driver)

## Install 

```
php composer.phar require mactronique/phpcache "~1.0"
```

## Configuration

### for xCache

No configuration need.



### for WinCache

No configuration need.



### for Null

No configuration need.

### For Predis

```
$config = array(
	"host" => "127.0.0.1",
	"port" => "",
	"password" => "",
	"database" => "",
	"timeout" => 1,
	"read_write_timeout" => 1
);
```

Only 'host' key is required.

## For Redis

```
$config = array(
	"host" => "127.0.0.1",
	"port" => "",
	"password" => "",
	"database" => "",
	"timeout" => 1
);
```

Only 'host' key is required.
