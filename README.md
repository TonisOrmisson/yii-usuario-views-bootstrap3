# yii-usuario-views-bootstrap3
Bootstrap 3 views for yii2-usuario module


Copied from original usuario views (https://github.com/2amigos/yii2-usuario)

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

run:

```composer require --prefer-dist yii-usuario/yii-usuario-views-bootstrap3```

## Usage

In your user module config set the viewPath to the views folder of this package.

```
'user' => [
    'class' => \Da\User\Module::class,
        'viewPath' => '@vendor/yii-usuario/yii-usuario-views-bootstrap3/src/views',
]
```

