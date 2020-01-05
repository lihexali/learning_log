## create env
cd learning_log

python -m venv ll_env

source ll_env/bin/activate

pip install Django pylint yapf pylint_django

python manage.py runserver

## install pluins for vscode

    接下来便是安装真正协助我们开发的插件：
    Python：Python 语法的基本插件
    Django：Django 的插件，用于模板中语法提示和补全，注意不是搜索出来的第一个，而是后面有个 1.0 版本的
    XML Tools：整个 VSCode 都会用到的插件，运维配置 VSCode 需要
    Beautify：前端美化
    View In Browser：浏览器快捷打开前端页面
    HTML CSS Support：HTML 基础插件
    Path Intellisense：路径补全插件

## superuser

ll_admin   hxxz

