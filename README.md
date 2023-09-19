# Moka - PrestaShop Payment Gateway

![image](https://optimisthub.com/cdn/moka/moka-prestashop-plugin.jpg)

## Requirements

PHP 8 and later.

## Supported Version 

1.8.x

## Dependencies

The bindings require the following extensions in order to work properly:

-   [`curl`](https://secure.php.net/manual/en/book.curl.php)
-   [`json`](https://secure.php.net/manual/en/book.json.php)

## Cookie SameSite

Advanced Parameters -> Administration -> Cookie SameSite = None

## SSL / TLS

PCI-DSS rules only allow the use of TLS 1.2 and above protocols. Please ensure that your application POST to Moka URL over these protocols. Otherwise, errors such as 'Connection will be closed or Connection Closed' will be received.

## Test Cards

See the [Test Cards](https://developer.moka.com/home.php?page=test-kartlari).