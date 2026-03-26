# buildVPN-SSR

## 购买海外节点的服务器
海外节点</br>
以阿里云购买轻型应用服务器为例，选择通用型实例，系统选择centos，节点选择海外，提交即可</br>
<img width="1524" height="1098" alt="image" src="https://github.com/user-attachments/assets/2b40369a-8c01-48d8-887f-01ae6cfc9807" />


## 安装ssr
[参考安装ssr的参考步骤](https://github.com/sucong426/VPN)

执行如下命令</br>
```bash
wget –no-check-certificate -O ss.sh https://raw.githubusercontent.com/sucong426/VPN/main/ss.sh

chmod +x ss.sh

sh ss.sh install
```

安装过程需要选择 Encryption Method:  aes-256-cfb  </br>

记录下ip, port, password, encryption method </br>

## 配置
添加访问规则：将安装ssr时的port添加到服务器的访问规则中

![image](https://github.com/naughtybabyfirst/buildVPN-SSR/assets/10113802/8f659a08-4fec-48e1-93e9-41f47a5ad2db)

## 使用
PC端使用 ShadowsocksR等</br>
iOS使用 shadowrocket等
