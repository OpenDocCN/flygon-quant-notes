# P179：4-决策树graphviz安装与可视化 - 程序大本营 - BV1KL411z7WA

来各位小伙伴，刚才那我们使用mat plot lib，对我们的决策树进行了一个可视化，各位小伙伴，你就能够看到这个就是我们的决策树，那我们就能够发现，咱们的决策树是一个标准的二叉树，对不对。

决策树的可视化还有另外一种方式，那么另外一种方式呢，咱们使用的是graph vr z，使用这个画出来的决策树，它更加的漂亮和美观，我给你看一下啊，你看这个就是咱们使用graph vz画出来的。

你看它可以设置圆角，更加的这个漂亮，丝润圆滑，那这个该如何操作呢，首先咱们得需要安装一下它的教程，那我们把这个链接打开，你看这个就是我写的这个博客啊，那我们安装相应的软件。

首先咱们要安装咱们的python库，大家看啊，叫pip install graph v i z，你在命令行安装一下就可以了，光安装它还不够，那么它呢得需要相应的软件和它配合，那我们装c make。

现在你就能够看到，我把下载的链接是不是都给你放到这儿了，好那你点这个，那我们就可以进入到c mac的下载链接，那你在c mac下载链接，这是吧，该怎么找呢，找见你windows 64位是吧。

如果你要是mac，那你就找mac的，那我们windows 64位，咱们就选择这个c make相应的版本就行了，后缀是msi，这个msi呢它其实就是e x e，也是一个可执行的文件，好安装好。

这个下载好之后呢，咱们就进行安装，安装的过程当中，大家只需要在这个出现这一步导航的时候，我们把环境变量添加一下就可以了，你看你只需要做这个就行了啊，把这个勾选上之后，一路下一步就搞定了。

这第一步就完成了，接下来我们再来看，还得需要安装一下graph v a z，那这个该如何安装呢，同样是不是有相应的这个下载页面呀，看你进入下载页面，或者说你直接下载地址。

你直接点这个软件就对应着这个下载地址，现在呢我进入这个下载页面给你看一下啊，唉咱们点继续啊，你看这也是一样的啊，咱们进入这个下载页面之后，那我们呢就找到windows所对应的版本。

现在咱们看刷新出来了吗，刷新出来了，第一个是linux，是不是啊，我们往下滑看，找见windows了吧，这第一个就是咱们的e x e，把它下载下来就可以了，下载下来双击是不是就可以安装，安装的过程当中。

同样咱们把环境变量这个勾给他勾上，然后呢你就一路下一步就可以了，这个是咱们软件的安装和配置，接下来我们看一下他该如何使用啊，回到咱们的代码当中，现在的话咱们在这儿给它添加一个标题，好。

那这个呢依然是三级标题，这个呢就是咱们的可视化，二来现在的话那我们就导一下包，此时呢咱们就import graph vz把这个导进来，然后呢使用train，train呢是sk learn当中的模块。

里边有一个方法叫export graph v a z，这个呢就是导出咱们决策树当中的数据，那我们导哪个决策树呢，model放进去，那就是m o d e l这个model就是咱们的模型。

然后呢我们给一个field field就表示颜色填充，现在呢咱们接收一下这个就是咱们的数据，叫做dot data，dot它有节点的意思，data就是数据的意思，现在呢我我们把这个节点数据。

使用咱们的graph vz，咱们把它变成一个这个图形，那graph vz来一个source，咱们就将上面的dot data放进去，那我们就接收一下graph g r a p h，现在你看就有一个图形了。

我们显示一下这个图形，此时你看过一执行来，各位小伙伴，你能够看到咱们这个数据是不是就有了呀，那我们这个参数当中呢还可以有更多的设置，run，我们来一个true，这个时候就是圆角。

现在你就能够看到它的四个角，是不是就圆滑了呀，滋润了，是不是湿润圆滑，有弹性，然后接下来呢我们再来逗号，咱们呢再给一个feature names，这个feature names就是它的这个特征。

就是你这个x一是什么样的特征呢，咱们把这个特征我们给一下啊，好那咱们的数据是不是上面的x呀，对不对，你看执行一下，那特征都是什么日志密度，好友密度，那现在的话咱们获取一下它的这个特征好。

那这个时候呢就是x点，column c o l u m n s执行一下，现在你发现看原来是不是x一啊，现在你看就变成了什么，是不是好友密度呀，这个时候我们就更加清晰啊。

好然后呢逗号咱们还可以给一个class name，那这个class name其实就是它的这个嗯这个类别，那我们的类别分哪两个呢，咱们给一个y给一个np。uni q，uni q呢就是去重，咱把y放进去。

这个时候大家仔细观察啊，你看我一运行，大家看这个class这个地方是不是就给了个y，给了个n呀，那这个y它表示什么呀，这个y y是不是就是表示，咱们的这个账号是真实账号，n是不是就表示这个账号是嗯。

是这个虚假账号呀，哎大家看这个图形是不是就有了，那图形有了之后，接下来呢我们再进行一个操作啊，咱们可以把这个图形呢给他保存一下，那这个时候呢就是graph，咱们来一个点调用方法render。

这个时候呢咱们就来一个小括号，那我们把它保存一下，咱们来一个点儿反斜杠，哎这个时候呢咱们给它起个名啊，叫j叫做j r a p h叫做graph图片，然后呢逗号咱们可以给它格式叫format。

就是保存图片，我们可以给png，是不是还可以给jpg呀，咱们还可以给pdf，现在咱们给一个png这种形式，那我执行这个代码，你看我一运行，现在这张图片是不是就保存成功了呀，咱们现在回到当前路径下来。

现在你能不能看到咱们刚刚保存的这个graph，图片呀，我们打开看一下哈，来各位小伙伴，你发现这张图片这怎么给乱码了呀，那这个是不是中文呀对吧，那他为啥乱码了，那肯定是咱们的编码是不是有问题。

咱们修改编码是不是就可以了，这是一个思路啊，好那么我们除了存了这个graph图片，我们是不是还存了一个graph呀，看到了吧，是还存了一个graph，这个是不是没有后缀，他是不是也是几秒钟之前存的。

那这个是什么，咱们打开看一看，来各位小伙伴你就能够看到这个是什么，是不是一个文本文件，对不对，我们在进行数据保存的时候，各位你就能够发现，你看嗯咱们使用tr export graph v i z。

这个是不是将咱们的数据导出，我们这个数据是不是叫做dot data，这个dot呢它有节点的意思，那这些节点它是以怎样的形式表现的呀，你看咱们打开这个txt这个文件。

你就能够发现看这个地方是不是有一个level，好友密度小于等于0。5，是不是好，那么在这个文本文件当中，我们就发现这个地方是不是有一个font name，这个font name是不是就是字体。

它这个字体不是咱们的中文字体，所以我们保存的这个图片，那中文呢就没有很好的显示，那现在怎么办，来咱们回到代码当中，咱们去修改一下中文乱码，咱们呢再来一个三级标题，哎这个呢就是修改咱们的中文乱码。

这个也很简单好，那么现在的话我们文本文件当中的数据不匹配，那我们导入r e这个呢就是咱们的正则表达式，然后呢咱们将这个文件呢给他open一下，那来一个open，那就是点反斜杠。

咱们找见graph图片这个文件，然后呢我们给他读出来数据，咱们给一个encoding编码，那就是ut f8 ，好，现在这个文件咱们就加载进来了，那我们的文件操作永远是有了打开必须得关闭，所以说咱们忘了。

我们把这个文件关闭，咱们先给它关闭，然后在开和关之间，咱们呢对它进行相应的操作，那我们是不是要把这个数据给它读出来呀，对不对呀，那这个时候呢咱们就读出这个数据吧，那我们就调用f。read。

你看这个数据是不是就读出来了，读出来之后咱们用s来表示啊，这个就是咱们的文本，那我们对这个文本进行什么样的操作呢，那这个时候就是r一点儿，咱们sub r e呢是这个正则表达式，sub就有替换的意思。

咱们替换谁呢，替换s s当中的数据，那我们要把它当中的什么数据找出来呀，那就是fault name，我们让它等于多少来，咱们回到这个文件当中，你看是不是就是他选中复制一下，回到代码当中。

咱们在这儿来一个粘贴，那要把它替换替换成什么样呀，中间是咱们要替换的数据，那就是fault name，这这个时候呢咱们就给一个仿宋啊，来一个仿宋好，那么这个时候咱们就替换了，好，那么替换的时候呢。

我们前面给一个r就是字符串，前面给一个r，是不是就是表示它是这个正则表达式的意思呀，好那么你看这个文件就替换了，那这个文件替换了之后，咱们接收一下，依然把把它叫做s2 。

现在呢我们需要将s2 保存到一个文件当中，这个时候呢就是打开一个文件with open，打开哪个文件呢，咱们先给他一个文件，这个时候咱们就来一个graph图片二唉，往这个文件当中去怎么样写东西。

来一个w，然后呢我们给一个编码encoding，我们让它是ut f8 as as as咱们的fire，那有了它之后呢，现在咱们就像file当中，我们去write写东西是不是就可以了呀。

咱们就将这个s2 替换之后的这个数据写进去，那这个with open咱们是不是这个代码执行结束，这个文件是不是会自动的帮我们关闭啊，咱们就不需要关闭了，来此时咱们执行这个代码，代码执行了。

那看一下我们当前路径下，是不是就多了一个graph 2图片呀，看到了吧，graph图片二来咱们打开这个图片嗯，好现在你就能够发现这个font name，是不是就变成了放送了，好那变成了这个之后呢。

和原来的是不是就不一样了，看到了吧，和原来的就不一样，来现在咱们在代码当中，我们把这个数据呢再用graph va z，我们去给它显示一下好不好，那这个时候呢咱们就使用graph va z。source。

然后点调用它的from five，我们修改之后的这个文件，是不是就是graph图片二呀，对不对，好，那么来咱们接收一下啊，这个时候来一个graph，你看这个graph在咱们这个网页当中显示的时候。

它呢是没问题的，看到了吗，他是没问题的，哎现在你看咱们出现了一个错，couldn't find放送，那这个是怎么回事呢，是因为我们放送后面这个s应该也是大写，咱们这个地方给了个小写。

现在呢我们把它调整过来哈，叫做仿啊，这个这个o呢啊我们应该写成a是吧，咱们来一个放送啊，这个时候这个宋到底是大写小写，咱们验证一下啊，来再来执行一下上面的代码运行好，那么这个文件又被覆盖了。

咱们重新再来执行，这个时候一执行，大家现在就能够看到这个字体，和刚才是不是就不一样呀，看到了吧，和刚才不一样，刚才长什么样，我给你看一下，看到了刚才这个字体是不是就呃这个黑一点呀，看到了吧，粗一点。

是不是，你看现在这个仿宋是不是轻描淡写的，这种感觉就有了哎，这个时候说明咱们的字体就写写对了啊，刚才不小心给写错了哈，看刚才写成什么了，是不是fg是吧，犯了一个低级的错误啊，好所以我们代码一报错。

咱们是不是就把它改过来了，好那么在在咱们这个网页当中，在咱们代码当中我们显示是没问题的，对不对呀，你看上面他不是这个它它是咱们的非中文字体，我们在代码当中显示也没问题，但是我们什么时候出问题了。

保存图片的时候出问题了，现在呢我们把字体给它调整成仿宋了，咱们保存一下图片，我们看一下还有没有问题，这个时候呢咱们就调render来一个小括号，来一个点反斜杠。

那这个时候呢咱们给一个这个graph graph图片二，然后呢format我们给它调整一下，那这个format呢就是p n g来，咱们执行这个代码，此时你看我一运行保存成功了，回到咱们目录下。

咱们就看一下graph 2这张图片，看看到底怎么样来，现在你就能够看到看好友密度是吧啊，成功了吧，原来我们看原来咱们graph图，原来咱们的这个graph图片，你看它怎么样。

它是不是咱们的这个中文乱码了，现在你看这张图片没问题了吧，好那么我们保存的png，咱们所看到的这个图片呢，它不太清楚是吧，咱们说了，保存图片的时候，咱们是不是可以给相应的格式来。

咱们给一个jpg执行一下这个代码好，那么当前路径下就多了个jpg，看到了吧，是不是来打开这个图片看一下，这是jpg的形式，那除了这种之外，咱们还可以给什么，还可以给pdf来，咱们执行这个代码，好。

pdf格式咱们就保存成功了，看当前路径下是不是就多了一个graph，图片二pdf呀。

![](img/49b8763ca4a7b32ccd0aeebe5e779bb1_1.png)

我们打开这个哎，现在你就能够发现，你看使用pdf这个效果是不是要稍微好一点啊，咱放大一些是不是更清楚呀，所以说咱们的graph v a z保存的时候。



![](img/49b8763ca4a7b32ccd0aeebe5e779bb1_3.png)

那我们就选择pdf这种格式，咱们保存的图片呢就非常清楚了，好到现在为止，我呢为各位小伙伴演示了，咱们啊决策树可视化的第二种方式是吧，就是咱们的graph va z，大家要记着你的电脑上。

如果想要使用graph va z，首先你得需要安装相应的库，对不对，咱们的教程就在这里，这个呢是我呃写的相应的这个博客，非常清楚明白，你呢按照这个安装流程把它安装一下，然后呢重启你的命令行，知道吗。

安装之后呢，你把这个命令行关闭掉，然后重新打开，这个时候呢你再进入咱们的主parator notebook，你就可以使用这个简单的代码，使用这个简单的代码进行相应图形的绘制了。

它画出来这个图形是很漂亮美观的，好，这个就是咱们呃决策树的可视化的第二种方式。

![](img/49b8763ca4a7b32ccd0aeebe5e779bb1_5.png)