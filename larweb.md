#   laravel 基础操作

## 配置composer 国内阿里镜像
    ‘’‘ 
    compsoer config -g repo.packagist composer https://mirrors.aliyun.com/composer/   
    ’‘’

## 创建larweb 项目
    ‘’‘  
    composer create-project laravel/laravel larweb --prefer-dist "7.*"
    ’‘’
##  git 常用设置
    1.用户名和邮箱设置  --global 选项代表对 Git 进行全局设置。
        、、、
        git config --global user.name  "laolee"
        git comfig --global user.email "wencai159@126.com"
        、、、
    
    2.Git 推送分支时相关配置：
    此设置是 Git 命令 push 的默认模式为 simple，当我们执行 git push 没有指定分支时，自动使用当前分支，而不是报错
        、、、
        git config --global push.default simple
        、、、
    3.git 实际操作
        (1)对 git 进行初始化
        
        (2)将项目所有文件纳入到 Git 中：
        (3)检查 Git 状态：
        (4)保留改动并提交
        (5)查看历史提交记录：
        (6)git文件删除与恢复：
    4.github 实际操作
        (1)账号注册
        (2)为 GitHub 账号设置 SSH Key
        (3)提交代码到 Github#        
##  
