# loopr-ios-docs

1. 点击keystore解锁，卡住 (Ruby)
2. p2p订单，第一个输入框里面没发选取lrc（可能因为第二个输入框是lrc），不能方便地把交易方向改过来
3. p2p订单，没有参考价格。建议在下方增加三个市场价格，比如币安，okcoin，bittrex。点击之后直接计算出第二个输入框的数字
4. p2p订单，空间上可以把有效期变成下拉框
5. ~~app store有 too many symbol files (不影响app的性能和功能。是给Apple的系统用于分析闪退用的。我们现在用Google的闪退分析，就够了。) (Ruby)~~
6. weth余额不足，eth余额充足的情况下，错误提示最好可以显示一个转换链接 (iwbrhwfy)
7. ~~错误提示的颜色太深~~
8. ~~滑动条，改为黄色 (Ruby)~~
9. ~~买入 变成 买~~
10. 条目中，日期中日月年可以不显示，可以按照日分组
11. 订单列表，每个订单的量可以像币安app里面那种暂时 100/200 表示一个单是量200，成交量是100
12. p2p订单，选择自定义过期时间后，再次选择的时候，默认值不体现我上次的选择。默认值应该体现我上次选择，或上次点击的其他按钮对应的值
13. ~~p2p订单，分享的图片，不能是个莫名其妙的二维码。甚至要更美观才行。体现买卖币种，过期时间，数量。最重要的是路印的场外交易订单。还要有个app下载url~~
14. ~~地址二维码分享页面，可以加upwallet的官网地址，下载UP Wallet~~
15. ~~分享地址二维码也只发二维码。变成宣传页。~~
16. ~~app下载不了。速度慢。~~
17. app目前有80M，太大了 (Ruby)
18. ~~添加代币的页面，toggle的颜色应该改为黄色。~~
19. ~~图片静态托管 (对app大小没有太大帮助，暂时不做)~~
20. 在导出私钥的时候，数字0和O容易混淆
21. 导入两个钱包，在界面上，不容易找到钱包切换
22. ~~翻译文件需要整理好 (Ruby)~~
23. ~~在设置里面点击生成新钱包之后点进入，app闪退 (Ruby)~~
24. 选择另一个钱包的时候可以把最后的确认对话框去掉 (Ruby)
25. ~~Data is temporarily unavailable 改为 No data available~~
26. ~~Convert的按钮，改为黄色~~
27. ~~etherscan.io的地方，页面加一个open in Safari按钮~~
28. ~~订单取消按钮，目前是蓝色，应该改为主题色~~
29. ~~转换页面，第二句话，改为 When converting ETH to WETH, we will reserve 0.01 ETH as gas fee for your future transactions.~~
30. ~~Set Gas, 改为 Set gas price~~
31. ~~生成助记词，每次到备份助记词页面，点击回到密码页面，再点击下一步，应该生成不同的地址。每次都不一样。~~
32. ~~输入钱包名字和密码的三个页面，输入焦点应该自动聚焦到输入框，不需要再点击一下 (Ruby)~~
33. ~~助记词不能跟密码相关。~~
34. ~~发送页面，缺少一个max按钮，而且滑动100%也无法把我的币转的干净，一分不差变成0~~
35. ~~扫码二维码不必要提供下面的弹出框~~
36. p2p订单，输入第一个金额后下面的滑动条没有自动更新
37. p2p下单后再没有confirm前，两个交易者都看不懂订单，这个其实可以通过中心华数据库一个改进。这个比较重要
38. ~~右上角的图标线条太宽了。~~
39. ~~根据地址添加token，app显示成功，但是找不到，没有显示出来~~
40. ~~添加过程中没有提示我symbol和digits。symbol应该是主动全大写。添加成功后，不应该停留在原页面。~~
41. ~~manage wallet应该改为manage wallets~~
42. ~~数据不可用图标和weth转换图标太像，应该换一个。~~
43. 在setting页面，推广收益地址，字体太大。
44. ~~Convertion ration应该改为 conversion ratio~~
45. 支持LRN绑定 (iwbrhwfy)
46. 申请直接上appstore (Ruby)
47. 发送token页面，资产很少的时候，下面百分比滑动不起效果
48. imToken的二维码包含其他信息，app无法直接读出地址
49. token的小数点精度应该从后端配置读取
50. ~~从图片读取二维码的功能 (Ruby)~~
51. ~~点击收藏，退出app再进入就没有了~~
52. ~~下单界面，为什么LRC等值USD0.08， WETH等值USD0.13~~
53. 下单界面，单价为什么变了0.0005？前一页下的是0.00057633
54. 搜索框显示，如果能有最近一次或者3次的搜索的代币，可以直接点击。
55. 交易界面的滑动条，需要联动
56. ~~Asset详情页面，4个tabs，数据和功能不是很清晰~~
57. 市场的搜索框，搜索出来的最好包括所有tab里面的包含lrc的交易对，但不包括以lrc为基本货币的交易对  (Ruby)
58. 市场的搜索框，激活时，tab应该隐藏。 (Ruby)
59. ~~imtoken的keystore，在loopring里面没有办法导入 (Ruby)~~
60. ~~loopr的资产显示会不定期的美元和人民币自动变化，这样会给用户带来困惑 (Ruby)~~
61. ~~添加钱包名称未有提示，实际已经添加成功了，但是显示名称添加重复，这时候改其他的名字再去添加钱包名称，会报错；导入失败，地址之前已经被导入 (Ruby)~~
62. 【bug】解锁多个钱包后，打开第二个钱包，点击copy address，结果拷贝的还是第一个app的地址。(iwbrhwfy and Ruby)
63. ~~将1‰改成 0.1%~~
64. ~~市场页面，搜索结果，点击进入详情页，返回，在点击会掉到不对的市场详情页面。~~
65. ~~在英文中，市场买卖页面，Amount的输入框有问题~~
66. app的涨幅，可以参考第三方
67. ~~Typo Congradualations 应该是 Congratulations~~
68. There should be a way to swap Buy / Sell 
69. ~~Loopr P2P Order should be Loopring P2P Order~~
70. 查看合约地址页面，应该加个在etherscsn.io察看的按钮；钱包本身也应该能一键在etherscan.io查看 (iwbrhwfy)
71. p2p下单页面，要显示一个价格，否则还要自己算。最好中间也显示兑换价格。点击一下显示反向的比例
72. 取消订单，现在是软取消。加上允许用户硬取消。UI上多个checkbox就可以。(iwbrhwfy)
73. 交易确认页面，价差分成建议去掉。(iwbrhwfy)
74. 有时候，用Lrc交易别的币时候，闪退。
75. 价格变化幅度用cmc的
76. app和web端也需要支持深度聚合。
77. 前后端还要支持另一个功能，就是默认很多交易对都是隐藏的，之后一些符合标准端交易对才默认展示出来，可以背浏览；隐藏的交易对通过搜索可以出来，点进去后也可以交易
78. 未实施屏幕截图检测措施 (iwbrhwfy)
79. 备份助记词，导出私钥没有密码保护 (Ruby)
