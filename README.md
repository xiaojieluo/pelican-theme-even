# pelican-theme-even
A super simple theme for Pelican

移植自 [hexo-theme-even](https://github.com/ahonn/hexo-theme-even)

## 使用方法：

1. 复制 `themeconfig.py.example` 到 pelican 根目录，并重命名为 `themeconfig.py`
2. 按需修改 `themeconfig.py` 中的设置
3. 打开 `pelicanconf.py` ， 在顶部加上如下代码：
```python
import os
import sys
sys.path.append(os.curdir)
import themeconfig as THEMECONFIG
```
4. 修改 `pelicanconf.py` 中的 `THEME` 变量， 启用主题