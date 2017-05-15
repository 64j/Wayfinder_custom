# Wayfinder_custom
Изменённый Wayfinder

При использовании TV параметров добавляет всего один запрос в БД

Добавлена шаблонизация по уровням

```code
[!Wayfinder_custom?
&startId=`0`
&rowTpl=`wf.rowTpl`
&rowTpl2=`wf.rowTpl2`
!]
```

### Установка
Добавить оба файла в папку assets/snippets/wayfinder/

Создать сниппет Wayfinder_custom
с кодом
```php
<?php
return require MODX_BASE_PATH.'assets/snippets/wayfinder/snippet.wayfinder_custom.php';
```

Все остальные параметры аналогичны как и в оригинальном Wayfinder
