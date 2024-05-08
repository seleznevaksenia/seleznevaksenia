# Hello there 👋

![visitors](https://visitor-badge.laobi.icu/badge?page_id=seleznevaksenia.780167062)

```PHP
<?php

class SoftwareEngineer
{

    public $name = "Ksenia Selezneva";
    public $role = "Software Engineer";
    public $language_spoken = ["uk_UA", "en_US", "ru_RU", "ro_RO"];

    public function __construct(
        public string $name = null,
        public string $role = null
    )
    {
        $this->name = $name ?: $this->name;
        $this->role = $role ?: $this->role;
    }

    public function sayHi(): void
    {
        echo "I'm Ksenia Selezneva a Software Engineer with more than 7 years of experience.\n";
    }
}

$me = new SoftwareEngineer();
$me->sayHi();
```

## 🔧 Technologies & Tools

**Programming Languages:**

[![PHP](https://img.shields.io/badge/PHP-8.3-brightgreen.svg?logo=php&logoColor=white)](https://www.php.net/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-blue.svg?style=flat&logo=javascript&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
![Java](https://img.shields.io/badge/Code-Java-informational?style=flat&logo=java&logoColor=white&color=6aa6f8)

**Frameworks, Platforms and Libraries:**

![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white)
![Symfony](https://img.shields.io/badge/symfony-%23000000.svg?style=for-the-badge&logo=symfony&logoColor=white)
![Vue.js](https://img.shields.io/badge/vuejs-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)

**Tools and Services:**

![Docker](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=6aa6f8)

**Databases:**

![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
