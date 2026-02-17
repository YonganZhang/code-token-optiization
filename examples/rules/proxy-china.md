# Proxy (Clash)

外网请求需设代理 `http://127.0.0.1:7890`：
- Bash: `export HTTPS_PROXY=http://127.0.0.1:7890 HTTP_PROXY=http://127.0.0.1:7890`
- Python: `os.environ['HTTPS_PROXY'] = os.environ['HTTP_PROXY'] = 'http://127.0.0.1:7890'`
- ConnectionRefused → 提醒用户开 Clash
