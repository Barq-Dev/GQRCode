# GQRCode
Generate Google QR Code Image

### Instalation
```
composer require barq-dev/gqrcode
```

### Usage
```php
$qr = new QRCode();
$text = "https://barqun.com";
$qr->text($text)->qrCode(350, "storage/QR-Image.png");
```
