myextension
===========
myextension

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist oland-studio/yii2-myextension "*"
```

or add

```
"oland-studio/yii2-myextension": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \myextension\test\AutoloadExample::widget(); ?>```