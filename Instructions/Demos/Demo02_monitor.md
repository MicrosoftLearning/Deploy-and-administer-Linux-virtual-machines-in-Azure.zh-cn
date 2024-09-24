---
demo:
  title: 演示 02：监视 Azure Linux 虚拟机
  module: 'Guided Project: Deploy and administer Linux virtual machines'
---

# 演示 02：监视 Azure Linux 虚拟机

## 凭据任务

+ 创建虚拟机（快速启动模板）。
+ 配置 VM 见解。
+ 创建警报。  
+ 确定性能问题。 
+ 调整虚拟机的大小。 

## 资源要求

+ Linux 虚拟机（使用自定义模板创建）

## 参考幻灯片 

+ Azure Resource Manager 模板
+ Azure Monitor 关键功能
+ Azure Monitor 组件
+ 指标和日志

  
## 引用步骤

这些链接中提供了详细步骤。

+ [部署简单的 Ubuntu Linux VM](https://learn.microsoft.com/azure/virtual-machines/linux/quick-create-template)
+ [为 Azure Monitor 代理启用 VM 见解](https://learn.microsoft.com/azure/azure-monitor/vm/vminsights-enable-portal#enable-vm-insights-for-azure-monitor-agent) 
+ [教程：为 Azure 资源创建指标警报](https://learn.microsoft.com/azure/azure-monitor/alerts/alerts-create-metric-alert-rule)


## 参考幻灯片（可选）

将这些幻灯片用于其他上下文。



## 讨论点

1. 为简单的 Linux Ubuntu 计算机使用“**部署自定义模板**”。 这就是学生在练习中创建 VM 的方式。 讨论模板的使用。 

1. 启用 VM 见解。 查看如何使用数据收集规则以及如何选择 Log Analytics 工作区。 

1. 在指标上创建警报。 例如，基于 CPU 百分比使用情况创建新的警报规则。

1. 讨论操作组的使用以及如何将操作组分配给警报。 

1. 查看在触发警报时如何监视警报。

1. 关闭如何导出资源模板。 
