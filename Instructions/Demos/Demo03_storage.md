---
demo:
  title: 演示 03：访问 Azure Linux 虚拟机的存储
  module: 'Guided Project: Deploy and administer Linux virtual machines'
---

# 演示 03：访问 Azure Linux 虚拟机的存储

## 凭据任务

+ 创建虚拟机 (CLI)。
+ 添加虚拟机数据磁盘并配置分区。 
+ 在 Linux VM 上装载 SMB Azure 文件共享。
+ 在 Linux VM 上分配托管标识。 
+ 分配 Azure 角色。 
+ 使用 AzCopy 将数据传入和传出 Linux VM。 

## 资源要求

可以在演示之前或期间创建这些资源。 
+ 资源组
+ Linux 虚拟机。
+ 带有文件共享和 Blob 容器的存储帐户。
+ 要用于测试的已上传文件。
+ 托管标识。 

## 引用步骤

这些链接中提供了详细步骤。

+ [快速入门：在 Azure 上使用 Azure CLI 创建 Linux 虚拟机](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-cli)
+ [将数据磁盘附加到 Linux VM](https://learn.microsoft.com/azure/virtual-machines/linux/attach-disk-portal)
+ [创建 SMB 文件共享](https://learn.microsoft.com/azure/storage/files/storage-how-to-create-file-share?tabs=azure-portal)
+ [AzCopy 入门](https://learn.microsoft.com/azure/storage/common/storage-use-azcopy-v10)


## 参考幻灯片

将这些幻灯片用于其他上下文。 
+ 存储帐户
+ Blob 容器和文件
+ 文件与 blob
+ 托管标识
+ 基于角色的访问控制

## 讨论点

**使用 CLI 创建虚拟机** - 参考 #1

>可以使用现有 VM，而不是创建另一个 VM。

1. 访问 Cloud Shell。

1. 使用 CLI 创建虚拟机。 指出这是学生展示的创建 VM 的第三种方式。
   
**将数据磁盘添加到 Linux 虚拟机** - 参考 #2

1. 查看如何使用门户向虚拟机添加数据磁盘。 学生将在练习中使用 CLI。

1. 连接到虚拟机并使用 `lsblk` 列出磁盘。 请注意磁盘大小，并且磁盘未装载。

1. 使用 `parted` 和 `partprobe` 准备磁盘。 使用引用链接中的代码。

1. 装载磁盘并使用 `df` 列出装入点。 

**从虚拟机访问 SMB 文件共享** - 参考 #3 和学生实验室说明

1. 找到存储帐户并讨论文件共享。

1. 将托管标识分配给虚拟机。 标识应有权访问存储帐户。

1. 复制门户脚本以从 Linux 虚拟机访问文件共享。

1. 连接到虚拟机并使用脚本创建文件。 可以使用 vi 编辑器。

1. 运行脚本并装载文件共享。 

**使用 AzCopy 将 blob 文件复制到数据驱动器** - 参考 #4 和学生实验室说明。

1. 向虚拟机添加“Blob 数据存储参与者”角色。 查看其他 blob 角色。 

1. 连接到虚拟机并安装 AzCopy。 查看可用于传输文件的其他工具。 

1. 使用 AzCopy 将文件从 Blob 存储传输到数据驱动器。 还可以将文件传输回 Blob 存储。  
