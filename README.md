# ddlt

## 容器中需要的环境变量
### ddl-postgre
| 名称 | 描述 | 必须 | 默认值 |
| --- | --- | --- | --- |
| POSTGRES_DB | 数据库名称 | False | ddl_database |
| POSTGRES_USER | 数据库用户 | False | ddl_username |
| POSTGRES_PASSWORD | 数据库密码 | False | ddl_password |

### ddl-redis
| 名称 | 描述 | 必须 | 默认值 |
| --- | --- | --- | --- |

### ddl-backend
| 名称 | 描述 | 必须 | 默认值 |
| --- | --- | --- | --- |
| POSTGRES_HOST | Postgres服务器地址 | False | 127.0.0.1 |
| POSTGRES_DB | 数据库名称 | False | ddl_database |
| POSTGRES_USER | 数据库用户 | False | ddl_username |
| POSTGRES_PASSWORD | 数据库密码 | False | ddl_password |
| REDIS_HOST | Redis服务器地址 | False | 127.0.0.1 |
### ddl-celery
| 名称 | 描述 | 必须 | 默认值 |
| --- | --- | --- | --- |
| POSTGRES_HOST | Postgres服务器地址 | False | 127.0.0.1 |
| POSTGRES_DB | 数据库名称 | False | ddl_database |
| POSTGRES_USER | 数据库用户 | False | ddl_username |
| POSTGRES_PASSWORD | 数据库密码 | False | ddl_password |
| REDIS_HOST | Redis服务器地址 | False | 127.0.0.1 |
| DEBUG | 打印运行中的日志 | False |  |


### ddl-web
| 名称 | 描述 | 必须 | 默认值 |
| --- | --- | --- | --- |
| BACKEND_HOST | 后台的服务器IP | True | ddl-backend |
| BACKEND_PORT | 后台服务器的端口 | True | 8000 |
