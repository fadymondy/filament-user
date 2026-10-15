![Screenshot of Login](./art/screenshot.png)

# Filament User Resource

User Resource For Filament Admin

## Installation

Before install looking for this packages and install it

- [filament-shield](https://github.com/bezhansalleh/filament-shield)

You can install the package via composer:

```bash
composer require 3x1io/filament-user
```

Publish Translation and config

```bash
php artisan vendor:publish --tag="filament-user-config"
php artisan vendor:publish --tag="filament-user-translations"
```

and now clear cache

```bash
php artisan optimize:clear
```

## Publish Resource

you can publish the resource to your project

```bash
php artisan filament-user:publish
```

it will publish the resource to your project

than go to `filament-user.php` config file and change the `publish_resource` to `true`


## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Credits

- [Fady Mondy](https://github.com/3x1io)

## Follow the build

Built in public by **[Fady Mondy](https://github.com/fadymondy)** (فادي مندي): open source, AI agents & MCP, Laravel and Go.
Release notes, deep-dives and behind-the-scenes go out here first:

[![Follow on X](https://img.shields.io/badge/X-@fadymondy-0B1429?style=flat-square&logo=x&logoColor=E2661C)](https://x.com/fadymondy)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Fady%20Mondy-0B1429?style=flat-square&logo=linkedin&logoColor=E2661C)](https://www.linkedin.com/in/fadymondy/)
[![YouTube](https://img.shields.io/badge/YouTube-@FadyMondy-0B1429?style=flat-square&logo=youtube&logoColor=E2661C)](https://www.youtube.com/@FadyMondy?sub_confirmation=1)
[![Bluesky](https://img.shields.io/badge/Bluesky-fadymondy-0B1429?style=flat-square&logo=bluesky&logoColor=E2661C)](https://bsky.app/profile/fadymondy.bsky.social)
[![Threads](https://img.shields.io/badge/Threads-@engfadymondy-0B1429?style=flat-square&logo=threads&logoColor=E2661C)](https://www.threads.com/@engfadymondy)
[![GitHub followers](https://img.shields.io/github/followers/fadymondy?label=Follow&style=flat-square&logo=github&color=0B1429&logoColor=E2661C)](https://github.com/fadymondy)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
