# Magento Deleter
Delete unused product such as disabled products, products without image etc.

# Usage
 You can simply run next command which delete all disabled product, product without images and permanent rewrites from `core_url_rewrites`
 
`php shell/deleter.php --delete all`
 
 Also you can run all command separately

```
php shell/deleter.php --delete disabled
php shell/deleter.php --delete noImage
php shell/deleter.php --delete rewritePermanent
php shell/deleter.php --delete rewrite
```
