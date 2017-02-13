##VManagePlatform是什么?
一个KVM虚拟化管理平台

##开发语言与框架：
* 编程语言：Python + HTML + JScripts
* 前端Web框架：Bootstrap 
* 后端Web框架：Django  
* 后端Task框架：Celery + Redis

##VManagePlatform有哪些功能？

* Kvm虚拟机`生产周期`管理功能
    *  资源利用率（如：CPU、MEM、磁盘、网络）
    *  实例控制（如：生存周期管理、快照技术，Web Console等等）
    *  设备资源控制（如：在线调整内存、CPU资源、热添加、删除硬盘）
* 存储池管理
    *  增减卷，支持主流类型存储类型
    *  资源利用率
* 网络管理
    *  支持SDN，底层网络使用OpenVSwitch/Linux Bridge，支持子网隔离，IP地址分配，网卡流量限制等等。
* 用户管理
    *  支持用户权限，用户组，用户虚拟机资源分配等等 
* 宿主机
    *  资源利用率，实例控制

##部分功能截图登陆页面
    登录页面</br>
![](https://github.com/welliamcao/VManagePlatform/raw/master/demo_images/login.png)</br>
    用户注册需要admin激活才能登陆</br>
![](https://github.com/welliamcao/VManagePlatform/raw/master/demo_images/register.png)</br>
    主页</br>
![](https://github.com/welliamcao/VManagePlatform/raw/master/demo_images/index.png)</br>
    任务调度</br>
![](https://github.com/welliamcao/VManagePlatform/raw/master/demo_images/task.png)</br>
    宿主机资源</br>
![](https://github.com/welliamcao/VManagePlatform/raw/master/demo_images/server.png)</br>
    虚拟机资源</br>
![](https://github.com/welliamcao/VManagePlatform/raw/master/demo_images/instance.png)</br>
    Web Console</br>
    ![](https://github.com/welliamcao/VManagePlatform/raw/master/demo_images/consle.png)</br>
