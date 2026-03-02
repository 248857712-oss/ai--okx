1.config中接入自己的okxapi，代理地址
2.is_sim ：true为模拟盘 false为实盘（实盘能否运行未知）
3.该策略只做为学术学习，不具备投资要求
4.config中的一些参数      
 leverage：杠杆倍数
 position_ratio: 每次开仓比例
 lr_weight: 逻辑回归权重
 rf_weight: 森林模型权重
 vote_threshold: 权重开仓阈值
 tp_prob_threshold: 设置这个值（止盈概率阈值），判断是否超过该止盈概率
 sl_prob_threshold: 止损概率阈值，同上
 cycle_interval: 每次执行周期（单位：s）
 boll_window: 布林窗口值
 boll_dev: 布林标准差
 min_profit_threshold: 最小止盈阈值
 target_profit_ratio: 目标收益率
 min_loss_threshold: 最小止损阈值
5.模型可以通过获得训练集重新自动调参，但当无法调参或调参回测后仍然不完美，请手动调参并回测