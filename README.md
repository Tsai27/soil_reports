<!--
 * @Author: Mr.Car
 * @Date: 2024-01-24 10:31:16
-->

## 创建环境
conda env export > environment.yaml

## 恢复环境
conda env create -f environment.yaml

## 整体打包
pyinstaller -c -D --icon=icon.ico reports.py --add-data=config:./config --add-data=C:\Users\Lenovo\.conda\envs\soilCli\Lib\site-packages\grapheme:grapheme
注意 pyinstaller 的更新