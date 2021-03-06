![Nest-Starter](https://socialify.git.ci/Lmmmmmm-bb/Nest-Mysql/image?description=1&language=1&theme=Light)
<p align="center">
<a href="https://github.com/Lmmmmmm-bb/Nest-Mysql/blob/main/LICENSE"><img alt="GitHub license" src="https://img.shields.io/github/license/Lmmmmmm-bb/Nest-Mysql"></a>
<a href="http://commitizen.github.io/cz-cli/"><img alt="Commitizen friendly" src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg" /></a>
<a href="https://github.com/Lmmmmmm-bb/Nest-Mysql/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/Lmmmmmm-bb/Nest-Mysql"></a>
<a href="https://github.com/Lmmmmmm-bb/Nest-Starter/pulls"><img alt="GitHub PR" src="https://img.shields.io/badge/PR-Welcome-%2345A2FF" /></a>
</p>

## 分支

- **[main](https://github.com/Lmmmmmm-bb/Nest-Starter/tree/main) => NestJS + TypeOrm + Mysql + Swagger**
- [open-api](https://github.com/Lmmmmmm-bb/Nest-Starter/tree/open-api) => NestJS + Swagger

## 目录结构

```
├── LICENSE
├── README.md
├── commitlint.config.ts          // commitlint 配置文件
├── nest-cli.json
├── package.json
├── pnpm-lock.yaml
├── src
│   ├── app                       // 存放 App Module 相关文件的文件夹
│   ├── common
│   │   ├── decorators            // 存放装饰器的文件夹
│   │   ├── filters               // 存放过滤器的文件夹
│   │   ├── interceptors          // 存放拦截器的文件夹
│   │   ├── middleware            // 存放中间件的文件夹
│   │   └── pipes                 // 存放管道的文件夹
│   ├── configs                   // 用来存放各种依赖的配置文件
│   │   ├── swagger.config.ts     // Swagger 配置文件
│   │   └── typeorm.config.ts     // TypeOrm 配置文件
│   ├── constants                 // 存放常量的文件夹
│   ├── main.ts                   // 应用主入口
│   ├── modules                   // 存放各种 Module 的文件夹
│   └── utils                     // 存放工具文件的文件夹
├── tsconfig.build.json
└── tsconfig.json
```

## 相关配置

### 数据库

本地创建 `.env.local` 文件，并配置如下：
```
MYSQL_HOST=
MYSQL_USER=
MYSQL_PASSWORD=

MYSQL_PORT=
MYSQL_DATABASE=
```

### Swagger

配置 Swagger 页面信息请在 `/src/configs/swagger.config.ts` 中进行配置。
