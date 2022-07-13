# inspiration
# 提交规则：
## feat: 表示新增功能
## refactor：表示对功能的重构
## fix：表示修复bug
## doc：表示更新文档
思维导读在线工具：http://39.105.53.80:8001/
> 1. docker 拉取镜像：docker pull fjudith/draw.io
> 2. 启动镜像：docker run -itd --name="draw-io" --restart=always -p 8001:8080 fjudith/draw.io
> 3. 开启端口权限：firewall-cmd --permanent --zone=public --add-port=8001/tcp
> 4. 如果没有 firewall-cmd 则装一下：apt install firewalld
> 5. 确保云服务上相应的安全组规则也对此端口开放后重启云服务

前端采用vue进行开发，文档地址：https://v3.cn.vuejs.org/guide/introduction.html
