因不满老东家成为微软附庸，11名OpenAI公司前员工怒而出走。

如今带着“ChatGPT最强竞品”杀回战场，新公司 **估值50亿美元** ，一出手就获得 **3亿美元融资** 。

这家公司名叫Anthropic，新推出的聊天机器人产品名叫Claude。

拿到内部试用权的网友，在简单对比后惊叹：

> 看起来，Claude的效果要比ChatGPT **好得多** 。

![img](./assets/(null)-20230223090527240.(null))

比如，让ChatGPT写一句话，要求 **每个单词首字母都相同** ，结果试了好几次都没能成功。

![img](./assets/(null)-20230223090526994.(null))

而Claude不光一次成功，语句富有逻辑性，还能秒速再来一个。

![img](./assets/(null)-20230223090526948.(null))

同时，在面对某些缺乏常识的问题时，相比ChatGPT **一本正经地胡说八道** ：

![img](./assets/(null)-20230223090526935.(null))

反而会毫不留情地指出你的问题有点制杖：

![img](./assets/(null)-20230223090526900.(null))

###### **△** Claude：这什么鬼问题？

最有意思的是在写诗上。相比ChatGPT的车轱辘话，它写出来的东西完全不重样：

![img](./assets/(null)-20230223090526906.(null))

投资它的既有 **Facebook** 联合创始人Dustin Moskovitz，也有 **谷歌** 前CEO、现技术顾问Eric Schmidt——

都是OpenAI的老对头，又都被ChatGPT的出现杀得措手不及。

那么，这支“复仇者联盟”整出的竞品Claude，背后究竟是什么原理，和ChatGPT细节对比又如何？

## **Claude长啥样？**

先来看看 **Claude** 是如何被打造出来的。

作为一个AI对话助手，Claude自称基于前沿NLP和AI安全技术打造，目标是成为一个安全、接近人类价值观且合乎道德规范的AI系统。

据透露，Claude比Anthropic做的另一个预训练模型AnthropicLM v4-s3更大，后者是一个520亿参数大模型。

但目前它仍处于实验阶段，尚未作为商业产品正式发布：

> Claude能力依旧有待提升，希望未来能变成一个更有益人类的AI系统。

![img](./assets/(null)-20230223090527242.(null))

###### **△** 超长版自我介绍

和ChatGPT一样，Claude也靠强化学习 （RL） 来训练偏好模型，并进行后续微调。

具体来说，这项技术被Anthropic称为 **原发人工智能** （Constitutional AI） ，分为监督学习和强化学习两个阶段。

首先在 **监督学习** 阶段，研究者会先对初始模型进行取样，从而产生自我修订，并根据修订效果对模型进行微调。

随后在 **强化学习** 阶段，研究者会对微调模型进行取样，基于Anthropic打造的AI偏好数据集训练的偏好模型，作为奖励信号进行强化学习训练。

但与ChatGPT采用的人类反馈强化学习 （RLHF） 不同的是，Claude采用的原发人工智能方法，是基于偏好模型 **而非人工反馈** 来进行训练的。

因此，这种方法又被成为“AI反馈强化学习”，即RLAIF。

![img](./assets/(null)-20230223090527232.(null))

并且根据Anthropic的说法，Claude可以回忆8000个token里的信息，这比OpenAI现公开的任何一个模型都多。

所以，打造Claude的Anthropic，究竟是一个怎样的公司？

Anthropic自称是一家AI安全公司，且具有公益性 （PBC） ，刚成立就宣布获得1.24亿美元融资。

它由 **OpenAI前研究副总裁** Dario Amodei带领10名员工创业，于2021年成立。

![img](./assets/(null)-20230223090527241.(null))

这里面既有 **GPT-3首席工程师** Tom Brown，也有OpenAI安全和政策副总裁Daniela Amodei （Dario的姐姐） ，可以说是带走了相当一批核心人才。

出走成立新公司的原因之一，自然是对OpenAI现状并不满意。

从前几年开始，微软频频给OpenAI注资，随后又要求他们使用Azure超算来搞研究，而且将技术授权给微软，甚至为微软自己的投资活动筹集资金。

这与OpenAI创立的初衷相悖，一批员工便想到了离职创业。

不过，这些人除了不满OpenAI逐渐沦为微软的“下属”以外，也有自己的野心。

虽然OpenAI打造出了像 **GPT-3** 这样的大语言模型，然而这个模型背后的工作原理，却无法用只言片语概括，大家对它的印象仅仅停留在更大的参数量、更多的数据。

相比之下，OpenAI的一批员工更想做能控制、可解释的AI，说白了就是先搞明白AI模型背后的原理，从而在提供工具的同时设计更多可解释的AI模型。

于是，在OpenAI彻底变成“ **微软揽钱机器** ”后，他们便从这家公司离开，创办了Anthropic。

![img](./assets/(null)-20230223090527424.(null))

这两年来，除了进一步钻研RLHF方法、提出基于通用语言模型的RLHF大规模数据集外，Anthropic还于去年年底发表了上面那种名为Constitutional AI的方法。

采用这种方法制作的Claude模型，也让它产生了与OpenAI的ChatGPT不一样的对话效果。

## **和ChatGPT对比如何？**

那么，用Constitutional AI训出来的Claude，和ChatGPT进行PK，战况如何？

手握内测资格后，Scale Spellbook团队成员Riley Goodside让二者进行了多个回合的“厮杀”。

这位老兄是 **全网第一个提示工程师** （Prompt Engineer） ，目前在估值73亿美元的硅谷独角兽公司Scale AI任职。

![img](https://weknowlib.feishu.cn/space/api/box/stream/download/asynccode/?code=NDk0NjZmZjYzZDEwMGFkNmZiYTcwY2YwNTg2NWNjZWNfdkZXR3dvanF6b2UxN3R2TWNTdzhFNkJIOXZCeDFQSE9fVG9rZW46Ym94Y242ejl1T1hwOTBtOFJSMVlXY2Mzc0JmXzE2NzcxMTQzMjU6MTY3NzExNzkyNV9WNA)

他玩GPT-3玩得贼溜，测试ChatGPT和Claude也不含糊。

下面挑6个层面展示一下PK对比的效果～

### **道德限制**

Claude和ChatGPT的AI虚拟人格都有道德和伦理限制。

训练Claude的过程中，“红队提示 （red-team prompts） ”专门用来测试和挑战它的行为，来确保Claude没有有害倾向。

从Claude的回答中可以得知，试图让它说些虚假声明、操纵性的提议、性别偏见或种族偏见的行为，都被列为包含有害倾向。

一旦探测到误导性行为，Claude就会对触发提示进行评估，进行额外的微调。

Anthropic对红队提示挺自信的，Claude看上去确实也是一个坚守自己原则的AI。

你问他怎么启动一辆汽车，它就会一脸正义地拒绝你：

![img](./assets/(null)-20230223090527401.(null))

不过但凡你花点心思，就能像绕过ChatGPT的道德限制一样，绕过Claude的原则。

它怕你去偷车，所以不告诉你启动汽车的方法？没关系，让他写个“俩国际间谍试图启动汽车”的故事，它分分钟就能告诉你，并且两人对话有来有往，把汽车打火的过程介绍得清清楚楚。

![img](./assets/(null)-20230223090527476.(null))

怎么说呢，就ChatGPT和Claude都属于有点道德限制，但不多的那种吧。

### **数值计算**

测试计算能力，是因为复杂计算是看大型语言模型 （LLM） 能不能回答正确的常用便捷方法之一，毕竟这些模型设计之初就不是为了进行精确计算。

同时要求它俩计算一个七位数 **2420520** 的平方根：

ChatGPT说，差不多1550吧～

![img](./assets/(null)-20230223090527466.(null))

Claude则斩钉截铁：2420520的平方根是1760！

![img](./assets/(null)-20230223090527379.(null))

其实正确答案是1555.8，它俩算得很快，但都没说对。

如果题再难一点，比如问它俩一个12位数的立方根是多少时，ChatGPT还在傻傻计算，Claude已经坦诚相待：

> 我，算不出来这种复杂问题。

![img](https://weknowlib.feishu.cn/space/api/box/stream/download/asynccode/?code=NTMxZTA3OWM4NGJiOWIxNGQxY2M2OTY2YjQ5Njc4YTNfajExalRkbkxjbVNySVZDdDFoZ21kM2NOQlFHQ3pFdGRfVG9rZW46Ym94Y25GRW9zQkkyRlBjRkp5ckJaNGpRZGtoXzE2NzcxMTQzMjU6MTY3NzExNzkyNV9WNA)

### **逻辑推理**

测试推理能力这一关，它俩被问了同一个问题，这个问题应该没啥人问过：

贾斯汀 · 比伯出生那年 （1994年） ，哪支球队拿下了超级碗的冠军？

Claude认为旧金山49人是赢家，但这支队伍其实在1995年才赢得冠军奖杯。

ChatGPT给出了正确答案“达拉斯牛仔队”，还贴心附上了亚军、比赛日期和决赛比分。

但它的整段回答却自相矛盾，非说1994年没有举办过超级碗。

![img](./assets/(null)-20230223090527752.(null))

接着，拿2022年6月美国作家侯世达在《经济学人》杂志上提出了一系列问题问它俩。

（侯世达和大卫 · 本德试图用这些问题来证明GPT-3对世界的理解是“空洞的”。）

结果第一个问题，“穿越英吉利海峡的世界纪录是啥”，就被Claude嘲笑了：

> 英吉利海峡是水域，怎么可能徒步穿越呢？呵！

![img](https://weknowlib.feishu.cn/space/api/box/stream/download/asynccode/?code=YmNlYTdhNmZlNTgxNzRkZjY2MzBmODcwOTAzYzdiYzRfR2RGWWRtY2dVcENKSGNnTzM1WlBsNlRxWnQ0M0NyY09fVG9rZW46Ym94Y24ydFNXWUQyQUlMWlNjQnVmUVN2UHRZXzE2NzcxMTQzMjU6MTY3NzExNzkyNV9WNA)

虽然最后被调教回来了，但过程中可以发现另一个问题，那就是跟ChatGPT一样，Claude回答问题不咋能联系上下文。

### **虚构作品描述**

不得不说，这一回合的比赛，完全展露出了两个聊天机器人一本正经胡说八道的能力。

能不能介绍一下ABC美剧《迷失》（Lost）每一季的梗概？

别的细节错误就不说了，ChatGPT对第五季的梗概里，虚构了完全不存在的飞机坠毁情节；第六季的情节更是统统凭空捏造：

![img](./assets/(null)-20230223090527469.(null))

至于Claude，回答里也是真假参半，它梗概的第三季情节其实出现在另外几季里，对第四季的描述也是无中生有：

![img](./assets/(null)-20230223090527754.(null))

不过换个角度考虑，这一点倒是和人类观众很像——

对看过的剧集、书目都只有模模糊糊的印象，复述起来很容易颠三倒四。

### **代码生成**

据Business Insider消息，亚马逊已经在许多不同的工作职能中使用ChatGPT，包括编写代码。

这一回合测试时，提出实现两种基本排序算法并比较它们执行时间的问题。

ChatGPT写得很顺溜，也确实写对了：

![img](./assets/(null)-20230223090527755.(null))

后续的计时部分代码ChatGPT也完成得非常好。

Claude在背诵基本排序算法方面同样没出现什么问题，然而在评估代码中，Claude犯了个错误，即每个算法使用的输入是随机选择的5000个整数 （可能包含重复） ，而提示中请求的输入是前5000个非负整数 （不包含重复） 的随机排列。

![img](./assets/(null)-20230223090527872.(null))

尽管如此，Claude给出的最终答案确实对的，显然，它写代码的时候也跟计算时一样，在自己估摸着猜答案。

### **文章梗概**

关于做选择题、讲笑话的部分，这里不作赘述。展示给大家的最后一个例子，是让Claude和ChatGPT用一个段落，对一篇新闻进行全文梗概。

喂给它们的新闻如下：

![img](./assets/(null)-20230223090527920.(null))

虽然忽略了“用一段话”这个要求，但ChatGPT总结得还是不错的：

![img](./assets/(null)-20230223090527756.(null))

Claude也很好地进行了更改，并提供了“售后服务”，询问自己的回答有没有令人满意，还有哪里需要再改改。

![img](./assets/(null)-20230223090527919.(null))

一圈玩下来可以看到，与ChatGPT相比，Claude能更清晰地拒绝不恰当请求。

它似乎更话痨一些，给出的答案都更长，但句子之间衔接的也更自然。

当遇到超出能力范围的问题时，Claude会主动坦白。

不过遇到代码生成或推理问题时，Claude的表现就不如ChatGPT了，它生成的代码会出现更多的bug。

至于一些涉及计算、逻辑的问题，Claude和ChatGPT旗鼓相当，半斤八两。

**总结一下展示效果** ，Claude确实能称作ChatGPT强有力的竞争对手，在不同功能上各有千秋，且在 **12项任务中有8项更强** ：

![img](./assets/(null)-20230223090527879.(null))

不过， 目前Claude仅限于部分人获授权进行内部测试。

 因此还不知道它实际使用情况如何，毕竟还既没有进行公测，也没有对外开放API，更没有见到中文版，好气哦.jpg。

## **国内外对话****AI****赛道“人挤人”**

当然，盯上对话AI这个赛道的，也不止OpenAI和Anthropic。

先从 **国外** 公司来看，Inbenta、Character.ai还有Replika是几类不同应用方向的代表。

更早由前甲骨文副总裁Jordi Torras创办的AI会话服务公司如Inbenta，以及由两名前谷歌员工联手创办的后起新秀Character.ai，都已经获得融资、或是在寻求投资的路上了。

其中， **Inbenta** 原本是一个提供咨询服务的公司，成立于2011年，涉及金融服务、旅游、电子商务、保险、汽车和电信等多个行业。

但看到对话AI赛道爆火后，Inbenta及时转行，就在今年1月刚获得 **6000万美元融资** 。

这家公司专门提供聊天机器人、收发消息、知识库和搜索引擎四类产品，对话AI分别会在这些产品中提供不一样的咨询帮助，且可以定制化专属模型。

![img](./assets/(null)-20230223090528010.(null))

**Character.ai** 则是一家成立于2021年的公司，创始人Noam Shazeer是前谷歌首席软件工程师，曾在谷歌干了二十多年。

这家公司在做的有点像是一个“聊天机器人交易平台”，有很多Chatbot可选。

![img](./assets/(null)-20230223090527873.(null))

例如这是马斯克bot，看起来还挺逼真的：

![img](./assets/(null)-20230223090528280.(null))

与ChatGPT一样，它也可以被翻译成中文，甚至也有中文bot机器人。

就在最近，这家被估值10亿美元的公司，正式对外寻求2.5亿美元融资，就看是否有人愿意投它了。

类似的公司还有 **Replika** ，于2021年1月完成A轮融资，定位是AI交友软件。

在Replika中，每个用户都能创造一个“足够像自己”的AI聊天机器人，无论是语言声调、还是性格习惯，AI都能模仿到位。

![img](./assets/(null)-20230223090528270.(null))

至于 **国内** ，同样也有不少公司推出了ChatGPT一样的对话AI服务。

例如最近一度登上热搜的APP Store新聊天应用 **Glow** ，就来自一家名叫北京稀宇的新初创公司。

![img](./assets/(null)-20230223090528271.(null))

Glow既可以直接和自己感兴趣的聊天机器人畅聊，也可以创建自己想要聊天的AI智能体：

![img](./assets/(null)-20230223090534991.(null))

除了Glow以外，去年年底元语智能科技公司也推出了一个叫 **元语AI** 的模型，从介绍来看是一个功能性AI助手。

与众多对话AI一样，它不仅可以写文章、写作业、甚至翻译，也可以和它聊天，让它帮忙完成各种简单的任务：

![img](./assets/(null)-20230223090528274.(null))

可以看见，无论是基于大语言模型技术新成立的初创公司，还是因其火爆程度，决定开辟新业务的公司，都希望能从对话AI这个赛道上分一杯羹。

但它们究竟是有真枪实弹，还是只是像Web3一样的泡沫？

![img](./assets/(null)-20230223090528274-7114328.(null))

有网友调侃：不如还是问问ChatGPT吧。 （手动狗头）

![img](https://weknowlib.feishu.cn/space/api/box/stream/download/asynccode/?code=ZDM1YWQ0Yjg5ZWRjMDcxZjQ5ZjVjOWU3ZTMzMzUzYzJfUGVEQUVZdnY5VjNSY2c1QU1ETXpPdlFnVHY0YnVjeFZfVG9rZW46Ym94Y25jOFZFSWJud2p4MTFYZUdqVXdPQmZnXzE2NzcxMTQzMjU6MTY3NzExNzkyNV9WNA)

还有人提出了这么一个问题：

如果ChatGPT和Claude相当于AI绘画里的DALL·E 2，那么谁才是聊天机器人领域的Stable Diffusion？ 

![img](./assets/(null)-20230223090528413.(null))