# Pagination
一个PHP的分页组件

安装
```
composer require chaodada/page:dev-master
```

使用
```
include "./vendor/autoload.php";

use PageName\Page;

$page = new Page('50', 25);
var_dump($page);
```
