# Gradle 构建多模块Spring Boot项目
## 基本结构
```sh
.
├── build
├── build.gradle
├── creatgitkeep.sh
├── demo-common
│   ├── bin
│   ├── build
│   ├── build.gradle
│   └── src
│       ├── main
│       └── test
├── demo-data
│   ├── build.gradle
│   ├── build
│   ├── build.gradle
│   └── src
│       ├── main
│       └── test
├── demo-service
│   ├── build
│   ├── build.gradle
│   └── src
│       ├── main
│       └── test
├── demo-view
│   ├── build
│   ├── build.gradle
│   └── src
│       ├── main
│       └── test
├── README.md
└── settings.gradle
```

## gradle 说明
### settings.gradle
主要包含两个参数：
1. rootProject.name
    - 存储项目的名字
2. include 
    - 包含的字模块的目录名字
### build.gradle