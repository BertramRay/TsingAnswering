# TsingAnswering
清答疑小程序开发工作组仓库

## Todo

- 本todo仅作为4.28工作组会议的简单记录，具体是否需要实现，以及实现规划会在之后进行技术评估和讨论后确定。
- 最近可能比较忙所以评估会放在五一假期之后

### bug

- [x] 咨询消息通知除接单的志愿者外的其他志愿者也会收到消息通知
- [ ] 经由转发界面首次登陆小程序可能会要重启才能进入

### feature

- [x] 管理员需要删除订单和导出订单的功能(数据库人工实现)
- [x] 管理员需要批量添加志愿者的功能（数据库脚本实现）
- [ ] 志愿者需要对自己的已完成订单进行统计的功能
- [ ] 多人聊天室可能需要添加@的功能
- [ ] 新订单的出现可以通过订阅消息及时通知志愿者

### detail

- [ ] 需要更多的界面交互设计
- [ ] 聊天界面在调用输入框时界面应固定
- [x] 签到的时间和地点需要限制
- [x] 答疑信息和时长的实时更新
- [x] 志愿者时长和评级的计算
- [ ] 个人界面答疑时长显示志愿时长和勤工助学时长
- [x] 背景颜色设定问题
- [ ] 短时间内志愿者回复多条消息可能会导致提问者收到很多订阅通知
