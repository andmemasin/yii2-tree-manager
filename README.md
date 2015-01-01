yii2-tree
=========

An extended tree widget for Yii Framework 2.

## Demo
### _Extension is under development_

## Installation

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

> NOTE: Check the [composer.json](https://github.com/kartik-v/yii2-tree/blob/master/composer.json) for this extension's requirements and dependencies. Read this [web tip /wiki](http://webtips.krajee.com/setting-composer-minimum-stability-application/) on setting the `minimum-stability` settings for your application's composer.json.

Either run

```
$ php composer.phar require kartik-v/yii2-tree "dev-master"
```

or add

```
"kartik-v/yii2-tree": "dev-master"
```

to the ```require``` section of your `composer.json` file.

## Usage

### TreeView

```php
use kartik\tree\TreeView;

echo TreeView::widget([
    // options
]);
```

## License

**yii2-tree** is released under the BSD 3-Clause License. See the bundled `LICENSE.md` for details.