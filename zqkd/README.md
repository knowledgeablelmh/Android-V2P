## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行
## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行
## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行

## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，会与签到重写冲突，抓之前请关闭签到的重写！！

阅读文章，看视频：zqwz.js（zqwzbody，zq_timebody）
- 进入app点击文章、视频获取body
- 注意⚠️请务必抓取阅读时长，否则容易黑号，进入app阅读一分钟左右会抓取
- 视频的body要点进去博主的主页单独看，才抓得到
- app-下方第二个视频图标，那里有很多个一起竖排，一个个点进去发布者主页看视频
签到：zqqd.js（zqqdbody）
- 进入app点击签到，显示增加金币，则获取body成功
看看赚：zqkkz.js（zqlookStartbody）
- 点击看看赚某一任务获取body
- 每日任务里面的xx送好礼也是看看赚，用看看赚去抓
任务宝箱奖励：zqbox.js（zqboxbody）
- app下方点击赚钱图标，在每日任务中点击所有可领取的奖励，获取body，明天再跑一次脚本试试
- 注意⚠️任务宝箱重写会与签到脚本的重写冲突，抓取任务宝箱body之前记得把签到脚本的重写关掉。
每日收益查询：zq_today_score.js（zq_cookie）
火爆转发：zq_share.js（zq_cookie）
转盘抽奖：zq_Rotary.js（zq_cookie）
好友签到红包?：zq_friendSign.js（zq_cookie）
福利视频：zq_Adv_video.js（zq_cookie）
自动提现：zq_withdraw.js（zq_withdraw,zq_cash）
- 定时确保在脚本运行之前完成即可，一天一次
- 打开app进入提现页面，选择对应金额，点击立即提现（不管当日是否已经提现，都能抓），到变量中查看到有zq_withdraw即可
- 注意⚠️多账号用户抓包zq_withdraw时需要与zq_cookie账号顺序一致
- zq_cash不填默认0.3元，填的话有0.3，30两个选项（boxjs订阅中可直接修改，没有订阅的话直接新建变量即可）
- zq_withdraw务必与zq_cash金额一致，即修改zq_withdraw时也要修改zq_cash
打卡赚：zq_wakeup.js(调用zq_cookie)
浏览赚：zqllz.js（调用zqllzbody)
- app-看看赚上方浏览赚-去白拿
搜索赚：zqssz.js（调用zqsszbody）
- app-看看赚上方搜索赚-选择带（火）图标任务-去搜索，随便选一个热词搜索即可退出。
- 搜索赚只支持带（火）图标任务


MITM解析域名
kandian.wkandian.com

中青文章
https://kandian.wkandian.com/v5/article/info.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zqwz.js
中青视频
https://kandian.wkandian.com/v5/article/detail.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zqwz.js
中青阅读时长
https://kandian.wkandian.com/v5/user/stay.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zqwz.js
中青搜索赚
https://kandian.wkandian.com/v5/Sousuo/playStart.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zqssz.js
中青签到
https://kandian.wkandian.com/v5/CommonReward/toGetReward.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zqqd.js
中青浏览赚
https://kandian.wkandian.com/v5/task/browse_start.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zqllz.js
中青看看赚
https://kandian.wkandian.com/v5/nameless/adlickstart.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zqkkz.js
中青宝箱
https://kandian.wkandian.com/v5/CommonReward/toGetReward.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zqbox.js
中青自动提现
https://kandian.wkandian.com/v5/wechat/withdraw2.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zq_withdraw.js
中青每日收益查询
https://kandian.wkandian.com/v17/NewTask/getTaskList.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zq_today_score.js
中青火爆转发
https://kandian.wkandian.com/v17/NewTask/getTaskList.json 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/zqkd/zq_share.js
