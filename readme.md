#　第一次使用專案
1.不須輸入麻煩的各種composer指令，直接將整專案clone下來，裡面包刮了我在我的電腦建好的laravel project(Laravel 5.3)

2.有關於.env檔的設定:

將.env.example 改成 .env
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=homestead <-改成你的database名
DB_USERNAME=homestead <-改成你的phpMyAdmin帳號(如果是用phpMyAdmin話)
DB_PASSWORD=secret <-改成你的phpMyAdmin密碼
```

# Git 的使用:

1. 第一次使用時，先從專案clone下來
    * ```git clone https://github.com/superTO/Translator.git```
2. 每次git順序
    1. 先用cd切換到專案根目錄
    2. ```git pull```(將檔案全部抓下來到自己電腦中，避免下次git更新時出錯)
    3. ```git add .```(記得要有空白在"add" 和 "."之間)(偵測全部專案有被更動到的地方)
    4. ```git commit -m "your commit message"```(commit這次更動，並註解)
    5. ```git push"```(push這次的更動到github上)
    6. github會由第一次clone下來時所提供的git路徑去將本機的檔案自動上傳到對應的repo上
# Laravel PHP Framework

[![Build Status](https://travis-ci.org/laravel/framework.svg)](https://travis-ci.org/laravel/framework)
[![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Stable Version](https://poser.pugx.org/laravel/framework/v/stable.svg)](https://packagist.org/packages/laravel/framework)
[![Latest Unstable Version](https://poser.pugx.org/laravel/framework/v/unstable.svg)](https://packagist.org/packages/laravel/framework)
[![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

Gary is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as authentication, routing, sessions, queueing, and caching.

Laravel is accessible, yet powerful, providing tools needed for large, robust applications. A superb inversion of control container, expressive migration system, and tightly integrated unit testing support give you the tools you need to build any application with which you are tasked.

## Official Documentation

Documentation for the framework can be found on the [Laravel website](http://laravel.com/docs).

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](http://laravel.com/docs/contributions).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell at taylor@laravel.com. All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
