# 前言

*作者 [Zach Lieberman](http://thesystemis.com)*


openFrameworks始于2004/2005年左右。我在Parsons设计学院任教的同时，以艺术家为生，用代码创造互动作品。

我几年前从2002年届的大学毕业了，当我还在大学时，我们使用Director/Lingo和Flash等计算工具——这是闪光实验的全盛时期。2002年，我的教授Golan Levin邀请我在学校毕业后与他合作完成一些项目，他把我介绍给了ACU，这是一个由麻省理工学院的美学与计算团队开发的C++库，这个团队是由John Maeda管理的，有像Elise Co，Peter Cho，Ben Fry，Casey Reas和Golan这样的学生。

ACU作为一个库是很棒，但它太过适用于90年代后期的技术，如SGI机器。它既不是开源的，也没有人积极维护。很多人像Ben Fry一样，偶然转向了开发Processing，并且，它似乎无法满足我们的长期工作。看起来，我们需要一个可替代的代码库。

另外，我真的想和我的学生分享我在专业实践中写的代码。 我清楚地记得与部门的管理在Parsons进行了交谈，他们说：“艺术系学生不想学习C++”。我在2005年开始用oF上课，我有像Theo Watson，Christine Sugrue和Evan Roth这样的学生，他们用oF创造了非常疯狂的、实验性的作品，这让那个论点迅速崩溃。C++提供了对计算机的低级访问，用于计算机视觉，声音处理，硬件访问以及访问其他人编写的各种库。 它为计算的表现用途打开了大门。

我曾经2005年的学生Theo Watson加入了oF团队，帮助制作OS X版本。在早期，我们通过一个神秘的“加入邮件列表”前端页面将openFrameworks上线，Theo和我将生成一个带有oF文档的静态HTML页面。当时不是完全公开的，但是我们有了一小群愿意贡献的人开始使用oF。我不能完全确定我们的第一次正式发布时间，但我清楚地记得在2006年的OFFF节上我们将还在测试阶段的openFrameworks展示给了大家，我们在Hangar举办了一个高级的processing研讨会。该研讨会的参与者之一Arturo Castro加入了oF团队，帮助制作Linux版本。一大群使用oF并对其作出贡献的人加入了Theo、Arturo和我。

我认为关于代码和任何工具最重要的事情之一就是快乐，我无法表达我与Theo和Arturo一起工作的乐趣，开玩笑说奇怪的操作系统属性，为了弄清楚棘手的问题而深夜打Skype电话。我认为oF的优点之一是它吸引了真正关心，乐于助人的人，他们喜欢制作并分享他们学到的东西。

2008年，我们在Ars Electronica获得了一个奖项，并建立了一个名为oF lab的实验室，这个实验室让原本远程工作的我们可以面对面，大部分是第一次见面。这是许多帮助发展了社区的全球会议，实验室，研讨会和开发者大会中的第一个。那一年，我们还在日本YCAM举办了一个oF研讨会，发现了一整个社区来自世界各地的人在使用这个工具。它比我们想象的更加全球化。它令人振奋的同时，也让人感到可怕，我们意思到全世界都有人在用这个工具来谋生。

We've been lucky in these events to be able to work with great institutions such as The Studio for Creative Inquiry, V&A museum, YCAM, Imal, Ars Electronica and Eyebeam, which have helped sponsor events to bring the oF community together.

In recent years, we've tried to help grow and expand the community -- folks like Kyle McDonald have helped organize the diverse interests of developers and keep everything focused while Caitlin Morris has produced detailed surveys of the community.  Greg Borenstein and James George helped launch ofxAddons.com, an online repository which helps organize the impressive quantity of addons that the community is creating on a daily basis.  In addition, there are now section leaders for the development of oF, helping grow different parts of the codebase and helping imagine what modern oF looks like.  Finally, there are countless contributors to oF who help with the codebase, documentation, examples, addons and answering questions on the forum.

More than anything, we've tried as hard as we can to create a friendly atmosphere around programming, which can be an unfriendly activity and in some ways isolating.  We preach the idea of art-making as a laboratory, as R&D (Research & Development) for humanity, and oF is one attempt to make a large lab where we can grow and share experiments together.   There's been a big movement for DIY  (Do it Yourself) culture these days, things like Make Magazine and Instructables promoting a culture of sharing through making.  We are big fans of DIWO (Do it With Others) and try to do that as much as we can online and offline.  Somehow, luckily, we've attracted some of the most amazing, helpful, warm-hearted, lovely people to come be a part of this, and if you're not already, we'd like to say **welcome**.


## About This Book

This book, much in the spirit of openFrameworks, is a community driven affair and it's **very much a work in progress**.   It was a suggestion on the openFrameworks developers mailing list which kicked this off and for a the past months we've been hacking away on it.

A couple of notes,

* Feedback is very much appreciated and we'd like to know what's missing, or what you'd like to have in here.  Likewise, if you find something helpful, we'd love to hear it, too!  Our github repo is active and we take issues and pull requests.
* Please note that there are likely gaps here.  We've tried to roughly lay out chapters in order of skill level, but since it's a collectively written book, it can feel a bit disorienting, with some chapters being on the long side, while some are short.  Think of it not as a book you read front to back, but more like a collection of short tutorials from the community.

*Every chapter, unless noted, is licensed: [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/deed.en_US)*

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/deed.en_US"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>


## Credits

Countless thanks to Rachel Uwa for organizing this project, Tega Brain for helping edit it, Ishac Bertran and Andy Clymer for directing the design, and Arturo Castro, Christoph Buchner and Michael Hadley for developing the codebase for generating the book.   In addition, the following authors and editors have contributed to this book:  Rui Pereira, Arturo Castro, Brannon Dorsey, Zach Lieberman, Kayla Lewis, Josh Nimoy, Phoenix Perry, Jane Friedhoff, Caitlin Morris, Pierre Proske, Golan Levin, Blair Neal, Michael Hadley, Abraham Avnisan, Christopher Baker, Lukasz Karluk, Omer Shapira, Mimi Son & Elliot Woods (Kimchi and Chips), Eva Schindling, Pierre Thirion, Joel Gethin Lewis, Roy Macdonald, Adam Carlucci, Christoph Buchner, tpltnt as well as countless others who have given feedback, submitted pull requests, offered advice, etc.

I think if there's one motto that openFrameworks (and open source generally) embodies, it is:

*together we know more*
