## Design Thinking Fundamentals

On your first day working with any software system the architecture is always TBD—to be discovered. Whether we start from a blank page or must uncover structures in an existing software system, the architecture we need is out there, somewhere, waiting for us to discover it. To design a software system’s architecture we explore solutions at the same time we’re working to uncover the problem to be solved.

*从你第一天开发某个软件系统开始系统架构就是一直需要去学习的内容.不管我们是从零开始开发新系统还是需要去发现某个现存系统的结构,软件架构始终就在那儿等待着我们去发现它.我们总是在开发过程中一边解决遇到的问题一边设计软件架构.*

To help you perform this challenging task, you’ll learn a creative and analytical approach to problem solving that puts humans at the center of attention called design thinking. Focusing on the people affected by your design decisions helps you concentrate on the exact problems that must be solved. It also grounds your solution exploration by reminding you that your purpose is to build software that helps people.

*为了帮助你完成这项有挑战的任务,你需要学习一项有新意且基于分析的方法来解决问题,同时这种方法是把注意力都放在了用户身上,这种方法叫做设计思维.聚焦在用户身上的这种设计理念能帮助你把注意放在解决最紧急的问题上.同时也根据方案落地的效果来提醒你,软件最终是用来帮助用户的.*

In this chapter, you’ll learn how to apply design thinking to software architecture. You’ll start by learning the core principles of design thinking. Next, you’ll learn how to use different design mindsets to keep your architecture moving forward in (mostly) the right direction. Finally, you’ll see an approach for picking design mindsets.

*在本章中,你会学到怎样应用设计思维来思考软件架构.你会从学习几个核心的设计原则开始,然后学习怎样使用不同的设计思路来让你的架构尽量保持在正确的方向上演进.最后你会看到能帮助你选择设计思路的方法.*

### The Four Principles of Design Thinking

Design thinking is less a process and more a way of thinking about problems and solutions from the perspective of the people affected by them. While design thinking is not a process, there are still rules to guide our design activities. In Design Thinking: Understand - Improve - Apply Christoph Meinel and Larry Leifer propose four universal principles of design. These principles apply to software architecture as well as to detailed program design, user interaction design, or any other design-focused discipline.

*设计思维更多的是从受众的角度出发来思考问题和解决方案而不仅仅是一种流程.虽然设计思维不是一种流程,但是依然有指引我们的设计工作的规则,那就是理解 - 优化 - 实施, Christoph Meinel和Larry Leifer提出了四个统一的设计原则,这些原则同时适用于软件架构和具体的编程设计和用户交互设计,或者其他任何以设计为主的过程.*

Here are the four principles of design:

*下面就是这四个设计原则:*

1. Human rule.
All design is social in nature.

*1. 以人为本
所有的设计都是自然界中的社交行为*

2. Ambiguity rule.
Preserve ambiguity.

*2.歧义规则
避免歧义*

3. Redesign rule.
All design is redesign.

*3.再设计规则
所有的设计都是再设计*

4. Tangibility rule.
Make ideas tangible to facilitate communication.

*4.有形性规则
将想法转化为可见的实体更有助于交流*

We’ll use the acronym HART to help remember these principles. Let’s examine the HART principles as they relate to software architecture design so we can see how to apply design thinking in the context of software architecture.

*我们会使用HART的缩写来帮助记忆这些原则,我们先在软件架构领域来检验HART原则,进一步来看怎样使用设计思维来进行软件架构设计.*

### Design for Humans

Design is an inherently human-focused endeavor. We design software for people. We design software with people. Every design decision in the architecture helps individuals in some way. Every design decision must be understood by and shared with other humans.

*设计是一种天生的为人服务的工作.我们为别人设计软件,同时我们和别人一起完成软件设计.软件架构中的每一个设计决策都帮助在某个方面帮助着每个人,每个设计决策都应该是易懂且易于被分享给别人理解的.*

Architects must empathize with all stakeholders. We care about end users as much as the people the end users help, the programmers who write the code, the testers who verify it, and even the managers who keep tabs on the development schedule. As we design a software system, we’ll collaborate with the other humans on our team and show them respect by listening, assuming positive intent, and using human-centered design methods.

*架构师必须考虑到所有参与者的感受,我们不仅关心软件用户同样也关心我们的用户的用户,程序员写代码,测试人员验证软件功能,甚至项目经理管理开放周期都是在做这件事.在设计软件系统的过程中我们和其他团队成员通过倾听对方,积极看待对方的想法以及本真以人为本的设计方法来充分合作.*

The Human rule also reminds us that architects are not separated from our teams. We work directly with them to design the architecture together. Building software is an intensely social activity. The idea of an ivory tower architect who designs the architecture isolated from the team is a myth. Software architects are an integral part of every team. Separating the architect from the team severs the human connection the architect shares with everyone touched by the architecture.

*以人为本的原则同样提醒我们架构师不是和团队分割开的,我们的直接和团队一起进行架构设计,创建软件是一件社交密集型的活动,那种呆在象牙塔里面和团队分开的架构师都是神奇的.软件架构师是每个团队中不可或缺的,将架构师和团队分离的行为会把架构师和所有试用软件架构的人之间的联系切断.*

Empathizing with the humans who directly and indirectly interact with the architecture makes us a better designer, communicator, and leader.

*感受那些直接或者间接参与架构设计的人们的行为让我们成为更好的设计者,交流者和领导者.*

### Preserve Ambiguity

Ambiguity in engineering is dangerous. Once we’ve made a design decision, we must share it with precision and clarity. Allowing requirements, design decisions, and commitments to remain ambiguous is the best way to destroy a project. Before we solidify a design decision, we can use ambiguity to keep options open.

*工程学中的歧义是很危险的事情,一旦我们确定了一个设计决定,我们就必须能清楚且精确的将它分享出来,容忍需求,设计或者技术承诺中存在模糊的歧义是摧毁项目最好的方式.当然在确定技术设计之前我们可以使用一些模糊的概念来更开放的引入更多的可能性.*

Since the goal of software architecture is to arrange structures that promote desired quality attributes, we’ll focus our attention there. In Less is more with minimalist architecture [MB02], Ruth Malan and Dana Bredemeyer suggest architects design a minimalist architecture. A minimalist architecture only shows how high-priority quality attributes are achieved and reduces risks for promoting those quality attributes. All other design decisions are left open for downstream designers to determine.

*因为软件架构个的目标是确保需要的质量属性能达到满足,我们当然会专注于此,在<<少即是多,更简洁的架构>>这本书中Ruth Malan和Dana Bredemeyer建议架构师应用遵循极简原则,一个极简的架构只反应如何满足高优先级的质量属性以及降低风险,其他设计决定让下游的设计者来完成.*

Architecture minimalism implies that we want to defer binding design decisions for as long as responsible. Design decisions that do not directly influence a quality attribute or reduce risks threatening our ability to deliver software are more about detailed design than architecture. Such decisions can safely be left open for downstream designers to settle outside the architecture. You’ll learn more about preserving ambiguity in ​Design for Change​.

*极简架构的理念是我们希望只要能有人负责就尽量延迟做技术决定的时间点,设计决定如果没有直接反应质量属性或者降低风险的话就会让我们的工作更多的是在做细节设计而不是架构.某些技术决定可以留给下游的设计者来在核心架构之外完成,你会在"基于变化的设计"这章学到更多关于保持模糊的知识.*

Preserving ambiguity allows us to deliver software even as the world around us changes.

*保持模糊可以让我们在交付软件时更加适应周围世界的变化.*

### Design Is Redesign

In A Pattern Language: Towns, Buildings, Construction [AISJ77], Christopher Alexander and others cataloged over 253 civil engineering problems with known good solutions. Topics ranged from construction materials to community organization techniques to building architectures. If you’ve ever enjoyed a perfect spring morning while sipping coffee at a sidewalk cafe, then you can thank Christopher Alexander for documenting the sidewalk cafe pattern as a community building solution.

*在<<模式语言:城镇,建筑,建设>>这本书中,Christopher Alexander和其他人总结了超过253种国内的工程问题以及对应的好的解决办法.其中涉及的话题从建筑材料到建筑架构到社区组织再到建筑架构.如果你曾经在一个美好的春天的清晨在人行道上喝着咖啡,那你就应该感谢Christopher Alexander制定了这种人行道咖啡模式作为一种社区的组织方式.*

The redesign rule encourages us to look to think about what we already know by exploring patterns and past designs. As time goes on and as we build more software, our institutional knowledge about how to design great software improves. Other teams have probably seen a problem similar to the one you face currently. Hopefully, someone documented a pattern you can use as a starting point for your architecture. Maybe someone built a framework designed to solve your exact problem?

*再次设计规则鼓励我们去思考我们已知的模式和过时的设计,伴随着时间的流逝,我们参与了更多软件的开发,我们对于如何开发伟大的软件的知识也在随之改进.其他团队也许也面临着和你相似的问题,但愿有人制定了一种模式能作为你的架构工作的开始的指导,也许有人创造了一个框架可以刚好解决你的问题呢?*

When designing software architectures, we’ll spend more time refining existing designs than we’ll be creating new ones. One of the least effective ways to design software architecture is to ignore the software systems that came before us.

*当做软件架构设计的时候,我们会花更多的时间来总结现存的设计以便创造新的设计,其中最低效的设计架构的方式就是不去参考已经存在的软件系统.*

