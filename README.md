## source located in 
/Users/zeenlong/.espressif/v6.0/esp-idf

## how to use
- open a new terminal
```bash
esp_idf

## how to exit
`ctl + ]`
idf.py create-project --path <project name> #创建新工程
idf.py set-target esp32s3 # 设置目标芯片
idf.py create-component <component name> # 创建新组件
idf.py build # 编译工程
idf.py monitor # 监控项目工程
idf.py menuconfig # 配置项目
idf.py -p COMx flash # 下载程序，x是端口号
idf.py fullclean; idf.py clean # 清除编译文件

```
## 创建新的组件
在 atk-test 文件夹下创建 LED 组件
