# AliExpress PHP SDK

This is a PHP SDK for AliExpress, adapted from the original SDK to be Composer-friendly. It allows developers to easily integrate with AliExpress services and APIs using PHP.

## Features

- Composer compatibility for easy installation and autoloading (PSR-4).
- Provides a simple interface to interact with AliExpress APIs.
- Log management and request handling built-in.

## Installation

You can install the SDK via Composer. Simply add the repository to your `composer.json` file and require the package:

```bash
composer require lpcs007/ae_php_sdk
```

## Usage

Once installed, you can use the SDK to interact with AliExpress services as follows:

```php
use AliExpress\Sdk\IopClient;

$client = new IopClient($url, $appKey, $secretKey);
// Now you can use $client to make API requests.
```

For more detailed examples, refer to the `demo` directory included in this repository.

## Documentation

This SDK was adapted from the original AliExpress SDK. You can find the full documentation for the AliExpress API at:

[AliExpress API Documentation](https://openservice.aliexpress.com/doc/doc.htm)

Please refer to the official documentation for more details on the available methods, endpoints, and authentication requirements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to submit issues or pull requests if you have any suggestions or improvements.
