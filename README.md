# Inspire
Just an example of creating a package

A complete working example from the https://adevait.com/laravel/how-to-create-a-custom-package-for-laravel tutorial.


## Installation

Include repository in composer.json

``` 
"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/heartlandtechie/inspire"
        }
    ],
```

Now install via composer

`composer require heartlandtechie/inspire 1.0.1`

Include in the package service providers in config/app.php of your application:

`Heartlandtechie\Inspire\Providers\InspirationProvider::class,`

Calling from your application:

`https://yourapplication/inspire`


        
        
