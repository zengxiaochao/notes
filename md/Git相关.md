## 配置
```
#绑定邮箱以及用户
git config --global user.name '用户名称'
git config --global user.email '登录邮箱'

#生成密钥
ssh-keygen -t rsa -C '登录邮箱'
```
上述代码执行完成后，会连续多次要求输入密码。注意：此时请不要输入密码。

--- 

打开.ssh文件夹下的id-rsa.pub文件的内容，全部复制。然后登录你的git服务器个人账户设置中，寻找ssh key菜单项，然后粘贴即可。

![](2022-01-21-18-46-57.png)