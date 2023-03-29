# GQRCode
Generate Google QR Code Image

### Instalation
```
composer require barq-dev/gqrcode
```

### Usage
```php
$qr = new QRCode();
$qr->text($qrtext)->qrCode(350, "storage/QR-Image.png");
```
