### 小说章节详情接口

1、接口地址：/catalog

2、参数

| 参数名 | 参数类型 | 是否必填 | 备注 |
| :--- | :--- | :--- | :--- |
| catalogId | int | 是 | 章节id |
| bookId | int | 是 | 小说id |
| num | int | 是 | 章节序号 |

3、接口返回结构

```js
data: {
    "book":小说的基本信息,
    "catalog":本章节的基本信息,
    "nextCatalog":下一个章节的基本信息,
    "lastCatalog":上一个章节的基本信息,
    "container": 本章节的内容

}
```

4、接口返回例子

```js
{
    "code":1000,
    "data":{
        "book":{
            "id":1102,
            "name":"《漂亮女医生的风雨爱情》",
            "author":"蓝箐",
            "description":"    三个女人，三朵花。一个热情如火，敢爱敢恨；一个文静温柔，善解人意；一个开朗洒脱，与众不同。这是发生在上个世纪九十年代的一段悲欢离合的爱情故事。她们从走出校门的那一天起，就注定今后的生活道路不可能是一帆风顺的。因为是临时工被人欺负，被人刁难，被世俗的眼光所不容，甚至因此失去工作和爱情。面对着这些突如其来的打击，她们迷茫过、退缩过，但是最终她们还是重新振作起来，毅然选择走上了一条艰苦的创业之路。在这条充满风风雨雨的艰难创业道路上，她们还能重新收获自己的爱情吗？\n",
            "originUrl":"http://www.biquge.com.tw/15_15234/",
            "imgUrl":"http://www.biquge.com.tw/files/article/image/15/15234/15234s.jpg",
            "type":3,
            "updateTime":"2017-12-31T16:00:00.000Z",
            "bookStatus":2,
            "bookType":"都市小说",
            "reptileType":1,
            "isJin":1
        },
        "catalog":{
            "id":12794,
            "bookId":1102,
            "name":"第1章女自费生的烦恼",
            "num":0,
            "type":1,
            "createTime":"2018-05-01T06:57:18.000Z",
            "updateTime":"2018-05-01T06:57:18.000Z",
            "isJin":2,
            "isReptileTool":2,
            "reptileAddress":null
        },
        "nextCatalog":{
            "id":12795,
            "bookId":1102,
            "name":"第2章多情善感的女孩",
            "num":2,
            "type":1,
            "createTime":"2018-05-01T06:57:18.000Z",
            "updateTime":"2018-05-01T06:57:18.000Z",
            "isJin":2,
            "isReptileTool":2,
            "reptileAddress":null
        },
        "container":"<p>燕北油田是石油部下属的一个管理局，是我国著名的几大油田之一。二十多年来，经过几代来自全国各地的献身油田建设的油田人的艰苦创业，把燕北油田从曾经寸草不生的盐碱荒地，变成了如今楼房林立，繁荣富足的石油城。<br /><br />在这个美丽富饶的城市里有一所部属卫校，&ldquo;燕北石油卫生学校&rdquo;，是附属于燕北油田职工总医院的。设有医士、检验、护理三个专业，这所学校由于地处繁华的闹市区所以占地面积不是很大。<br /><br />如果你细心观察就会看到从这个学校出入的百分之九十多都是女生。她们一个个打扮的花枝招展，她们都是初中毕业就上了卫校，所以年岁都不大，十六、七岁，她们都是那么活泼、开朗、无忧无虑。所以这个学校虽然不大，但是整个校园特别干净，整洁，到处充满欢声笑语。<br /><br />此刻正是放学的时候，忙碌了一天的女孩们终于解放了，她们三一群、二一伙的，叽叽喳喳地说笑着从校园里走出来。在这些欢笑的人群里，你很容易发现一位与其他人不一样的姑娘，她很沉静，显得很忧郁，仿佛有满腹的心事。<br /><br />她叫余心雨，在这个学校整整生活二年了，她所在的班是&ldquo;燕北石油卫校&rdquo;唯一由高中毕业生组成的班级。她们这班的学生不仅年岁比其它班的学生大几岁，而且也是这所学校唯一特殊的班级，和其它班级有着本质的差别。<br /><br />那就是因为她们都是自费生，毕业之后国家是不包分配的。毕业之后其它班的学生就可以顺顺利利的、堂堂正正的走上工作岗位，而她们却没有这么幸运，毕业之后她们还得继续奋斗寻找工作。所以她们这班学生少了其它班学生的无忧无虑，却多了几分淡淡的愁绪和对未来前途的忧虑。<br /><br />记得二年前余心雨高考落榜，她曾经痛苦过、消沉过。但是最终她还是振作起来，她不甘心就此随随便便地找个工作，在家乡的小县城里平静地渡过一生。于是她在父母的支持下报考了自费学校，她想到外面广大的世界去闯一闯，成功了那当然是她所希望的，即使失败了她也不后悔。<br /><br />这一年即一九八八年正好是国家在全国范围内大批招收自费生的第一年，最后她被&ldquo;燕北石油卫生学校&rdquo;录取了，是医士专业。这就意味着将来毕业之后她将成为一名医生，这是她从来没想过的职业。她的理想是将来能成为一名服装设计师，用自己的双手来美化生活，把人们打扮的多姿多彩。<br /><br />但是随着高考的失败，她这一美好的理想也成了泡影，她也曾经偷偷地流过伤心的眼泪，这一切能愿谁呢？还不是愿自己没能考上大学。如今两年的时光已经过去了，她已经从卫校毕业了，明天她就将离开这个学校了，走向另一个完全陌生的地方。<br /><br />此刻她随着放学的人群出了学校大门，独自一个人走在&ldquo;创业大道&rdquo;上默默地想着心事。<br /><br />&ldquo;创业大道&rdquo;你一定觉得这是一个很俗气的名字，其实不然，这个名字有着非同一般的意义。它是燕北石油人为了纪念&ldquo;大会战期间&rdquo;人们艰苦创业的功绩而起的。它贯穿着整个燕北油田的东西方向，是&ldquo;燕北油田&rdquo;的象征，也是&ldquo;燕北油田&rdquo;最宽阔，景色最美的一条主街道。<br /><br />九月的天气还是那么炎热，喧闹了一天的城市现在开始静了下来。落日的余辉染红了半边天，给城市的街道、建筑仿佛镀上了一层金边，似梦、似幻、煞是好看。&ldquo;创业大道&rdquo;两旁被修剪成各种造型的松柏还是那么茂盛，一片片的草坪还是那么翠绿，圆形的、八角形的花坛里开满了五颜六色的鲜花。人行道两旁高大的榕树长的枝叶繁茂，挺拔茂盛。<br /><br />此刻人们吃完了晚饭都出来散步、乘凉，那些小商贩们不失时机地在道路两旁搭起了凉棚，卖起了冷饮。围绕着凉棚的彩灯不时地散放出五彩缤纷的光芒，伴随着从棚子里飘出来的轻柔的音乐，给那些棚子底下坐在白色圆桌、白色藤椅周围的一对对情侣和一个个三口之家的人们，增加了一种神秘和浪漫的气氛。所以每到这时来这里喝冷饮的人很多，生意很兴隆。<br /><br />看看他们想想自己，余心雨心里总觉着是那么苦涩。昨天在他们班毕业生的欢送会上，他们班的班主任兼学校学生处主任李有德宣布了分配名单。结果她被分到了采油一厂，和她分配在一起的还有宋美男、李雪、张燕和陶大伟。说是分配事实上并不是分配而是推荐，因为自费生国家不包分配。<br /><br />虽然今年国家规定自费的大专生给分配，但对她们这些自费的中专生国家却没有什么政策，给分还是不给分根本涉及不到她们。所以她们上了班以后也只是临时工，将来能否转正也不知道。现在就是到哪个地方去上班也还是个未知数，厂部卫生所肯定留不下，一定得去下面的大队，她不得不为自己的前途和命运担忧着。<br /><br />想想过去上高中的时候为能否考上大学担忧，上了这个卫校以后又为将来毕业之后能否找到工作担忧，而现在有了工作又为将来能否转正担忧。小小的岁数就背上了一个沉重的包袱。她在心里一遍一遍地问自己，难道这就是我选择的人生道路吗？为什么要有这么多的艰难，这么多的烦恼，难道我选的这条路真是错了。每当想到这些她心里总有一丝丝的惆怅。<br /><br />&ldquo;心雨、心雨，等等我&rdquo;。<br /><br />有人叫她，她回头一看是她的好朋友江玉屏。</p>"
    },
    "msg":""
}
```



