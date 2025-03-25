# ss-ana
 桑尾草原语录系统

### Install

`pip install -r requirements.txt`

or

`poetry install`

- If you use Python 3.8 or lower, located in Chinese Mainland, you can use

`mv pyproject.toml pyproject.toml.bak && cp pyproject_38_cn.toml pyproject.toml && poetry install`

- If you are using Python 3.8 or lower, you can use

`mv pyproject.toml pyproject.toml.bak && cp pyproject_38.toml pyproject.toml && poetry install`

### Run

- `python/python3 main.py`

### Usage

```
http://127.0.0.1:7777 # 主页

or

http://127.0.0.1:7777/ana/{json文件名}/json # 只返回json数据
```