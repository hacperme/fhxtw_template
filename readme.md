## Flask + Htmlx + Tailwind CSS 程序模板

使用 Flask Htmlx 和 Tailwind CSS 搭建一个简单的 web 全栈开发环境。

## 使用步骤

创建虚拟环境

```bash
py -3 -m venv venv
source venv/bin/activate # or
.\venv\Scripts\Activate.ps1
```

安装依赖包

```bash
pip install -r requirements.txt
```

初始化 tailwindcss

```bash
tailwindcss
```

使用 tailwindcss 生成 CSS

```bash
tailwindcss -i ./static/src/main.css -o ./static/dist/main.css --minify
```

运行

```bash
(venv)$ python app.py
```

