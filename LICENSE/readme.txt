# server.py
# 从wsgiref模块导入:
from wsgiref.simple_server import make_server
# 导入我们自己编写的application函数:
from hello import application

# 创建一个服务器，IP地址为空，端口是8000，处理函数是application:
httpd = make_server('', 8000, application)
print('Serving HTTP on port 8000...')
2019.10.18 update
2019.10.18 10:02
up 2019.10.18 10:05
up 2019.10.18 10:18
up 2019.10.18 10:29

