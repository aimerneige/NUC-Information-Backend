本仓库为 [中北信息](https://github.com/Dreace/NUC-Information) 小程序的后端，使用 Python 编写。
# 安装依赖
```
pip install -r requirements.txt
```
# 启动服务端
```
python index.py
```
# 状态码（全局使用）
| 值 | 状态 |
|----|-----|
|0|正常|
|-1|服务器错误|
|-2|认证失败|
|-3|登录失败|
|-4|暂停服务|
|-5|访问过快|
|-6|查询失败|
|-7|查询失败|
# 状态码（组件特定）
| 值 | 状态 | 组件 |
|----|-----|-----|
|1|登陆失败（可能是验证码错误）|体测
