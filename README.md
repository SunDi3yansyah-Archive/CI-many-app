# CodeIgniter Many App CI 2

This repository many application for one system.

## Structure Directory

```
.
├── primary.com
│   └── application
│       ├── cache
│       ├── config
│       ├── controllers
│       ├── core
│       ├── helpers
│       ├── hooks
│       ├── language
│       │   └── english
│       ├── libraries
│       ├── logs
│       ├── models
│       ├── third_party
│       └── views
│           └── errors
│               ├── cli
│               └── html
├── sub.primary.com
│   └── application
│       ├── cache
│       ├── config
│       ├── controllers
│       ├── core
│       ├── helpers
│       ├── hooks
│       ├── language
│       │   └── english
│       ├── libraries
│       ├── logs
│       ├── models
│       ├── third_party
│       └── views
│           └── errors
│               ├── cli
│               └── html
└── system
    ├── core
    │   └── compat
    ├── database
    │   └── drivers
    │       ├── cubrid
    │       ├── ibase
    │       ├── mssql
    │       ├── mysql
    │       ├── mysqli
    │       ├── oci8
    │       ├── odbc
    │       ├── pdo
    │       │   └── subdrivers
    │       ├── postgre
    │       ├── sqlite
    │       ├── sqlite3
    │       └── sqlsrv
    ├── fonts
    ├── helpers
    ├── language
    │   └── english
    └── libraries
        ├── Cache
        │   └── drivers
        ├── Javascript
        └── Session
            └── drivers
```

## Outline

**index.php**
``` php
$system_path = '../system';
```

## License
[![MIT License](https://img.shields.io/dub/l/vibe-d.svg)](LICENSE)