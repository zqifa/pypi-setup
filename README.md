my-package

pypi 上传python包

打包源代码的包:
python setup.py sdist build

使用twine上传,先安装twine
twine upload dist/*
