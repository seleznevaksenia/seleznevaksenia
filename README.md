# Hello there 👋

![visitors](https://visitor-badge.laobi.icu/badge?page_id=zhenye-na.zhenye-na)

```PHP
<?php

class SoftwareEngineer {

  public $name = "Ksenia Selezneva";
  public $role = "Software Engineer";
  public $language_spoken = ["uk_UA", "en_US", "ru_RU", "ro_RO"];

 public function __construct(
      public string $name = null,
      public string $role = null
  ) {
    $this->name = $name ?: $this->name;
    $this->role = $role ?: $this->role;
  }

  public function sayHi(): void {
    echo "I'm Ksenia Selezneva a Software Engineer with more than 7 years of experience.\n";
}

$me = new SoftwareEngineer();
$me->sayHi();
```

## 🔧 Technologies & Tools

**Programming Languages:**

[![PHP](https://img.shields.io/badge/PHP-8.3-brightgreen.svg?logo=php&logoColor=white)](https://www.php.net/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-blue.svg?style=flat&logo=javascript&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
![Java](https://img.shields.io/badge/Code-Java-informational?style=flat&logo=java&logoColor=white&color=6aa6f8)

**Tools and Services:**

![Docker](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=6aa6f8)
