
此仓库来自 [BasicSR](https://github.com/XPixelGroup/BasicSR)
---
❌ 安装 BasicSR 
```
uv pip install basicsr 
```



✅ 安装 BasicSR 
```
git clone https://github.com/classronin/BasicSR.git
cd BasicSR
uv pip install -r requirements.txt
uv run python setup.py develop
```

构建并打包为 .whl 文件
```
uv pip install build
uv build
uv pip install dist/basicsr-1.4.2-py3-none-any.whl
```


