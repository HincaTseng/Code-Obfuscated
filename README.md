**步骤如下：**

1. 终端 在xcodeproj 创建 `funny.list`和`class.sh` 。
2. 在下级工程文件夹 创建`class.h`。
3. 在TARGETS->Build Phases->左上角添加 Run Script。。。`$PROJECT_DIR/class.sh`
4. 添加需要替换的函数名称到`funny.list`。