# Quantitative_Trading
some quantitative trading notes with python
### DoubleMaStrategy
1. 使用事件驱动型回测来验证简单的双均线策略，避免了向量化回测所可能带来的未来函数
2. 创建DailyResult类用于储存每日盈亏数据，for循环运行回测
3. 为便于计算，默认每日收盘前一秒快速计算当日交易信号，并进行买入卖出操作，下一步将细化成交价格对于策略收益的影响
