## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行
## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行
## duck不必fork！ duck不必fork！duck不必fork！ 给个星星就行

## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！
## 注意，宝箱重写会与签到重写冲突，抓之前请关闭签到的重写！！



## 文章,视频：wzbody
* 进入app点击文章、视频获取body，进入app阅读文章一分钟左右，退回主界面会抓取
* 请务必抓取阅读时长，否则容易黑号
## 看看赚：lookStartbody,jc_cookie
* 点击看看赚某一任务获取body
## 每日任务奖励领取：jcboxbody
* app下方点击赚钱图标，在每日任务中点击所有可领取的奖励，获取body，明天再跑一次脚本试试
## 签到：qdbody
* 进入app点击签到，显示增加金币，则获取body成功
## 文章时长：jc_timebody
## 提现：jc_withdraw
* jc_cash(无需抓包，属于个人设置)
## 转盘抽奖：jc_cookie
## 火爆转发：jc_cookie
## 任务宝箱奖励领取：jcboxbody
* app下方点击赚钱图标，在每日任务中点击所有可领取的奖励，获取body，明天再跑一次脚本试试
* 注意⚠️重写会与签到脚本的重写冲突，抓取任务宝箱body之前记得把签到脚本的重写关掉
## 自动提现：jc_cookie,jc_withdraw,jc_cash（个人不建议自动提现，真的没必要）
* 打开app进入提现页面?选择对应金额?点击立即提现（不管当日是否已经提现，都能抓）?到变量中查看到有jc_withdraw即可
* 注意多账号用户抓包jc_withdraw时需要与jc_cookie账号顺序一致
* jc_cash不填默认0.3元，填的话有0.3，30两个选项（boxjs订阅中可直接修改，没有订阅的话直接新建变量即可）
* jc_withdraw务必与jc_cash金额一致，即修改jc_withdraw时也要修改jc_cash
## 福利视频：jc_cookie
* 首次跑完之后需要打开jcbox的重写，在app-赚钱-每日任务-看福利视频处，领取任务奖励，以后就不用管了。
## 晶彩cookie：jc_cookie
## 好友签到红包：jc_cookie
* 好友签到红包位置：打开app → 下方左起第三个选项（赚钱图标） → 中间好友红包（在看看赚的左边）
* 每天每位好友签到后有4个红包，前两个是100金币，后面两个是10金币，先抢先得

## MITM解析域名
* ant.xunsl.com

## 晶彩看点文章
* 匹配链接 https://ant.xunsl.com/v5/article/info.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jcwz.js

## 晶彩看点视频
* 匹配链接 https://ant.xunsl.com/v5/article/detail.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jcwz.js

## 晶彩看点阅读时长
* 匹配链接 https://ant.xunsl.com/v5/user/stay.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jcwz.js

## 晶彩看点签到
* 匹配链接 https://ant.xunsl.com/v5/CommonReward/toGetReward.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jcqd.js

## 晶彩看点看看赚
* 匹配链接 https://ant.xunsl.com/v5/nameless/adlickstart.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jckkz.js

## 晶彩看点宝箱
* 匹配链接 https://ant.xunsl.com/v5/CommonReward/toGetReward.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jcbox.js

## 晶彩看点自动提现
* 匹配链接 https://ant.xunsl.com/v5/wechat/withdraw2.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jc_withdraw.js

## 晶彩看点每日收益查询
* 匹配链接 https://ant.xunsl.com/v17/NewTask/getTaskList.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jc_today_score.js

## 晶彩看点火爆转发
* 匹配链接 https://ant.xunsl.com/v17/NewTask/getTaskList.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jc_share.js

## 晶彩看点5分钟60分钟任务
* 匹配链接 https://ant.xunsl.com/v17/Ad/getReward.json
* 重写目标 https://raw.githubusercontent.com/knowledgeablelmh/Android-V2P/main/jckd/jc_5_60.js
