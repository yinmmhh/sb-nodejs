# singbox-nodejs
直接git运行即可，无需修改任何东西

单端口模式：启用 HY2 + HTTP(订阅) + Argo  可以手动选择tuic
多端口模式：TUIC + HTTP(订阅) + Argo + HY2 + REALITY

订阅链接： http://IP:PORT/sub

如果系统无法自动获取到可用端口，则需自己手动新建 ${FILE_PATH}/ports.txt 文件，一行一个端口号
