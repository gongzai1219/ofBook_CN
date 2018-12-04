# 前言

*作者 [Zach Lieberman](http://thesystemis.com)*


openFrameworks始于2004/2005年左右。我在Parsons设计学院任教的同时，以艺术家为生，用代码创造互动作品。

我几年前从2002年届的大学毕业了，当我还在大学时，我们使用Director/Lingo和Flash等计算工具——这是闪光实验的全盛时期。2002年，我的教授Golan Levin邀请我在学校毕业后与他合作完成一些项目，他把我介绍给了ACU，这是一个由麻省理工学院的美学与计算团队开发的C++库，这个团队是由John Maeda管理的，有像Elise Co，Peter Cho，Ben Fry，Casey Reas和Golan这样的学生。

ACU作为一个库是很棒，但它太过适用于90年代后期的技术，如SGI机器。它既不是开源的，也没有人积极维护。很多人像Ben Fry一样，偶然转向了开发Processing，并且，它似乎无法满足我们的长期工作。看起来，我们需要一个可替代的代码库。

另外，我真的想和我的学生分享我在专业实践中写的代码。 我清楚地记得与部门的管理在Parsons进行了交谈，他们说：“艺术系学生不想学习C++”。我在2005年开始用oF上课，我有像Theo Watson，Christine Sugrue和Evan Roth这样的学生，他们用oF创造了非常疯狂的、实验性的作品，这让那个论点迅速崩溃。C++提供了对计算机的低级访问，用于计算机视觉，声音处理，硬件访问以及访问其他人编写的各种库。 它为计算的表现用途打开了大门。

我曾经2005年的学生Theo Watson加入了oF团队，帮助制作OS X版本。在早期，我们通过一个神秘的“加入邮件列表”前端页面将openFrameworks上线，Theo和我将生成一个带有oF文档的静态HTML页面。当时不是完全公开的，但是我们有了一小群愿意贡献的人开始使用oF。我不能完全确定我们的第一次正式发布时间，但我清楚地记得在2006年的OFFF节上我们将还在测试阶段的openFrameworks展示给了大家，我们在Hangar举办了一个高级的processing研讨会。该研讨会的参与者之一Arturo Castro加入了oF团队，帮助制作Linux版本。一大群使用oF并对其作出贡献的人加入了Theo、Arturo和我。

我认为关于代码和任何工具最重要的事情之一就是快乐，我无法表达我与Theo和Arturo一起工作的乐趣，开玩笑说奇怪的操作系统属性，为了弄清楚棘手的问题而深夜打Skype电话。我认为oF的优点之一是它吸引了真正关心，乐于助人的人，他们喜欢制作并分享他们学到的东西。

2008年，我们在Ars Electronica获得了一个奖项，并建立了一个名为oF lab的实验室，这个实验室让原本远程工作的我们可以面对面，大部分是第一次见面。这是许多帮助发展了社区的全球会议，实验室，研讨会和开发者大会中的第一个。那一年，我们还在日本YCAM举办了一个oF研讨会，发现了一整个社区来自世界各地的人在使用这个工具。它比我们想象的更加全球化。它令人振奋的同时，也让人感到可怕，我们意思到全世界都有人在用这个工具来谋生。

我们有幸能在这些活动中与非常棒的机构合作，比如，The Studio for Creative Inquiry、V&A museum、YCAM、Imal、Ars Electronica 和 Eyebeam，这些机构帮助赞助活动将oF社区聚集在一起。

近年来，我们一直试图帮助发展和扩大社区——像Kyle McDonald这样的人帮助组织了开发人员的各种利益并保持一切关注，而Caitlin Morris已经制作了详细的社区调查。 Greg Borenstein和James George帮助推出了ofxAddons.com，这是一个在线存储库，可以帮助分类社区每天创建的大量插件。 此外，现在有致力于oF发展的部门领导者们，他们帮助发展代码库的不同部分，并帮助计划oF的发展。最终，有无数的oF贡献者帮助维护代码库、文档、示例、插件，以及回答论坛上的问题。

最重要的是，编程有可能会是一项不太友好的活动，从某种程度上来说是孤独的，但是我们已经尽可能地努力创造一种友好的编程氛围。我们传播将艺术创作作为实验室，作为人类研发的理念，为了建立一个我们可以共同成长和共享实验的大型实验室，oF是一个尝试。 如今，DIY（自己动手）文化已经发生了巨大变化，比如Make Magazine和Instructables通过制作来促进分享文化。我们是DIWO（与其他人合作）的忠实粉丝，并尽可能地线上和线下都做到。不知何故，很幸运地，我们吸引了一些最令人惊讶的、乐于助人的、热心的、可爱的人来参与到其中，如果你还没有，我们想说 **欢迎**。

## 关于此书

本书非常本着openFrameworks的精神，它是一个社区驱动的事情，它是 **一项正在进行中的工作**。这是对openFrameworks开发者邮件列表的一个建议，该列表将这剔除了，在过去的几个月里，我们一直在抨击此事。

几个注意点,

* 我们十分欢迎反馈，我们想知道此书缺少了什么，或者你想要在此书中获得什么。同样，如果你发现有用的东西，我们也很乐意听到它！我们的github仓库处于活跃状态，我们会处理问题和提取请求。
* 请注意，此书可能存在空白部分。我们试图按照技能水平粗略地列出章节，但由于它是一本集体写的书，它可能会让人觉得有点迷失方向，有些章节是长篇的，有些则是短篇。你可以把它想象成从前到后阅读的书，但它更像是社区的一些简短教程。

*除非另有说明，否则每一章都是许可的: [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/deed.en_US)*

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>


## 感谢

非常感谢Rachel Uwa组织这个项目，Tega Brain帮助编辑它，Ishac Bertran和Andy Clymer指导设计，Arturo Castro，Christoph Buchner和Michael Hadley开发用于此书的代码库。 此外，以下作者和编辑为本书做出了贡献：Rui Pereira, Arturo Castro, Brannon Dorsey, Zach Lieberman, Kayla Lewis, Josh Nimoy, Phoenix Perry, Jane Friedhoff, Caitlin Morris, Pierre Proske, Golan Levin, Blair Neal, Michael Hadley, Abraham Avnisan, Christopher Baker, Lukasz Karluk, Omer Shapira, Mimi Son & Elliot Woods (Kimchi and Chips), Eva Schindling, Pierre Thirion, Joel Gethin Lewis, Roy Macdonald, Adam Carlucci, Christoph Buchner, tpltnt以及无数其他提供反馈，提交合并申请和提供建议等的人们。

我认为如果openFrameworks（通常是开源的）体现了一个座右铭，那就是：

*同心协力，我们可以获得更多*
