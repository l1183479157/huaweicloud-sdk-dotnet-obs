 
Version 3.1.2

新特性：
1. 桶事件通知接口（ObsClient.SetBucketNotification/ObsClient.GetBucketNotification）新增对函数工作流服务配置和查询的支持；

资料&demo：
1. 开发指南事件通知章节，新增对函数工作流服务配置的介绍；
	

修复问题：
1. 修复创建桶接口（ObsClient.CreateBucket）由于协议协商导致报错信息不准确的问题；
2. 修复示例代码BucketOperationsSample.cs中的错误；
