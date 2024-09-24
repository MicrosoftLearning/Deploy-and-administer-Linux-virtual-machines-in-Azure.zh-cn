---
demo:
  title: 演示 01 - 配置 Azure Linux 虚拟机
  module: 'Guided Project: Deploy and administer Linux virtual machines'
---

# 演示 01 - 配置 Azure Linux 虚拟机

## 凭据任务

使用此演示查看这些凭据任务：
+ 创建 Linux 虚拟机（门户）。
+ 配置 Linux VM。
+ 使用 SSH连接到 Linux VM。  
+ 更新 Linux VM 操作系统。
+ 安装并运行工作负载依赖项。

## 资源要求

可以在演示之前或期间创建此资源。 

+ 资源组。 

## 参考幻灯片（可选）

+ 虚拟机的计划
+ 支持的 Linux 分发
+ 虚拟机大小调整
+ Azure 资源组织
+ Azure 管理员工具

## 引用步骤

这些链接中提供了详细步骤。

+ [使用 Azure 门户预配 Linux 虚拟机](https://learn.microsoft.com/training/modules/provision-linux-virtual-machine-in-azure/2-provision-linux-virtual-machine-using-the-azure-portal)
+ [快速入门：创建 Linux VM](https://learn.microsoft.com/azure/virtual-machines/linux/quick-create-portal?tabs=ubuntu)

## 讨论点

**创建和配置虚拟机**

1. 使用门户来创建 Linux VM。 讨论如何在后面的练习中使用 CLI 和快速入门模板来创建 VM。 

1. 使用门户链接查看 Linux **映像**选择。  确定最新的 Ubuntu 分发版。

1. 使用门户链接查看**大小**选择。  讨论如何缩放 CPU 和内存设置。

1. 讨论重设大小的效果。 重设大小将在后面的实验室中完成。 

1. 讨论连接到 Linux 虚拟机的不同方式（SSH 公钥和密码）。
   
1. 讨论**入站端口规则**的重要性。 具体而言，用于 SSH 的端口 22 和 Nginx 的端口 80。 

1. 使用“**磁盘**”选项卡显示如何添加数据磁盘。 稍后的练习中将添加数据磁盘。 
 
1. 使用“**高级**”页可显示可以在哪里提供 cloud-init 文件。

1. 此外，后续练习使用模板和 CLI 来安装虚拟机。 

**访问虚拟机并安装 Nginx**

1. 部署虚拟机。 讨论验证阶段以及如何监视通知。

1. 打开 CMD 窗口并使用 SSH 访问虚拟机。 讨论 SSH 命令的格式和密钥文件的位置。 

1. 安装 Nginx 并确保显示主页。 
