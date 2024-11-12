# 文件说明

## account_details.csv

模拟账户信息表

|字段|说明|
|---|---|
|account_id| 用户id，区分用户，可以模拟多个用户|
|init_balance|初始资金|
|current_balance|当前资金|
|total_asset|总资金|
|tag|标签|

## networth.csv

账户净值表

|字段|说明|
|---|--|
|strategy_name|策略名称|
|date|日期|
|equity|本金|
|networth|净值|

## position_details.csv

仓位信息表

|字段| 说明                      |
|---|-------------------------|
|strategy_name| 策略名称                    |
|symbol| 品种名称                    |
|pos_type| 持仓方向:1(多仓),-1(空仓),0(无持仓) |
|pos_num| 持仓数量                    |
|pos_price| 持仓价格                    |
|pnl| 盈亏                      |
|max_pnl|最大盈利|
|status| 仓位状态:'open'/'close'     |             
|open_time| 开仓时间                    |
|update_time| 更新时间                    |

## trading_history.csv

模拟交易记录信息表

|字段| 说明   |
|---|------|
|strategy_name| 策略名称 |
|symbol| 品种名称 |
|action| 动作   |
|pos_num| 持仓数量 |
|price| 持仓价格 |
|trading_time| 交易时间 |
