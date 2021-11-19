腾讯自选股APP & 微信微证券公众号
改自@CenBoMin大佬的脚本
只适配了IOS，测试了青龙和V2P，其他平台请自行测试，安卓请自行测试
多用户用#隔开

脚本只会在10点到13点之间进行猜涨跌，请务必在这段时间内跑一次脚本，猜涨跌开奖时间为15:15
有些任务会提示任务完成发奖失败 -- 可以忽略
或者任务完成前置条件不符合 -- 一般为需要分享，会在完成日常任务后尝试做互助

内置了多用户相互做分享任务，用户数多于一个才能用
测试了做分享任务的情况下，一天收益大概在15000金币
默认自动提现5元，做分享任务，不做新手任务
新手任务可能需要跑几次才能做完，不过每天跑的话总会做完的

提现条件设置：自己新建一个TxStockCash环境变量，0代表不提现，1代表提现1元，5代表提现5元
新手任务设置：新建一个TxStockNewbie环境变量，0代表不做新手任务，1代表做新手任务
分享任务设置：新建一个TxStockHelp环境变量，0代表不做分享互助，1代表做分享互助
互助顺序设置：新建一个TxStockHelpOrder环境变量，按顺序填入要帮助的用户，0代表不帮助其他用户，每个用户之间用@或者#隔开

青龙：
APP和微信都捉 https://wzq.tenpay.com/cgi-bin/activity_task_daily.fcgi? 开头的包，点击获取金币，看到任务应该就能捉到
APP捉包把整个URL放进去TxStockAppUrl，header转成JSON字符串之后放进去TxStockAppHeader
微信微证券公众号捉包后header转成JSON字符串之后放进去TxStockWxHeader
export TxStockAppUrl='https://wzq.ten....#https://wzq.ten....#https://wzq.ten....'
export TxStockAppHeader='{"Host":"...","Accept":"...",...}#{"Host":"...","Accept":"...",...}#{"Host":"...","Accept":"...",...}'
export TxStockWxHeader='{"Host":"...","Accept":"...",...}#{"Host":"...","Accept":"...",...}#{"Host":"...","Accept":"...",...}'

重写食用
TxStockAppUrl与TxStockAppHeader：打开APP，点击头像->右上角金币->获取金币
TxStockWxHeader：打开 腾讯自选股微信版|微证券 公众号，右下角好福利->福利中心

V2P：
重写: https://wzq.tenpay.com/cgi-bin/activity_task_daily.fcgi?   https://raw.githubusercontent.com/leafxcy/JavaScript/main/txstock.js
MITM: wzq.tenpay.com

圈X：
[task_local]
#腾讯自选股
16 12,15 * * * txstock.js, tag=腾讯自选股, enabled=true
[rewrite_local]
#获取APP和微信微证券的URL和header
https://wzq.tenpay.com/cgi-bin/activity_task_daily.fcgi? url script-request-header https://raw.githubusercontent.com/leafxcy/JavaScript/main/txstock.js
[MITM]
hostname = wzq.tenpay.com
