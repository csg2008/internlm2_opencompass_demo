---
name: ceval-xyj
desc: 西游记剧情评测数据集
language:
  - cn
dimension:
  - examination
sub_dimension:
  - text
website: https://github.com/csg2008/
github: https://github.com/csg2008/internlm2_opencompass_demo.git
paper: https://github.com/csg2008/InternLMAgricultureAssistant/blob/main/note/lesson7.md
release_date: 2024-4-22
tags:
  - text
  - reasoning
download_url: https://github.com/csg2008/internlm2_opencompass_demo/archive/refs/heads/master.zip
cn:
  name: ceval-xyj
  desc: 基于西游记剧情的问答评测数据集
---

## Introduction
西游记主要讲述了孙悟空出世，跟随菩提祖师学艺及大闹天宫后，遇见了唐僧、猪八戒、沙僧和白龙马，西行取经，一路上历经艰险，降妖除魔，经历了九九八十一难，终于到达西天见到如来佛祖，最终五圣成真的故事。该小说以“玄奘取经”这一历史事件为蓝本，经作者的艺术加工，深刻地描绘出明代百姓的社会生活状况。

## Meta Data
西游记剧情问题数测试数据集包含以下内容

- Question: 问题主体
- A, B, C, D: 模型可以选择的回答选项
- Answer: 正确答案
- Explanation: 问题正确解答分析

## Example
```
Question: 唐僧的姓名是____
A. 江流儿
B. 李白
C. 白居易
D. 李世民
Answer: A

Question: 猢狲是谁的外号____
A. 唐僧
B. 孙悟空
C. 猪八戒
D. 沙和尚
Answer: B
```

## Citation
none

### what
东胜神洲傲来国海边有一花果山，山顶一石，受日月精华，产下一个石猴。石猴勇探瀑布飞泉，发现水帘洞，被众猴奉为“美猴王”。猴王领群猴在山中自由自在数百载，偶闻仙、佛、神圣三者可躲过轮回，与天地山川齐寿，遂独自乘筏泛海，历南赡部洲，至西牛贺洲，终在灵台方寸山斜月三星洞，为菩提祖师收留，赐其法名孙悟空。悟空在三星洞悟彻菩提妙理，学到七十二般变化和筋斗云之术后返回花果山，一举灭妖魔混世魔王，花果山狼、虫、虎、豹等七十二洞妖王都来奉其为尊。

孙悟空占山为王，号为美猴王。苦于无兵刃，遂去东海龙宫求取，东海龙王敖广及其兄弟送给他一支如意金箍棒及一身披挂。又与牛魔王、蛟魔王、鹏魔王、狮驼王、猕猴王、禺狨王等结为兄弟，日逐讲文论武，弦歌欢舞。一日被阴司按勾去，遂大闹幽冥，于生死簿上勾去所有猴属之名。龙王、地藏王上天庭告状，太白金星建议招安孙悟空，玉帝准奏。

玉帝封孙悟空做“弼马温”，着他看管马匹。孙悟空后得知此官职卑微，大怒，打出南天门，回花果山，自封为“齐天大圣”，其他几个兄弟也分别自称了平天大圣、覆海大圣、混天大圣、移山大圣、通风大圣、驱神大圣。

托塔天王李靖及哪吒三太子奉旨兴师捉拿孙悟空，被孙悟空打败，回天庭复旨。太白金星奏请玉帝降旨封孙悟空为齐天大圣，但不给他事务与俸禄。玉帝准奏。孙悟空应太白金星之邀，再入天宫。玉帝封其为齐天大圣，并赐予他齐天大圣府。孙悟空在天上无事，每日交朋结义，不论尊卑。玉帝怕他闲中生事，让其看管蟠桃园。王母举办蟠桃盛会，孙悟空怪王母未请其赶会，竟闯至会上，饱吃仙酒佳肴，又至兜率宫，吃尽金丹；搅乱蟠桃会后，逃回花果山后，玉帝派十万天兵擒拿，未胜。

观音菩萨推荐二郎神助战。悟空和二郎各显神通：多般变化，难分胜负；老君掷金钢琢打倒悟空，哮天犬咬住悟空方被擒。玉帝令天神将其处死，刀砍枪刺，雷击火燃，孙悟空却毫发无损。太上老君将其关入八卦炉，孙悟空不但不死，还炼就一双火眼金睛。四十九天后，悟空推翻八卦炉，舞金箍棒，乱天宫。诸天将不能敌，玉帝只得请来西天佛祖。如来法力无边，悟空无法跳出其手心，被压于五行山下，饮餐铁丸、渴饮铜汁度日。

五百年后，如来因南赡部洲之人贪淫乐祸，多杀多争，令观音菩萨去东土觅一人，来西天取经，以普渡众生，并赐箍儿三个作降妖用。观世音菩萨携木叉行者往东土寻取经人，路上收服两个妖魔：一个原为灵霄殿下侍銮舆的卷帘大将，因失手打破玻璃盏，被玉帝贬在流沙河受苦；一个本是天河里的天蓬元帅，因带酒戏嫦娥，被打下凡尘投胎为猪形，在福陵山云栈洞为妖。观音替他们取法名沙悟净和猪悟能，叫他们等取经人来，保护取经人西去。观音又请玉帝饶恕犯法的西海龙王之子，将其送于深涧中，只等取经人来，为取经人作个脚力。

行至五行山，被压在山下的孙悟空表示愿意悔过，观音也令其等唐国取经人来，“你可跟他做个徒弟，秉教伽持，入我佛门，再修正果”。

唐太宗开科取士，青年陈光蕊高中状元，又娶相府殷小姐为妻。之后，官拜江州州主。陈光蕊携妻赴任，路上，被贼人刘洪谋害，妻子被占。陈之妻殷氏产下一子，抛入江中，被金山寺寺僧搭救。此子十八年后受戒，法名玄奘。玄奘终与母亲相见，又求见外祖父，报了血仇。

长安泾河边有一渔二樵叙说城中有神卦，按卦打鱼，百下百着，恰被巡水夜叉听见，转报龙王。龙王即变秀士询问雨情。卜者所答恰与玉旨相合，龙王为赌胜，错行雨，当斩，龙王求卜者搭救卜者嘱龙王进宫求助唐王。唐太宗梦中允龙王之请，第二日退朝后留魏征对弈，以拖过午时三刻。不料魏征午时睡着，梦斩泾河龙。龙王在冥间告唐王，冥王拘唐王三曹对案。判官受魏征所托，私改生死簿，唐太宗还阳，派刘全地府进瓜果，又因在地府见冤魂无数，遂决定建水陆大道场，选一名有德行的高僧主持法会。众臣举洪福寺和尚陈玄奘。玄奘前身是如来弟子金蝉，因无心听讲，被贬凡尘，从小经历种种磨难。观音到长安，与木叉变成癫头和尚，献袈裟、锡杖于唐王，使唐王赐与玄奘。又于法会上现身，指示西天有“大乘佛法三藏”，可度亡脱苦，消无妄之灾。玄奘因向唐王请命去西天取经。唐王与玄奘拜为兄弟，又命其指经取号，号作“三藏”，与文武百官送其西行。

三藏骑御赐白马，与两名侍者，一路出大唐西界，在双叉岭被老虎精变成的“寅将军”将其两名侍者食尽，三藏独得逃生，此为三藏取经初出长安第一难。前行遇猛虎、长蛇，为猎户刘伯钦所救。伯钦送三藏至两界山，猛听得山下有人大叫“我师傅来也！”原来此山就是五行山改名，山下压着五百年前大闹天宫的孙悟空。三藏揭去山顶如来金字压帖，悟空裂山跳出，拜三藏为师，被赐名孙行者。

路上，孙悟空打死六个强盗，不堪唐僧数落，一怒之下去了龙宫。唐僧接受观音赠送的用来钳制孙悟空的两件东西——嵌金花帽与紧箍咒。悟空听从龙王劝告，回到唐僧身边。在此间隙，观音赠三藏一领直裰、一顶花帽，又教他一篇“紧箍咒”。三藏哄悟空戴上花帽，一念紧箍咒，悟空痛得打滚，原来那花帽是如来所赐紧箍。悟空只得侍奉唐僧奔西而进。

二人至鹰愁涧，唐僧的白马被涧里玉龙吞下肚去。观音将玉龙变成白马，供三藏乘骑。

在观音院，悟空卖弄唐僧的锦襕袈裟，观音院长老金池长老心生贪念，欲火烧唐僧师徒，却被悟空弄法反烧了禅院。但袈裟反被金池长老之友黑风怪窃走。孙悟空求助观音，他设计让观音化作黑风怪的妖友，自己化作仙丹，诱黑风怪吞下，黑风怪降伏。

唐僧师徒继续西行，至高老庄，得知庄主女儿被一妖怪强占，悟空擒拿此妖，追至云栈洞。知妖怪原是天庭的天蓬元帅，因调戏嫦娥，被贬下界，错投猪胎，故形貌像猪。经观音收伏，赐名猪悟能，在此等候取经人。孙悟空引他拜见唐僧，唐僧收其为徒，唐僧因其自称断了“五荤三厌”，又替他起别号叫“八戒”。

过浮屠山，乌巢禅师传授唐僧《多心经》。

途经八百里黄风岭，唐僧被黄风怪摄入黄风洞。悟空到小须弥山请来灵吉菩萨收服黄风怪，原来此怪乃灵山下得道的黄毛貂鼠。

在流沙河，唐僧收被观音点化的沙悟净为三弟子，赐号沙和尚。师徒四人跋山涉水，往西天取经。

师徒四众渡河西行，遇观音、普贤、文殊菩萨和黎山老母变成一母三女试禅心。八戒凡心未退，被绑吊在树上。

经万寿山五庄观，悟空偷镇元子大仙“人参果”，又推倒人参果树，为大仙所困。悟空三岛求方，最后到南海请来观音，用手执净瓶中的甘露救活人参果树。

至白虎岭，尸魔欲害三藏，初变少女，次变老妇，三变公公，均被行者识破除之。由于八戒撺掇，三藏怪行者行凶，念紧箍咒，逐走行者。行者复回花果山为妖。三藏遇黄袍怪被捉。黄袍怪之妻为宝象国公主，搭救之。三藏至宝象国传信，国王遣八戒、沙僧降妖，反被黄袍怪所败。黄袍怪进宫诬陷三藏为白虎精。白龙马救师未果，嘱八戒去请行者。行者战败黄袍怪，后者原来是奎宿下凡。悟空救出师父，师徒言归于好。

过平顶山，三藏命八戒巡路。八戒初则偷懒睡觉，继则编谎骗师，均被行者识破。山中有金角、银角二妖，经行者恶斗收伏之，妖魔却是老君的二个看炉童子，由观音借来托化妖魔以试三藏师徒。

夜宿宝林寺，三藏夜遇乌鸡国王鬼魂诉冤。行者救活乌鸡国王，战败杀害国王并占据王位的妖魔，后者原来是文殊菩萨的坐骑，奉佛旨来报前仇。

抵号山，遇圣婴大王红孩儿，三藏遇难，行者、八戒等救师屡为妖败。红孩儿为行者早年的结拜兄弟牛魔王之子，行者变化为牛魔王进洞搭救三藏亦未果，为红孩儿三昧真火所败。最后得观音助解救之。观音收伏红孩儿，为善财童子。

过黑河，遇小鼍龙。三藏被困水底。行者请来龙王收伏之。

抵车迟国，遇虎力、鹿力、羊力三妖。行者、八戒、沙僧夜闹三清观；戏谑三妖。后在宫中与三妖斗法，赌求雨、猜枚，又赌砍头、剖腹、滚油锅，行者皆胜之，除却三妖。

经通天河，遇观音座前莲花池内成精为妖的金鱼，金鱼作法把唐僧摄入水府。观音赶来，收走金鱼。三藏得老鼋助渡过河。老鼋求三藏代问佛祖何时他可得人身。

过金兜山，遇独角兕大王，三藏被擒，行者几经恶斗，又请来各方神兵相助，均失利。后得如来指明，请来老君收伏之。原来妖精为老君坐骑青牛。

至西梁女国，三藏和八戒饮子母河水而怀孕，行者取落胎泉水解救之。女王欲招赘三藏，行者设计走脱之。但三藏又为毒敌山琵琶洞蝎子精所摄，行者请来昴宿灭之。又在途遇盗，行者除灭之。三藏怪行者杀人，逐之。行者无奈去求诉观音。时三藏遇假行者行凶，并抢走包袱。师徒们以为是行者所为，遣沙僧赶至花果山讨取未果，又赶到南海观音处，忽见行者又在彼，沙僧怒极，经观音说明才罢。行者寻至花果山与假行者恶斗。二行者直斗至如来处。如来说明假行者为六耳猕猴，并除灭之。

师徒路阻火焰山前。行者打听得有芭蕉扇可克服之，但扇在红孩儿之母、牛魔王之妻罗刹女处。行者赶至罗刹处，先是礼借，后是强索。罗刹因怪行者害红孩儿，只借给假扇。行者又至牛魔王小妾处找牛借，牛不允；行者盗得牛之坐骑，变作牛之模样，至罗刹处骗得芭蕉扇。但半路又被牛魔王赶上变做八戒模样而骗去。后来又借助神兵，与牛魔王恶斗，败之，索得扇子，灭火焰山火。

至祭赛国，行者为国王除灭盗宝之万圣龙王和九头驸马。

过荆棘岭，八戒挥钯开路。夜逢竹精树妖。三藏被摄，与妖精谈诗。后被八戒一顿钉钯筑翻妖树。

到小西天，遇黄眉大王。妖精善使搭包装人。行者请来各路神兵，均不敌。后得弥勒佛相助才降伏，原来妖精乃佛前司磐童儿。

经驼罗庄，行者和八戒杀蛇精，拯救了一庄老幼。

经稀柿衕，八戒变大猪拱开满山污路。

到朱紫国，行者为国王医病，又救回三年前为妖精赛太岁所劫的皇后金圣宫。赛太岁却是观音坐骑金毛狮，特来为国王消灾。

过盘丝岭，三藏遇蜘蛛精遭难，后者又唆使多目怪蜈蚣精来与三藏师徒作对。行者打死蜘蛛精，又请来毗蓝婆收伏多目怪。

至狮驼岭，遇青狮、白象、大鹏三魔，三藏遭灾；行者苦斗难胜，去西方求告佛祖。如来宣文殊、普贤降妖，原来狮、象乃二菩萨之坐骑，如来又迫使大鹏皈依。

比丘国王被寿星坐骑白鹿所化的国丈迷惑，欲用一千一百一十一个小儿心肝做药引，悟空解救婴儿，打退妖怪，寿星赶来收走白鹿怪。

三藏在松林救一女，却是妖精。师徒夜宿镇海寺，行者降妖，妖精摄走三藏至陷空山无底洞。行者请来哪吒相助，原来此妖乃李天王之义女老鼠精。

过灭法国，国王要杀一万和尚，正少四名。行者夜间剃尽皇宫内院、五省六部官员之发。迫使国王皈依秉善，并改国名为钦法。

隐雾山连环洞豹子精南山大王欲吃唐僧肉，被悟空用瞌睡虫睡倒，八戒将其打死。

经凤仙郡，孙行者见该郡三年未雨，灾情严重，盖因郡主当年推倒斋天素供所致，才劝归善，全郡念佛，感动天降甘霖。

抵玉华州，行者师兄弟三人收三个王子为徒传艺；仿造金箍棒等兵器。结果兵器为豹头山黄狮精所盗，黄狮精又求助其祖九灵元圣。行者知后者乃太乙救苦天尊坐骑，乃请太乙天尊降伏之。

过金平府，恰逢元宵节，三藏观灯被青龙曲妖精辟寒大王、辟暑大王、辟尘大王摄去，行者请来四木禽星降灭之，把妖怪斩首示众。

月宫玉兔化为天竺国公主抛绣球给唐僧，欲招之为婿。悟空会合太阴星君擒伏玉兔，救回真公主。

过铜台府地灵县，宿寇员外家，受优厚款待。后寇家被盗，寇员外被害。三藏师徒被诬。行者施法辨明之，又救寇员外还阳。

三藏师徒终于到达灵山，乘无底船过凌云仙渡，见如来求经。如来命阿傩、伽叶检经传与；阿傩、伽叶向三藏索人事不得，便将无字经本传给三藏。燃灯古佛便命白雄尊者去半路夺经，四众才知真相，返回告于如来。如来却说：经不可轻传。三藏把紫金钵盂送给阿傩，才发出真经五千零四十八卷。如来命八大金刚护送师徒回东土。观音查看三藏所经难簿，共八十难，便命揭谛赶上金刚，再生一难。时三藏等正坠落在通天河边，有老鼋来驮过河。老鼋因怪三藏未曾为他求问佛祖归着之事，便淬下水去，经卷遭水，残缺不全。终于完成了九九八十一难之数。金刚便将师徒们送至长安。

佛经送回长安，经一十四遍寒暑，太宗喜接得唐僧师徒，因作《圣教序》以彰唐僧之功。唐僧正在雁塔寺登台诵经，被金刚导引，师徒四人并白马复转灵山。四人真身重返灵山听封：三藏被封旃檀功德佛；悟空为斗战胜佛；八戒为净坛使者；沙僧为金身罗汉；白龙马为八部天龙，各归本位。孙悟空头上紧箍也自行消失。