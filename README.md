Bootstrap Date Time Picker
==========================
Bootstrap Datepicker and Timepicker in one extentions

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist moonlandsoft/bootui-datetimepicker "*"
```

or add

```
"moonlandsoft/bootui-datetimepicker": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?= \bootui\datetimepicker\Datepicker::widget(); ?>

<?= \bootui\datetimepicker\Timepicker::widget(); ?>

<?= \bootui\datetimepicker\DateTimepicker::widget(); ?>
```

or

```php
<?= $form->field($model, 'attribute')->widget(Datepicker::className()); ?>

<?= $form->field($model, 'attribute')->widget(Timepicker::className()); ?>

<?= $form->field($model, 'attribute')->widget(DateTimepicker::className()); ?>
```