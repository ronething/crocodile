# Crocodile 任务调度系统.v3


# TODO
- [x] 用户管理  
      普通用户、管理员
- [x] 主机组管理
- [x] 主机管理
- [x] rpc调度任务执行
- [x] 调度任务采用tls加密、token认证
- [x] 任务操作[增加、删除、更新、查询、暂停调度]
- [x] 保存执行日志
- [x] 实现两种task Run 接口
- [x] 手动触发任务、终止任务、获取任务日志
- [x] 使用golint检测代码
- [x] 删除主机，暂停主机运行任务
- [x] 运行任务流式返回数据
- [x] 实时在线日志后端接口 
    - 任务执行结果需要流式的返回 
    - 运行任务重写
- [x] 在一个任务中保存父子主任务的状态
- [x] 平滑退出
- [x] 调度算法
    - 随机
    - 最少任务数
    - 权重
    - 轮询执行
- [x] 报警
    - 配置告警模式，任务失败、成功 时报警
    - 通过检测返回结果、状态码，来判断是否报警，默认只检查返回码。
    - 报警方式: email,telegram,slack,钉钉,webhooks，
- [x] 支持语言`shell`,`golang`,`python`
- [x] Swagger API
- [ ] 前端
- [ ] 记录软删除
- [ ] 返回任务总数
- [ ] 任务标签
- [ ] 任务克隆
- [x] 获取正在运行的任务(`websocket`)
- [ ] ldap支持
- [x] 操作审计
- [ ] 任务审核
- [ ] 定时删除执行日志
- [ ] `Prometheus`+`grafana` 监控
- [ ] 压力测试

- [ ] 调度中心集群