yii2-flipclock
==============
Wrapper of FlipClock for Yii2.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist spevv/yii2-flipclock "dev-master"
```

or add

```
"spevv/yii2-flipclock": "dev-master"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
use spevv\flipclock\FlipClock;

<?= FlipClock::widget([
    'selector' => '#clock', // ID for the future DIV
    'time' => 60, // Seconds
    'varName' => 'clock', // Name of variable for control FlipClock
    'options' => array(
        // options of FlipClock
    ),
]);
?>
```
