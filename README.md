<p align="center"><a href="https://typerocket.com" target="_blank"><img src="https://raw.githubusercontent.com/TypeRocket/art/main/wordmark/typerocket.svg" width="320"></a></p>

<p align="center">
<a href="https://packagist.org/packages/typerocket/core"><img src="https://img.shields.io/packagist/dt/typerocket/core" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/typerocket/core"><img src="https://img.shields.io/packagist/v/typerocket/core" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/typerocket/core"><img src="https://img.shields.io/packagist/l/typerocket/core" alt="License"></a>
</p>

## TypeRocket

### Installation

```shell
git clone https://github.com/laragis/typerocket.git -b pro typerocket-pro
cd typerocket-pro
composer config repositories.professional '{"type": "composer","url": "https://satis.typerocket.com","only": ["typerocket/professional"]}'
composer require typerocket/professional
php galaxy extension:publish typerocket/professional
php galaxy root:install {database} {db_username} {db_password}
```
