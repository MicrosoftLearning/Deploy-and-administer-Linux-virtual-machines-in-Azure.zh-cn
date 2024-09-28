---
demo:
  title: 演示 04：备份 Azure Linux 虚拟机
  module: 'Guided Project: Deploy and administer Linux virtual machines'
---

# 演示 04：备份 Azure Linux 虚拟机

## 凭据任务

+ 配置 Azure 备份 

## 资源要求

+ Linux 虚拟机

## 引用步骤

此链接中提供了详细步骤。

+ [快速入门：在门户中备份虚拟机](https://learn.microsoft.com/azure/backup/quick-backup-vm-portal)
+ [快速入门：使用 Azure 门户创建和部署 ARM 模板](https://learn.microsoft.com/azure/azure-resource-manager/templates/quickstart-create-templates-use-the-portal)

## 参考幻灯片

将这些幻灯片用于其他上下文。  

+ 什么是 Azure 备份？
+ 用于保护虚拟机的选项

## 讨论点

1. 查看导入模板。 这是他们在类中创建 VM 的第四种方式。
   
1. 讨论恢复服务保管库的需求。 保管库必须位于数据源所在的区域。 

1. 查看如何在门户中访问和启用虚拟机备份。 

1. 讨论标准备份策略与增强型备份策略之间的差异。 

1. 使用**数据源类型**下拉列表查看备份中心可以保护的资源。

1. 指出默认备份策略以及可以创建自定义备份策略。

1. 讨论如何在许多不同的虚拟机之间使用单个备份策略。

1. 查看备份策略配置设置（计划和保留期）。

1. 查看如何监视备份作业。

1. 查看如何还原虚拟机（不在凭据上）。 
