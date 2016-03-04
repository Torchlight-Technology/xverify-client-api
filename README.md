Install with composer

```
composer require xverify/xverify-client-api:"~1.0"
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
