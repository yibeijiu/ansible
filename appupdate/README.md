此ansible应用包含两个文件appupdate.yml和approllback.yml
appupdate.yml用于一般的应用版本升级
approllback.yml用于一般的应用版本升级的变更回退步骤
运行ansible的命令：ansible-playbook appupdate.yml --extra-vars "Version=V1.15.1"
                   ansible-playbook approllback.yml --extra-vars "Version=V1.15.1"
其中Version变量是升级的版本号
此ansible文件仅供参考
