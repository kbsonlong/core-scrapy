## 1、修改数据库配置
settings.py

    DATABASE = {'drivername': 'mysql',
                'host': 'www.along.party',
                'port': '3306',
                'username': 'root',
                'password': '*********',
                'database': 'spider_tools',
                'query': {'charset': 'utf8'}}


## 2、初始化数据库

    python init_db.py