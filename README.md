```php
<?php

use Illuminate\Support\Facades\Route;

Route::get('/', function () {
    return [
        'country' => 'Netherlands',
        'working_on' => ['glasshosting'],
        'learning' => ['Javascript','Node.js','Java', 'PHP', 'Laravel'],
        'tools' => ['MySQL', 'Nginx', 'Docker'],
        'discord' => [
            'tag' => 'finniedj.exe#9075',
            'server' => null,
        ],
    ];
});
```
