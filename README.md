Install with composer

```
composer require xverify/xverify-client-api:"dev-master"
```

Usage in your project

```php
use xverify\XverifyClientAPI;

$client = new XverifyClientAPI;

$data = array();
$email = 'test@test.com';
$data['email'] = $email;
$client->verify('email', $data);
```
