# xrz_shell「1.0.1（4）」
欢迎使用xrz的linux软件补全脚本。  
### install脚本 [下载](http://8v2alw.coding-pages.com/install.sh)
wget下载「不定时更新」  
````
wget http://8v2alw.coding-pages.com/install.sh
````
或 git下载「最新」  
````
git clone https://e.coding.net/xrzyun/blog/xrz_shell.git
````
### install脚本 使用教程  
<font color="#FF0000"><b>记得设置执行权限:</b></font> 
`chmod 777 文件名(install.sh)`
直接执行 `./install.sh` 为 提示  
`./install.sh -h` 为 帮助  
其它

| 命令后缀 | 作用 |
| :-----: | :---: |
| -d y | 下载toolbox「没用的快捷命令」 |
| -i y  | 安装toolbox至 系统变量「可以直接输入作命令执行」 |
| -i n | 复制 到 用户指定目录 下「默认root目录」 |
| -c y | 清理缓存 |
| -tn {把这段中文改为名字} | 设置保存名「默认toolbox」 |
| -H {把这段中文改为名字} | 设置保存目录「默认/root/」 |
| -b y | 安装宝塔面板 |

### toolbox 使用教程  
直接执行脚本以询问使用命令。  
### 脚本开源，欢迎修改。