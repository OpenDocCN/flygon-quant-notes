# P23：3-Ricequant交易平台简介 - 人工智能博士 - BV1aP411z7sz

这里啊咱们先给大家演示一下，就是这个量化平台啊，它的一个使用方法，首先呢咱们点一下就是量化平台，然后进去之后有一个免费使用，我们来点一下，在这个免费使用当中啊，就是进去之后它会有一些策略，相当于啊啊。

就是这个平台人家已经给你写好的呃，一些简单的一个demo，方便你要自己来去熟悉一下，就是这些策略唉大概是怎么去写，然后呢这样这里有一个诶这个名字不是我起的，就是它默认会带的，咱们点进来看一下。

这里有一个第一个入门策略。

![](img/95cd91441859620e0defa6e1c8f6ade9_1.png)

点开之后啊，它这个东西诶，给大家感觉好像是像是那个notebook是吧，在这里我们可以写一些Python代码，但是呢它是有一点要求的啊，我们所有的操作你看这一块给大家列出来什么，首先我们可以看到这里啊。

咱们有三个函数是吧，第一个，然后还有这个，第二个，还有第三个，这三个函数啊，不是我该写的是默认都会要去用的啊，不是我指定的是这个平台，人家要求你啊，就是所有操作你都需要围绕着哎最少吧，围绕着这三个函数。

咱们来一步一步去实现的，我给大家先解释一下，就是这三个函数都什么意思，先来看一下第一函数，这样啊，第一个函数它是一个int的函数，他的意思啊就是做一个初始化诶，那咱们写那个Python的时候。

哎我们Python里边是不是有一个类啊，在类当中我可以定义一个构造函数吧，勾函数当中啊，一般都是这样诶，你传建一些参数，然后我对这些参数诶就是做一些负责操作呀，然后做一些其他基本操作。

哎这个经典的函数就相当于在Python当中啊，我们写的一个构造函数啊，是一样的，那咱们既然说它是一个构造函数诶，那你说你想去在Python里边实例化出来一个对象，那是不是得先走一遍它的一个构造函数啊。

这里它是一样的，就是所有的操作当中，哎不管你下面写了多么复杂的操作，不管你写什么东西，首先当你去执行的时候，引领的函数会先被调用啊，在这里它是会最先被调用的，然后呢被调用了诶，那你说调用里吧。

它还有一个参数，什么意思啊，这个参数啊是这样，就是咱们观察一下，你看啊就是在我们三个函数当中都有诶，有一些共同的参数吧，都有context这个东西，那它是什么意思啊，他表示啊就是你要全局当中啊。

经常比如说初始化当中诶，我用到一些对象，然后呢接下来预处理的时候我也要用到，然后实际数值精算的时候，我也要用到在这不同的方法当中啊，我要进行一个传递，唉比如说初始化当中唉。

你说你在这个权益对象当中做一些什么操作，或者说指定一些哎咱们股票的代码，然后获取一些股票数据是不是都行啊，好了都存入到当前我们的一个全局对象当中，然后呢接下来接下来预处理，那你说预处理的时候啊。

我也想去处理一下啊，咱们之前指定好的一些就是股票，或者是一些股票的一些数据之类的，那是不是，之前咱们已经存到了我的一个全局变量当中啊，好了这里我说再把它传进来，它们之间是可以进行相互的一个调用的啊。

相当于这个函数哎，不是这个函数这个参数帮助我们来去调用啊，一些算法策略，做一个船D的一个工作，比如这里这样，你看这话我写了一个S1啊，等于什么什么什么一个代码是吧，然后接下来呢我说哎呀在其他地方。

那我也想用到，那怎么办呢，比如说在预处理的时候哦，我说预处理的时候我要用到，那我可以直接怎么样把count组，这把当前这个context参数，是不是直接拿过来数就行了，你看这块有个点点的意思啊。

就是说啊你自己给他指定好一个名字就行了，然后接下来呢我们调用的时候也是一样，也是点二诶，当前你指定好的一个名字，或者说指定好的一个变量就行了，context啊，它主要是帮我们做一个传递的。

在这里咱们说完了，哎我们的第一块，第一块呢一个音量函数啊，相当于就是一开始的时候诶，它会被先被执行的，然后呢我们再来往下看，这一块还有这样一个事儿，这一块就是下面两个是这样一件事儿，呃，这个初始化啊。

它是一开始的时候被执行那么一次，然后呢，接下来接下来我现在，况且这个东西它不是会被执行一次，是会被执行很多很多次，那什么例子呢，就给大家举个例子吧，比如这样，我说啊现在在我蓝色这个框当中，唉。

一个音频函数当中，我说我先去啊，选择了一个股票啊，就在这里我就什么都不干了，就选了一个股票，那选这个股票是不是就定下来了，以后我就不需要了吧，好了，这是int函数当中，我说我就选了一个股票，然后呢。

接下来接下来就是这个红色框，那你说我的策略啊，是不是得对这个股票当中啊做一些操作呀，那咱们经常是不是说我也对股票，每一天我都要知道他的一些收盘价，每一天我可能都要做一些判断。

还是我是买呀还是卖还是怎么样的是吧，所以说此时啊有这样一件事，你每一天重复的都要去做一件事，我们想到哪了，写到这个红色的框当中，我先在红色框里边有两个函数，第一个函数在训练之前怎么样会被诶。

不是在我们的一个交易之前会被执行的，以及呢这个HDB每一天都会去执行的。

![](img/95cd91441859620e0defa6e1c8f6ade9_3.png)

它是什么意思呢，给我们感觉像是这样，每一天说起来之后，哎如果说你想对这个数据啊，就是在这个呃他实际比如说做买卖之前，你想做一些处理的操作，你可以写到当前啊，我们做这个trading之前。

before trading之前啊，先来去执行一下啊，相当于你就当做是数据预处理就好了，然后接下来呢，这点我们是不是实际要去判断一下我们的策略，或者说在这一块实际的去写诶，咱们的策略以及基于策略。

我要下单。

![](img/95cd91441859620e0defa6e1c8f6ade9_5.png)

我要买什么东西，我要执行后续的操作吧，所以这个相当于这样一件事啊，就是before training啊，相当于就是你的预处理啊，但是预处理每一一天都会去做的，注意点啊，我刚一定强调了这个淡蓝色框里边的。

每一天都会去做，憨豆瓣里边也是一样，憨豆瓣里边相当于就是我们算法，或者说我们的一个策略实际的一个逻辑啊，实际它具体的一些判断也好，然后操作也好，都是在汉豆瓣当中，咱去执行的那行了，简单给大家先介绍了啊。

有这么三个函数，大家简单这样就行啊，就是一开始咱们简练就行，后期给大家举个例子啊，今天函数啊做初始化的，比before trading啊，做一些预处理的，然后憨豆怕做实际我们的一个策略，来实际买卖的。

那刚才既然咱们提到一点哦，诶好像你说每天的你都要去做这样一个操作，那每天这个事儿怎么体现出来啊，你看右边一块当中啊，这个也非常重要，你需要选择就是咱们的几个参数，这几个参数。

而不是这右边我先框选这个东西，它不是你的一个结果，是需要你自己去选的，你既然诶或者说咱们既然要干什么，做一个回测吧，就是看看我们策略在历史数据当中怎么样，你是不是得把这个股票或者说你当前哎。

比如说我就指定的这个代码，这个股票你得把他的一些时间找出来，或者说把他的历史数据找出来啊，你要告诉我，你回撤的一个时间是从哪儿到哪儿吧，好了，这是一个起止日期，后面呢是一个终止日期啊。

从哪儿到哪儿这样一个时间段，然后这里还有这样，这是什么，你看这块我写了一个啊10万10万这样一个事啊，就是你做这个策略啊，那你是不是一开始手里有钱啊，让你这个钱，然后来买卖买卖买卖怎么样了。

做一些交易之后啊，反正每一天可能都做，做完之后大概过了几年，然后现在我要看我的一个回测收益率，还是不要看这样一个指标啊，那这个就是我们的一个初始资金了，注意这点，这个是我们初始资金你自己去写啊。

具体你的一个实验当中诶，或者你的策略当中，你想准备的一个初始资金，然后呢第三个这一块还有一个每日和每分钟，每日啊，就是说啊我每天啊做HDBAR当中做一个处理，然后呢每分钟那就是每分钟执行这样一个操作。

相当于啊就是我们啊每分钟去执行，还是每天去执行，这个都需要你自己啊来指定出来，咱们利用当中啊，就按照每天啊来去做就行了，实际任务当中啊，你看你的需求吧，但是它只有两种，要么是一个每天。

要么是一个每分钟啊，如果说你想指定一些其他的统计值，那这个代码当中啊，就是所有跟pandas相关的，你看这块他也说了，这个片段当中啊，你可以自己去导入啊，导入什么，你现在是pandas的男排。

你给自己导入吧，咱之前是不是讲了pandas as np怎么去做呀，那你倒进来是不是也能做计算啊，而且就你看这一块啊，呃这个我们用人界的一个API，相当于用人家很多接口啊，帮我们去做。

它的接口也是基于安排panda去做的，给你得到的一些返回值，也是一个data frame，或者是一个enda real，所以说啊就是人家API和pandas安排啊，或者是其他的像sk learn之类的。

都是能唉咱们结合在一起来一起去用的，不是说这底盘你就只能用人家API，不能去用别的，相当于这里，而是既能用咱们拍子那期啊，常用的也能用人家API啊，重点是他们支架会有这样一个结合。

这个给大家先简单的说了一下，就是在咱们这个介绍当中，有三个非常重要的函数，然后呢，以及右边你需要指定好当前我们要用哪个参数，然后才能去得到当前的结果，这些指标啊咱们之前都说过了吧，就是一些基本的啊。

咱们的一个啊策略，还有风险。

![](img/95cd91441859620e0defa6e1c8f6ade9_7.png)