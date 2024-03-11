软件用于自动化推特农场
我的Telegram频道（关注更新）- https://t.me/easypeoff

安装
方法1：

创建虚拟环境
```bash
python -m venv venv
```
激活虚拟环境（每次运行软件前都需要做这一步）
Windows用户：
```bash
venv/Scripts\activate
```
Mac和Linux用户：
```bash
source venv/Scripts/activate
```
安装依赖
```bash
pip install -r requirements.txt
```
方法2：

安装poetry https://python-poetry.org/docs/

激活虚拟环境（每次运行软件前都需要做这一步）

```bash
poetry shell
```
安装依赖
```bash
poetry install
```
配置
配置详细指南 - https://teletype.in/@easypeoff/twitter-automation

config.py - 主配置文件

modules_settings.py - 模块设置

在data/目录下可以找到所需文件的示例

data/accounts.txt - Twitter的认证token

data/proxies.txt - 代理

data/user_agents.txt - 浏览器标识符

启动
在激活的虚拟环境中（见安装）

```bash
python main.py
```
