# 简介
官方文档地址  http://dubbo.apache.org/zh-cn/





##负载均衡策略
#提供四种负载均衡实现
	基于权重随机的算法：RandomLoadBalance
	基于最少活跃调用数算法：LeastActiveLoadBalance
	基于Hash一致性：ConsistentHashLoadBalance
	基于加权轮询算法：RoundRobinLoadBalance