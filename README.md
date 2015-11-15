# CodeIgniter Many App

This repository many application for one system.

## Structure Directory

```
CI-many-app
├── primary.com
│   └── application
│       ├── cache
│       ├── config
│       ├── controllers
│       ├── core
│       ├── errors
│       ├── helpers
│       ├── hooks
│       ├── language
│       │   └── english
│       ├── libraries
│       ├── logs
│       ├── models
│       ├── third_party
│       └── views
├── sub.primary.com
│   └── application
│       ├── cache
│       ├── config
│       ├── controllers
│       ├── core
│       ├── errors
│       ├── helpers
│       ├── hooks
│       ├── language
│       │   └── english
│       ├── libraries
│       ├── logs
│       ├── models
│       ├── third_party
│       └── views
└── system
    ├── core
    ├── database
    │   └── drivers
    │       ├── cubrid
    │       ├── mssql
    │       ├── mysql
    │       ├── mysqli
    │       ├── oci8
    │       ├── odbc
    │       ├── pdo
    │       ├── postgre
    │       ├── sqlite
    │       └── sqlsrv
    ├── fonts
    ├── helpers
    ├── language
    │   └── english
    └── libraries
        ├── Cache
        │   └── drivers
        └── javascript
```

## Outline

**index.php**
``` php
$system_path = '../system';
```

## License
[![MIT License](https://img.shields.io/dub/l/vibe-d.svg)](LICENSE)