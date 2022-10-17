# 项目介绍

-  解决常用服务无法访问的问题

## 脚本介绍

### python依赖

python引入rich库，使用脚本前需 pip install -r requirements；

### 命令介绍

cd 至 workingDir 文件夹后 执行以下操作；

1. python ph.py -a domain domain ...
   -a命令，在默认domain列表后加入需要解析的域名；
2. python ph.py -d domain domain ...
   -d命令，使用自定义域名替换默认解析列表；
3. python ph.py -f file
   -f 命令，接收文本文件。
   解析文本文件中的域名;

以上命令将在当前文件夹中生成hosts.txt文件。
使用 -o 命令自定义输出文件名；（-o outputFile）

## hosts

### 本仓库 hosts文件介绍

1. hosts.txt 文件包含 GitHub hosts,Epic hosts,Microsoft hosts等；
2. Github 和 Epic 等分别有单独 hosts文件；

## 感谢

- [GitHub520](https://github.com/521xueweihan/GitHub520)
- [Hosts](https://github.com/JohyC/Hosts)

## TODO

- [x] GitHub Actions自动更新hosts内容.