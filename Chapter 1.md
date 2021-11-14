# Become a Software Architect

I’m not exactly sure when I became a software architect. I do remember the first time someone else called me one. We were at an important client meeting and someone asked a 
tough technical question. The project manager chimed in: “Michael is the architect on this project. He’ll dig in and send you an update by the end of the week.”

*我已经不记得我究竟是什么时候成为一名软件架构师的,但是我还记得第一次有人这样称呼我的时候.当时我们在和一个重要的客户开会,有人问了我一个困难的技术问题,然后项目经理说到:"Michael是我们项目的架构师,他会继续研究这个问题并在这周内给你回复."*

Just like that, I was a software architect. The rush of power. The anticipation of career advancement. I am an architect! Soon a slight feeling of dread set in. I am an architect. Now what do I do? How is being a software architect different from being a software engineer?

*就那样,在外力的推动下,我成为了一名软件架构师,而现在基于职业发展的考虑,我就是要成为一名架构师!很快我感觉到一种莫名的恐惧,作为一名架构师,我该做什么?架构师和程序员有什么不同?*

Software architects have a number of responsibilities in addition to programming. They define the problem from an engineering perspective. They divide the software system into implementable chunks, but also keep an eye on the big picture to ensure the system still works as a consistent whole. Architects decide trade-offs among quality attributes and manage the inevitable growth of technical “debt. Perhaps above all, architects develop their team’s architecture skills, because they know the best teams are filled with architects.

*架构师除了写程序还有很多其他的职责,比如找出工程上出现的问题;将软件系统切分为可实现的模块,同时保持对整体性的把控,以确保整个系统的完整性.架构师会平衡质量属性和不断增长的技术债务.除此之外,架构师还会在团队中传授软件架构相关的技能,因为他们知道最好的团队是所有人都是架构师的团队.*

In this chapter, you’ll learn what architects do. You’ll also learn why knowing about software architecture will make you a better programmer and technical leader. You’ll also learn how to get started on the path to becoming a software architect in your professional career.

*在本章中,你会学习到架构师的职责.你也会了解为什么熟悉软件架构师的工作会帮助你成为一个名更出色的程序员或者技术经理.同时你会学会怎样在职业道路中开始朝架构师的目标前进.*

### What Software Architects Do
Software architects are in a unique position on the team. They aren’t project managers, but architects decide when and how software is delivered. They aren’t product managers, but architects make sure the software meets its business goals. They write code, but architects design more than only algorithms and code. Software architects have a distinct set of responsibilities and are seemingly at the center of everything.

*软件架构师在团队的作用是独一无二的,他们不是项目经理但是却可以决定如何以及在什么时候交付产品.他们不是产品经理但是架构师却需要确保软件能符合业务需求.他们还需要编写代码,但是架构师更多的时候是在从事设计工作而不是仅仅专注于代码和算法.软件架构师有着一系列清晰的职责,看起来他们就是一切的核心.*

### Define the Problem from an Engineering Perspective

Software architecture design is a human-centered design discipline. Everyone with a stake in the software can help you understand what is expected of it. Software architects work with product managers, project managers, and other stakeholders to define business goals and requirements for the software to be built.

*软件架构是一种以人为中心的设计原则,每个参与者都可以帮你了解到他们想要的东西.架构师和产品经理,项目经理以及其他相关参与者一起定义业务目标和软件需求.*

On many teams, product managers define the features. Features are great, but there is another kind of requirement called a quality attribute that architects care the most about. In addition to defining quality attributes for the system, architects keep an eye out for design constraints and features that might force the architecture down a specific path.

*在很多团队中,产品经理负责定义功能,功能确实很重要,但是有另外一种功能叫做质量属性,这才是架构师最关注的点.除了考虑系统的质量属性,架构师同样会密切关注那些可能让架构倒退的设计要求和功能.*

Defining the problem with the architecture in mind ensures you can build a system everyone wants. You’ll learn how architects approach requirements Dig for Architecturally Significant Requirements in chapter 5.

*时刻注意架构中的问题可以让你创建一个大家都满意的系统.你也会在第五章学到架构师如何提炼需求.*

Most of us start our software careers focusing purely on technology. Knowing how to program, design efficient algorithms, test that everything works, and deploy software are all essential skills for software architects too. Growing from programmer to software architect requires you to accept some new responsibilities.

*大多数架构师都是从单纯技术层面开始的,比如编码,设计高效的算法,测试以及部署都是架构师必需的技能.但是从程序员到架构师需要你承担新的职责.*

### Partition the System and Assign Responsibilities

Have you ever watched little kids play soccer? The only tyke to stay in position is the goalie, who remains glued to their team’s goal while the other children form a glob of kicking feet and chase the ball from one end of the field to the other. It’s adorable. Once the kids grow up a bit, they learn to play set positions. Playing positions is important since it lets the coach create a game strategy, which increases the team’s likelihood of scoring.

*你看过小孩踢球吗?整个场地里除了守门员会呆在自己的位置上外,其他的小孩都是全场飞奔地追着球跑,看着很可爱.一旦这些孩子长大一点了,他们就会学会按分配好的位置踢球.场上的位置非常重要,因为这是教练制定的比赛策略,可以提高球队进球的几率.*

Some software systems are designed like a children’s soccer team: one great big clump of software chasing after a release. Software development, similar to soccer games, goes smoother when the software is divided into pieces and each piece is assigned a responsibility, a position to play.

*有的软件设计的就像儿童足球队的感觉,每次发布都会伴随着一大堆的功能.但是软件开发和踢足球一样,如果把一个软件切分成不同的模块,然后再把不同的模块交给不同的人来负责开发效率会更高,这就类似足球场上的“位置”.*

Architects partition (a fancy word for divide into pieces) the software system so they can develop a strategy for achieving quality attributes and other system requirements. For example, you might assign functional responsibilities by designing one component to register users and another to identify pictures of cats. Or you could assign different teams to develop different modules. Or you might split things that read data from things that write data so the software system will be more reliable, available, and scalable.

*架构师把一个软件系统分片(一个时髦的用来描述"切分"的词汇)然后就能更好的制定出能实现质量属性和其他系统需求的策略.比如你可以将用户注册和识别图标包含猫的图片这两个功能交给不同的人来开发,或者不同的团队开发不同的模块,还可以把读数据和写数据的部分切分开,这样系统就会更容易实现稳定性,可用性和可扩展性.*

Partitioning a system is important not just because it lets you develop a strategy for achieving quality attributes. Smaller things are easier to reason about, easier to test, and easier to design. Of course, since you broke the system into pieces, you’ll also have to make sure everything can come back together again.

*把一个系统拆解开不只是能为满足质量属性而更好的去制定策略,细颗粒的事物可以更好的描述,更方便的测试,更容易设计.当然最重要的是当你把系统拆解开后你要保证它们能在一起完美的配合工作.*

### Keep an Eye on the Bigger Picture

Every software system lives in the context of a bigger world. The world in which software lives includes the users who interact with it, the team who builds it, the hardware it runs on, and even the purpose for developing the software in the first place. Ideally, the architecture lives harmoniously within this broader context.

*每个软件系统都对应更大的外部世界的各种场景,包括使用系统的用户,开放系统的团队,运行软件的硬件,甚至最开始开放这款软件的初衷.理想状态下,软件架构应该和这种广泛的背景和谐共存.*

Thinking about the system as a whole means architects deal with more than just technology. People, processes, business needs, and many other technical and nontechnical factors play a part in the final software system. Even simple design decisions can have far-reaching consequences. Architects must look beyond a small neighborhood of design decisions and think about the system as a whole.

*更宏观地看待软件系统软件而不是仅仅限于技术角度,用户,流程,业务需求以及其他技术和非技术的因素都是最终交付的软件系统的一部分.甚至一个简单的技术设计都可能产生长远的影响.架构师必须以更长远的眼光来宏观地撕开整个系统.*

Software design is a constant struggle to find the right balance between the things you want and the reality you must accept. This means you must think about and make trade-offs.

*软件设计是一个不断进取而在需求和现实之间平衡的工作,这意味着你必须思考和权衡利弊.*

### Decide Trade-offs among Quality Attributes
Say high availability is an important quality attribute for your stakeholders and you need your software to respond to 99.9 percent of requests. One way to promote availability is to introduce redundant elements. Designing for this is simple, but there’s a catch. You now must purchase twice the hardware, which doubles your costs. In this case, you traded costs to get higher availability.

*假如高可用性是大家很关心的一个质量属性而且你的系统需要能响应99.9%的请求,第一个保证可用性的办法是引入冗余的节点,这种在设计上很简单,但是有一个缺点就是你必须买两份硬件资源,成本也加倍了.这样相当于用成本换可用性.*

It is common in software development to give up something you want to get something you need. Architects identify the trade-offs and work with stakeholders to decide which compromises make the most sense.

*在软件开发中这种做出一些牺牲来获取自己需要的东西的做法很常见,架构师需要识别出这种需要权衡的地方然后和大家一起决定怎样做出最佳的决策.*

Software systems are never partitioned perfectly. You’ll make compromises. You’ll make mistakes. As you build the system, you’ll introduce technical debt into the architecture.

*软件系统永远不可能完美,你会做出妥协,也会犯错,而随着系统的搭建过程,你会在架构中引入技术债务.*

### Manage Technical Debt

Software architects know the details about how the system is partitioned. They keep an eye on the big picture and guide how everything comes together. They also connect technology decisions with thing comes together. They also connect technology decisions with business needs. Knowing all this puts architects in the perfect position to manage technical debt.

*架构师知道系统是怎样切分的,他们会统筹全局并指导怎样让每个部分能结合在一起工作,他们会全盘考虑技术决策,会把技术决策和业务需求结合起来,只有这样架构师才能在胜任管理技术债务的工作.*

Technical debt is the gap between your software system’s current design and the design you need it to have so you can continue to deliver value. You can measure the amount of technical debt by estimating the effort required to close that gap. All software has technical debt. Technical debt is an inevitable byproduct of success. The best software development teams use technical debt strategically to ship faster and regularly pay debt down so they can continue shipping value over time.

*技术债务就是横亘在当前系统的设计决策和未来为了持续交付而需要的技术设计之间的鸿沟,你可以通过计算填补这个鸿沟所需要的工作量来衡量当前的技术债务,所有的技术债务都是获得成功而所不可避免产生的附属品,优秀的开发团队指定合理的技术债务管理策略来更快的交付同时定时的偿还一部分债务,这样保持持续的交付能力.*

Architects make technical debt visible and help stakeholders decide which actions to take to manage it.

*架构会让技术债务变的可见并帮助相关人员决定采取怎样的行动来管理这些债务.*

### Grow the Team’s Architecture Skills

Software architects are teachers and mentors for their teams. There is no use in designing an awesome architecture that nobody can understand. As the architecture expert on your team, it is your responsibility to share your knowledge with your team so they can successfully develop an amazing software system.

*软件架构师是团队的老师和领路人,没法让人容易理解的架构是没有用的,作为团队的架构专家,你的职责就是把你的知识分享给团队成员让他们能成功的开发出杰出的软件系统.*

Architects teach design skills and architecture concepts just-in-time. To pass on your knowledge, you’ll pair design with teammates, create documents that educate and inform, and share constructive criticism. Perhaps the most important thing you can do to grow the team’s architecture skills is to include them in the design process. Architecture design is a social activity. Skills development is crucial to your team’s success.

*架构师随时可能传授设计技巧和架构概念,为了传递技能,你可以和团队成员结对工作,编写相关的文档,然后分享有建设性的意见.最有效的提升团队成员的架构技能的办法大概就是让他们参与到设计过程中,架构设计是一个社会活动,团队要想取得成功技能的提高是非常重要的.*

Now you know what architects do, but we haven’t defined what we mean by software architecture yet. Let’s do something about that now.

*现在你知道架构师是做什么的了,但我们还没有给软件架构做出定义,这是我们接下来要做的.*

### What Is Software Architecture?

A system’s software architecture is the set of significant design decisions about how the software is organized to promote desired quality attributes and other properties.

*软件架构就是一系列推动系统满足必须的质量属性和其他功能的重要决策.*

A design decision might be significant for any number of reasons. It might represent a point of no return or influence quality attributes, schedule, or costs. A significant decision might be one that affects many people or forces other software systems to change. In any case, significant design decisions are costly to change later if you get them wrong.

*一个技术设计决策可能在很多方面体现出它的重要性,可能代表了一个没有回报的付出或者影响相关的质量属性,工作安排和成本.重要的技术决策可能会影响很多人,可能会迫使别个软件系统不得不做出改变,不管怎么样,重要的技术设计决策在未来做改动的成本是非常高的.*

To promote a quality attribute means to encourage it to appear in the software system. When the architecture is well organized, it will boost the quality attributes stakeholders want and downplay or eliminate the quality attributes stakeholders don’t want. Architecture can promote other properties too. For example, the right architecture for the job will let you ship on time, on budget, and without requiring too much overtime.

*提高某种质量属性意味着尽量使其在软件系统中被呈现出来,当软件架构被组织的很好时,它就会促使相关的人员将他们不需要的质量属性移除或者淡化.软件架构同样可以促进其他方面的价值,比如正确的架构可以让交付更及时,满足预算,而且不会要求太多的加班.*
