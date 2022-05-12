<template>
	<view>
		<view>
			<u-alert title="预计阅读时间3-5分钟,总计45个card,注意合理安排~ " :show-icon="true" type="warning"></u-alert>
		</view>
		<view class="base">
			<uni-card title="初次认识" sub-title="First" extra="2021下半期">
				<text class="uni-body">2021下半学期，因为刘倩，我和你第一次认识（占位符）</text>
			</uni-card>
			<uni-card title="你第一次给我发消息" sub-title="Second" extra="2022.1.14">
				<text class="uni-body">第一次发消息竟然是因为要我玩文艺复兴？！？！？！</text>
			</uni-card>
			<uni-card title="跨年" sub-title="Third" extra="2022.2.1 凌晨0:04">
				<text class="uni-body">“新年快乐 玫瑰”（我忘记回了，人太多了ababababababababaababababab）</text>
			</uni-card>
			<uni-card title="去川大" sub-title="第四次" extra="2022.3.18 下午">
				<text class="uni-body">我还记得，那是和你聊的最深的一次，也是第一次，也正是这一次“促膝长谈”，我......</text>
			</uni-card>
			<uni-card title="晚安" sub-title="第一个晚安" extra="2022.3.20 凌晨0:08">
				<text class="uni-body">“晚安”“白白晚安”（填满空隙填满空隙填满空隙填满空隙</text>
			</uni-card>
			<uni-card title="原神" sub-title="年后第一次上原神" extra="2022.3.27 凌晨0:12">
				<text class="uni-body">年后我就没怎么玩原神了，我又是个不喜欢玩游戏的人，但是我却加了你原神好友，还上线玩了半个小时？！</text>
			</uni-card>
			<uni-card title="可乐" sub-title="第一瓶可乐" extra="2022.3.29 中午">
				<text class="uni-body">这个确实是我同学给我带错了/doge，虽然后来才知道你不喜欢喝无糖</text>
			</uni-card>
			<uni-card title="川大" sub-title="第二次去川大" extra="2022.4.2 晚上9:30">
				<text class="uni-body">闲聊，了解了一点点你妈的工作相关，顺便安慰了一下姚悦妈骂你</text>
			</uni-card>
			<uni-card title="表白墙" sub-title="发了一个表白墙" extra="2022.4.2 晚上11:27" cover="/static/27.png">
				<text
					class="uni-body">我评论区at了你，但你好像看成下一张了，应付我了一个“666”，我私发给你，你说“麻了”“我知道是谁，就是之前给你说的那个人”（没猜错的话指cxr））</text>
			</uni-card>
			<uni-card title="给了一个口罩" sub-title="小忙" extra="2022.4.6 放学">
				<text class="uni-body">你没拿口罩 你没拿口罩 你没拿口罩 你没拿口罩 你没拿口罩 </text>
			</uni-card>
			<uni-card title="你的大事" sub-title="和cxr表白" extra="2022.4.8 放学">
				<text
					class="uni-body">wc这个事得好好说说，本来打算这个周六就去给你暗示一下，结果被tyx捷足先登了，他把你俩搓成了，也是这周6，tyx在往回走的路上问我“宝哥有没有喜欢的人啊”“你猜”，把所有人说完了，最后说的“gyx？”，我说“对”，他震惊“wc宝哥我突然有点对不起你”，我倒觉得没啥</text>
			</uni-card>
			<uni-card title="一点点" sub-title="买杯奶茶" extra="2022.4.9 中午11:48">
				<text class="uni-body">本来想给你买个茶百道/丸摩堂的，结果你不要，你说你要一点点</text>
			</uni-card>
			<uni-card title="失落" sub-title="看到了一些东西" extra="2022.4.9 下午2:40">
				<text class="uni-body">你点完了一点点，我看到了你置顶了cxr，u1s1，真的有点失落</text>
			</uni-card>
			<uni-card title="帮忙拿拍子" sub-title="记性有待提高" extra="2022.4.9 中午">
				<text class="uni-body">视频找拍子，找了快10分钟hhhhhhhhc（还说要请我吃东西，怎么还没兑现？doge）</text>
			</uni-card>
			<uni-card title="好烦" sub-title="闲聊" extra="2022.4.10 凌晨0:04">
				<text class="uni-body">你不会聊天，不如玩游戏，本来想给点指导，后来一想，不对啊，这是能免费指导的东西？？？</text>
			</uni-card>
			<uni-card title="宝哥做示范" sub-title="有点吓人" extra="2022.4.10 凌晨0:10">
				<text class="uni-body">我说不像我够勇，你说宝哥也谈一个，给我做示范，我是真懵了？？？这我该怎么回答？？？？</text>
			</uni-card>
			<uni-card title="不想谈了" sub-title="不想谈了 好烦" extra="2022.4.11 晚上7:31">
				<text class="uni-body">你说谈起来没意思，虽然确实喜欢，还不如之前暗恋来的开心（我也觉得）</text>
			</uni-card>
			<uni-card title="罐可" sub-title="间间断断的送点小东西" extra="2022.4.14 晚上7:03">
				<text class="uni-body">没敢去送，委托tyx送的，有那么亿点点点点点点点点点点点点点点害怕</text>
			</uni-card>
			<uni-card title="照片调色" sub-title="wc这专业对口不得展示一下？" extra="2022.4.16 晚上9:02" cover="/static/61.png">
				<text class="uni-body">我还专门打开了Lr，平时我哪修别人的照片，都是自己拍的才修一下，你还是第一个</text>
			</uni-card>
			<uni-card title="编曲小demo" sub-title="无聊做的(其实是在练手给你写歌)" extra="2022.4.17 晚上10:38">
				<text class="uni-body">第一次用ni的电鼓battery4，有一点点生疏，不过技术过硬，用的还凑合</text>
			</uni-card>
			<uni-card title="放学路上" sub-title="tyx说的其实差不多是真的" extra="2022.4.18 晚上7:22">
				<text class="uni-body">tyx要挟我，我以为他不会发，结果真发了，有一点点慌，不过还好</text>
			</uni-card>
			<uni-card title="薯片" sub-title="带点小东西" extra="2022.4.19 中午">
				<text class="uni-body">tyx+lgt一起拖我下去给你送，我说我怂，不敢，结果下去还遇到cxr了...虽然最后送了</text>
			</uni-card>
			<uni-card title="扯了一点about 你&cxr的" sub-title="这个没有副标题" extra="2022.4.19 晚上9:13">
				<text class="uni-body">我给你讲了cjc的事，你说你80%要be，结果到现在都还没分</text>
			</uni-card>
			<uni-card title="手表" sub-title="物理二没钟" extra="2022.4.21 早上">
				<text
					class="uni-body">本来你借的lgt的表，后来第二天早上我临时和lgt商量好，她假装忘带手表了，你来找我借，给个机会，娄来找我接水的时候，我直接脱口而出“你没带啊？”好像有点穿帮唉，后来检查消息，是因为怕qq消息同步过来，怕你看到我给你开了特别关心</text>
			</uni-card>
			<uni-card title="罐可" sub-title="二选一" extra="2022.4.21 下午6.31" cover="/static/86.jpg">
				<text class="uni-body">竟然选了罐可？？？我还以为你要选蜜雪ababababababababababa</text>
			</uni-card>
			<uni-card title="表盘" sub-title="还手环" extra="2022.4.21 晚上6:31">
				<text class="uni-body">怎么表盘全是心率？？？？？？？？？？？？都快成红色了</text>
			</uni-card>
			<uni-card title="beat demo" sub-title="编曲练手" extra="2022.4.22 晚上11:41">
				<text class="uni-body">ohhhhhhhhhh你说beat鼓组写的不错，op1的老师也这么说</text>
			</uni-card>
			<uni-card title="被发现了" sub-title="闲聊" extra="2022.4.23 凌晨">
				<text class="uni-body">聊了一个小时，第二次深入了解，聊到1点半，你是终于肯睡了</text>
			</uni-card>
			<uni-card title="二诊打赌" sub-title="请吃饭" extra="2022.4.24 晚上8:08">
				<text class="uni-body">其实我是真走不了，不过你这么肯定我，那走不了就你请哈哈哈哈哈哈哈</text>
			</uni-card>
			<uni-card title="网易云一起听" sub-title="网易云一起听" extra="2022.4.28 晚上9:57">
				<text class="uni-body">一起听我还只和cjc开过，还是他邀请的我，其实我是有点紧张的hhhhhhhh我怕你拒绝</text>
			</uni-card>
			<uni-card title="记手帐" sub-title="深入了解" extra="2022.4.28 晚上10:30">
				<text class="uni-body">你肯主动分享小事给我辣，我really really really really开心</text>
			</uni-card>
			<uni-card title="op1" sub-title="没来真的好遗憾" extra="2022.4.29 晚上">
				<text class="uni-body">啊啊啊啊说实话是我我绝对不会去吃火锅，真的去了一趟op1真的太值得了！！！</text>
			</uni-card>
			<uni-card title="看电影" sub-title="变成我请你了" extra="2022.5.1 晚上" cover="">
				<text class="uni-body">u1s1我是真的不敢靠上去，我怕你觉得ex，第一次和你看电影，有点紧张，10%的时间都在看你,没怎么好好看情节（2022.5.4 下午 补：如果你觉得那天我做的确实有点过分的话，我向你道歉，对不起了）</text>
			</uni-card>
			<uni-card title="Parties - Jake Miller" sub-title="好汀!" extra="2022.5.1 晚上" cover="/static/124.png">
				<text class="uni-body">单曲循环了2天了，真的好好听（当我写这段代码的时候我也在听hhhhhc）</text>
			</uni-card>
			<uni-card title="so saaaaaad" sub-title="unhappy" extra="2022.5.2 下午" cover="">
				<text class="uni-body">为啥你总是玩失踪啊啊啊啊啊啊啊，有的消息回有的消息不回，这就是冷处理吗</text>
			</uni-card>
			<uni-card title="买药" sub-title="好贵" extra="2022.5.3 上午10:11" cover="/static/128.png">
				<text class="uni-body">关心一下你啦，虽然这一瓶75，但是你要是说要，我还是会给你买的啦</text>
			</uni-card>
			<uni-card title="踩红线" sub-title="我怀疑你是装的doge" extra="2022.5.3 下午7:04" cover="/static/131.png">
				<text class="uni-body">怎么聊着聊着就聊到红线上面去了，聊的我好紧张啊啊啊啊啊</text>
			</uni-card>
			<uni-card title="烦" sub-title="莫名其妙的烦" extra="2022.5.3 晚上23:57" cover="">
				<text class="uni-body">当我知道你莫名其妙烦我，我当时真的强装镇定，但是还是有点崩溃，1点躺下的，2点睡着的，我真的不知道该怎么办了，除了崩溃，没有别的</text>
			</uni-card>
			<uni-card title="道歉专栏" sub-title="sorry" extra="2022.5.4 晚上9:04" cover="">
				<text class="uni-body">对不起套哥，最近可能有一些行为，让你感觉不舒服，在此向你道歉</text>
			</uni-card>
			<uni-card title="吓人" sub-title="终于不那么emo了" extra="2022.5.5 晚上7:44" cover="">
				<text class="uni-body">我还以为你真的不会回我了5555555555555555555555555555555555555</text>
			</uni-card>
			<uni-card title="建议" sub-title="你是真不会拍照啊" extra="2022.5.5 晚上10:33" cover="">
				<text
					class="uni-body">你觉得是真不会拍照啊，明明真人多好看的，每次看你空间发的自拍都觉得不像你hhhhhhhhc，那天买蜜雪的时候，你说能不能把店买下来给你，当时我知道你烦我，没敢多说话，但是你直勾勾看着我，我真的aaaaaa！不知道怎么说了</text>
			</uni-card>
			<uni-card title="网易云一起听" sub-title="114!" extra="2022.5.5 晚上10:33" cover="/static/128.jpg">
				<text class="uni-body">hhhhhhc一起听114小时（我知道是忘记退出了hhhhhhhhhh）</text>
			</uni-card>
			<uni-card title="没点赞" sub-title="上面下面都点了" extra="2022.5.6 晚上11:10" cover="/static/139.jpg">
				<text class="uni-body">你是不是把我屏蔽了555555,上面的下面的都点了，就我的没点，真的会乱想</text>
			</uni-card>
			<uni-card title="专门优化" sub-title="专项优化" extra="2022.5.6 晚上11:14" cover="/static/142.png">
				<text class="uni-body">专门用了x的布局，给iPhone X做了适配，确保不会出现过宽过窄</text>
			</uni-card>
			<uni-card title="特别篇" sub-title="END" extra="2022.5.9 晚上9:14" cover="">
				<text class="uni-body">是时候结束这一切了，我知道你有npy，我这么搞不太好，但是一直舍不得，因为我觉得，当这个链接发出去的时候，就象征着结束了，一切都结束了，我很舍不得，但是我告诉我自己必须要有道德底线，本来今天还给你买了个小风扇+维他命水，也不知道有没有机会送了，这是最后一个card了，这个网站我也不知道什么时候我会把它下架，就这样吧，that' all，到此为止咯~</text>
			</uni-card>
			<uni-card title="特别篇2" sub-title="no sub title" extra="2022.5.12 晚上11:11" cover="">
				<text class="uni-body">昨天有点emo，实在是舍不得，今天好点了，希望我可以forget it吧</text>
			</uni-card>

			<uni-title type="h4" title="————————2022.3.19-现在————————"></uni-title>
			<uni-title type="h5" title="希望在这一个多月的时间里,可以给你带来一丢丢的happy"></uni-title>
			<uni-title type="h5" title="如果对你造成了任何困扰或烦恼,在此再次道歉"></uni-title>
			<uni-title type="h5" title="应该是三年以来最喜欢的,也是最认真的了"></uni-title>
			<uni-title type="h4" title="写在最后,我喜欢你套套"></uni-title>
			<uni-title type="h4" title="———— 最后修改于 2022.5.12 晚上11:13 ————"></uni-title>


		</view>
	</view>

</template>

<script>
	export default {
		data() {
			return {

			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.base {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>
