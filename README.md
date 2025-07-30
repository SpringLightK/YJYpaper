# YJYpaper
本仓库专门用来记录武汉大学国际经济贸易专业杨景媛的硕士毕业论文《中印生育行为影响家庭暴力的经济学分析》中存在的问题。  

原论文在[这里](./paper/%E4%B8%AD%E5%8D%B0%E7%94%9F%E8%82%B2%E8%A1%8C%E4%B8%BA%E5%BD%B1%E5%93%8D%E5%AE%B6%E5%BA%AD%E6%9A%B4%E5%8A%9B%E7%9A%84%E7%BB%8F%E6%B5%8E%E5%AD%A6%E5%88%86%E6%9E%90.pdf) 欢迎各位评论并列举更多的错误。
## TODO
- [x] 收集存在问题
- [ ] 向武汉大学举报
- [ ] 在教育部科研诚信管理信息系统举报
- [ ] 向湖北省教育厅举报

## 主要问题
### 涉嫌造假
1. 内容编造(p2)：  
第二页第五行内容：“而在 2001 年随着《离婚法》的出台
与宣传”
我国并未颁布《离婚法》，此为杜撰内容。
2. 疑似编造数据(p14)：
第十四页的图2.1 全球各国家暴发生率直方图，纵坐标为频数，频数是怎么求出非整数的？
![plt](./pic/plt.jpeg)
### 数据错误
1. 年份错误(p4)：  
第四页第七行内容：“新中国成立之后，由于社会经济的逐渐稳定与发展，全国总人口从 1049 年之前的 5.42 亿增长到 1970 年的 8.30 亿。”  
我国于1949年成立，并非1049年，这属于严重的**政治错误**。
### 数据分析错误
1. 常识性分析错误(p21)：  
第一段倒数三行内容，如下图所示，0.01% 应为10000位女性中有一位。  
![idiot](./pic/img2.jpg)
2. 分析错误(p25)：   
第二十五页倒数第六行内容：“本文用各地区人均道观数据衡量该地区思想传统程度”  
道教属于宗教范畴，不同地区的宗教分布不一致，故人均道观数跟当地思想传统程度无直接关系。
3. 强行拟合(p26)：  
如图所示，图中的点散度过大，无明显线性关系。其中同为观念传统地区且生育率相近的甘肃和福建的家暴跨度过大，可说明该线不适合证明观念与家暴之间的关系。 
![idiot](./pic/img.jpeg) 

### 格式与规范错误
1. 格式错误(p1)：
第一页第二段第二行内容：“即有 27%的女性一生中至少遭受过一次来自丈夫或男性亲密伴侣的身体和/或性暴力侵害”  
没有必要使用“和/或”，直接使用或也能表达和的意思。

### 术语/词汇使用不规范

1. 术语使用不一致

1.1. 关于“家庭暴力”相关术语混用：
- “家庭暴力”“家暴”混用，缺乏术语的一致性，并且缺乏定义。
- 例如在论文 (p6) 中，如下图所示，“家庭暴力”和“家暴”交替出现，缺乏统一性：

  ![术语混用示例](./pic/term_issues/jiatingbaoli_sample.png)

1.2. 关于“女性”相关术语不一致：
- 全文频繁切换使用“女性”“妇女”“妻子”等术语，缺乏统一性。
- 例如在论文 (p8) 中，如下图所示，“女性”“妇女”“妻子”三个术语指代同一对象，却频繁切换使用：

  ![女性术语混用示例](./pic/term_issues/nvxing_sample.png)

1.3. 关于“男性”相关术语不一致：
- “丈夫”“亲密伴侣”术语使用混乱。
- 例如在论文 (p1, p14) 中，如 p1 所示，作者使用“丈夫或男性亲密伴侣”这一并列表达，表明“丈夫”并不等同于“亲密伴侣”；而 p14 中引用的数据则以“亲密伴侣”作为统计对象，未限定是否为婚姻关系中的配偶。此处术语含义已与“丈夫”脱节。然而，论文后文却以“丈夫”作为通篇分析的主体对象，试图据此探讨所谓“配偶造成的家庭暴力”问题，存在术语偷换与逻辑跳跃，属于严重的术语使用不规范，直接导致后续论证失去有效支撑。

  ![亲密伴侣术语示例1](./pic/term_issues/nanxing_sample1.png)  
  ![亲密伴侣术语示例2](./pic/term_issues/nanxing_sample2.png)


### 涉嫌抄袭剽窃

### 写作与表达错误
1. 摘要翻译错误：  
中文关键词：生育；家庭暴力；母职惩罚；社会规范
英文关键词：Fertility；Domestic Violence；Outside Option；Social Norm  
“母职惩罚”和“Outside Option”无法对应。
![en_abstract](./pic/zhaiyao.jpeg)
2. 摘要翻译问题：  
原文英文关键词那一行写着：“关键词：Fertility；Domestic Violence；Outside Option；Social Norm”  
其中**关键词**三个字未翻译为英文keyword。  
3. 错别字(p4)：  
第四页第一行内容：“伴随 90 年带股市房市大泡沫破
裂”  
此处应为“年代”而不是“年带”。
4. 疑似错误字符(p8)：
第八页 关于家庭暴力的其他文献 中的第六行内容：“例如，g 通过越南的数据发现”  
这个g指代不明，疑似错写字符。
5. 写错时间(p15)：
第十五页第一段第四行内容：“与 1960 年 -1665 之间的剧烈增长形成明显对比”  
疑似将1965写为1665。
6. 错别字及错误字符(p41)：
第四十一页的表格疑似将“7.”写成了“x7.”，将“被迫”写成了“被破”。
![table](./pic/tab.jpeg)
### 学术伦理问题
1. 该文章阐述家庭暴力与生育、传统文化、宗教、女性就业之间的关联，在数据拟合度低的情况下强行将家暴与文化、宗教捆绑，该课题可能涉及较为严重的学术伦理问题。
### 文献引用错误
1. 疑似为了降重修改标题(p63)：  
[46] Cesur R, Sabia J J. When War Comes Home: The Impact of Combat Service on Domestic Violence[J]. Review of Economics and Statistics, 2016, 98(2): 209-225.  
我查到的题目是 When War Comes Home: The effect of Combat Service on Domestic Violence
2. 完全重复(p64)：  
[59] Dugan L, Nagin D S, Rosenfeld R. Explaining the Decline in Intimate Partner Homicide: The 
Effects of Changing Domesticity, Women's Status, and Domestic Violence Resources[J]. Homicide Studies, 1999, 3(3): 187-214.  
[60] Dugan L, Nagin D S, Rosenfeld R. Explaining the Decline in Intimate Partner Homicide: The 
Effects of Changing Domesticity, Women's Status, and Domestic Violence Resources[J]. 
Homicide Studies, 1999, 3(3): 187-214.
3. 完全重复(p66)：  
[101]Tauchen H V, Witte A D, Long S K. Domestic Violence: A Nonrandom Affair[J]. International   
Economic Review, 1991, 32(2): 491.  
[102]Tauchen H, Witte A, Long S. Domestic Violence - a Nonrandom Affair[J]. International 
Economic Review, 1991, 32(2): 491-511.
