# Composer Repository
_Powered by [satis](https://github.com/composer/satis)_

Website served from `gh-pages` branch

Files published to https://buckhamduffy.github.io/composer/

- Used for a composer-compatible package repository for internal packages
- Automatically kept up-to-date by GitHub action workflows across multiple repositories

## Usage
https://getcomposer.org/doc/05-repositories.md#hosting-your-own

Add `repositories` property to your `composer.json` 
```json
{
  "repositories": [
    {
      "type": "composer",
      "url": "https://buckhamduffy.github.io/composer/"
    },
    {
      "type": "composer",
      "url": "https://packagist.org"
    }
  ]
}
```
Both repositories must be included.
