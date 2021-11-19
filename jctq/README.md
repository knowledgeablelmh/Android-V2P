## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行
## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行
## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行

## 重写：
* https://tq.xunsl.com/v17/NewTask/getTaskListByWeather.json  -- 点开福利页即可获取jctqCookie，注意只支持单账户，新ck会覆盖旧ck
* https://tq.xunsl.com/v5/CommonReward/toGetReward.json       -- 签到，观看签到翻倍视频，和福利页任务奖励（目前应该只有激励视频和20篇文章的奖励），获取完建议关掉重写
* https://tq.xunsl.com/v5/article/info.json                   -- 点开文章获取文章body，获取完建议关掉重写
* https://tq.xunsl.com/v5/article/detail.json                 -- 点开视频获取视频body，获取完建议关掉重写
* https://tq.xunsl.com/v5/user/stay.json                      -- 阅读文章或者看视频一段时间后可以获取到时长body，获取完务必关掉重写
* https://tq.xunsl.com/v5/nameless/adlickstart.json           -- 点开看看赚获取body，可以一直开着，脚本会自动删除重复和失效body
* https://tq.xunsl.com/v5/Weather/giveBoxOnWeather.json       -- 点开福利页浮窗宝箱和观看翻倍视频获取body，获取完建议关掉重写
* https://tq.xunsl.com/v5/weather/giveTimeInterval.json       -- 点开首页气泡红包和观看翻倍视频获取body，获取完建议关掉重写
* https://tq.xunsl.com/v5/wechat/withdraw2.json               -- 提现一次对应金额获取body，新获取的提现body会覆盖旧的
## 任务：
* jctq_daily.js   -- 领转发页定时宝箱，领福利页定时宝箱，领首页气泡红包，时段转发，刷福利视频，抽奖5次
* jctq_reward.js  -- 签到和翻倍，任务奖励领取，统计今日收益，自动提现
* jctq_kkz.js     -- 完成看看赚任务，删除重复和失效的body
* jctq_read.js    -- 阅读文章，浏览视频
## 分享阅读：  
* jctq_shareRead.js       -- 分享和助力阅读，需要在环境变量jctqShareNum里设置要被阅读的次数，不设置默认不跑  
