# Template generator for HotSpot Voucher Generator

This repository contains a template generator for **HotSpot Voucher Generator**. 
More details about the generator can be found at [hotspot-tools.duma.sh](https://hotspot-tools.duma.sh/hotspot-voucher-generator).

Here you will find following template files:

- `sunmi.php` - template for 58mm ESC/POS thermal printers, compatible with Sunmi devices
- `sunmi_label.php` - label template for Sunmi V2 Pro devices with label printing capability
- `webprint.php` - template for 80mm ESC/POS thermal printers

## How to use

1. Install composer dependencies: `composer install`
2. Modify the template file to your needs
3. Execute the generator: `php sunmi.php > template.txt` or  `php sunmi_label.php > template.txt` or  `php webprint.php > template.txt`
4. Copy content of generated template file (`template.txt`) to your HotSpot Voucher Generator configuration
