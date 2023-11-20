# tmate
MobaXterm设置
settings --->  Configuration --->  SSH ---> SSH agents中上传"*.pub"密钥


Session --->  SSH --->  advanced SSH settings --->  勾选 Use private key --->  上传密钥 --->  在Remote host输入tmate生成的SSH地址即可


下载git bash
按照GitHub的官方文档生成密钥，当然也可以使用MobaXterm生成密钥。

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

添加密钥到账户后测试SSH连接

https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection

生成密钥时会提示为密钥创建密码“ Enter passphrase (empty for no passphrase):”

不想输入的直接回车即可。
使用mxschmitt/action-tmate@v3.17 时timeout参数报错
