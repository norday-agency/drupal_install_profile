# IN10 - Drupal install profile

Default IN10 install profile for Drupal projects 

## Installation

Add a repository to your composer.json

```bash
"repositories": [
    {
        "type": "vcs",
        "url": "git@github.com:IN10/drupal_install_profile"
    }
]
```

###Get it with composer

For a Headless Drupal installation:

```bash
composer require "in10/drupal_install_profile: 2.*"
```

For a Drupal only installation:

```bash
composer require "in10/drupal_install_profile: 1.*"
```
