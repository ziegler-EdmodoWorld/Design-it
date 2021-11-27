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

### Define the Essential Structures

A skyscraper has a foundation and frames. A body has bones. Software has structures. A structure defines how a software system is arranged. Structures are in the code you write, the software you run, and even your collaborations with other people.

*建造一栋摩天大楼需要地基和框架,人体需要骨骼,而软件有它的结构.软件的结构决定了系统是怎样被组织起来的.结构存在于你编写的代码中,也存在于你使用的软件以及你和其他人的合作之中.*

To create a structure, take any element and connect it to another element using a relation. Think of elements and relations like the bricks and mortar of software. The bread and peanut butter. The duct tape and…well, you get the idea. Elements are the fundamental building blocks of software. Relations describe how elements work together to accomplish some task.

*创造一个结构的过程就是找一个元素然后把它和另外的元素通过某种关系连接起来,可以把软件的元素和关系想象成砖块和水泥或者面包和黄油或者胶带和...,你应该已经明白这点了,元素是软件的基础建筑模块,模块之间的关系描述了模块怎样通过合作来完成任务.*

It’s easy to design an architecture on paper with no bearing on reality. To avoid this trap, you’ll build architectures using three types of elements and relations. Software Architecture in Practic defines these three types as module, component and connector (C&C for short), and allocation. To create a structure, combine elements and relations of the same type.

*脱离现实的来在纸上画出一个软件架构设计师很容易的,为了避免这样你需要通过使用三种元素和关系,"软件架构实践"这章讲解了这三种元素类型:模块,组件,连接器(简称C&C)以及如果使用他们.我们通过把相同类型的元素组合连接起来来创造一个系统结构.*

Module structures exist at design time. You interact with module structures when you write code. Module structures live on the file system and stick around even when the software is not running.

*模块结构是在设计阶段确定的,不同模块通过编码产生交互,模块结构是存放在文件系统中的,即使软件没有运行起来也是存在的.*

Component and connector structures come into existence at runtime. At runtime, components can create connections to other components, spawn new processes, and instantiate new objects. Unlike module structures, C&C structures cease to exist when the system is not running. You might only know a C&C structure existed from the artifacts it left behind, such as a log file or database entry.

*组件和连接器结构只有在运行时才会存在,在运行时组件可以创建连接器来连接其他组件,创建新的进程,创建新的对象,和模块结构不同的是组件+连接器结构在系统停止运行后就不再存在了,你只能通过它留下来的足迹捕捉到它的存在,比如日志文件和数据库里的数据.*

Allocation structures are created by showing how module and C&C elements correspond with each other and the physical elements that exist in real life. Allocation structures are sometimes called mapping structures since they show how different elements map to one another. Does an element run on the client machine or the server? Which teams are building which parts of the system? Allocation structures help us answer questions like these.

*分配结构是用来描述模块和组件间的对应关系以及现实生活中的物理元素的,分配结构有时会被称为映射结构因为它展示了不同的元素之间的对应关系.比如某个元素是运行在客户机还是服务端?哪一个团队负责系统中的某一个部分?分配结构就是帮组我们来回答这些问题的.*

### Joe asks: Are Components and Modules Different Things?

In your software development career you may have heard the words module and component used interchangeably and in different contexts. Technically a component is a different concept from a module. A module refers to a design time element whereas a component is a runtime idea.

*在你从事软件开发工作的经历中可能听到过这种说法:模块和组件在不同的场景中都是可互换的,从技术上讲组件和模块是两个不同的概念,模块更多的是一个设计过程中的一个元素而组件是一个运行时的概念.*

Sometimes this precision in language is important. Using a term with specific meaning to describe something general can create confusion. Anytime you want to describe a generic building block of an architecture instead of using component or module, use the word element.

*有时这种语言上的精确表述是很重要的,使用专业的术语来描述一个宽泛的事物会让人困惑,每当你想要描述架构中某个宽泛的组成部分的时候尽量使用元素这个词而不要随意使用组件或者模块这样的词汇.*

All that said, arguing about semantics is not the best way to get your ideas across. While I encourage you to use proper and precise terminology, your ideas will sometimes get better mileage by adapting your language so others understand you.

*不管怎么说,在语义上吹毛求疵并不是帮助你传达想法的最重要的事情,但是我仍然鼓励你尽量使用适合且精准的术语,这样你的想法能够通过准确的表达来让别人更好的理解到.*

Different kinds of structures are useful for thinking about different properties you want in your system. For example, you can think about testability and maintainability using a module structure. A C&C structure helps us think about runtime concerns such as availability or performance. You also might know there’s a gap in our understanding if you see mixed structures such as a static element using a dynamic relation.

*在思考系统中需要的不同属性的时候使用不同的结构是很有用的,比如你可以把可测试性和可维护性看作一个模块,组件结构帮助我们思考运行时的关注点比如可用性和性能.你同样可能知道如果你看到一个混合的结构比如一个静态的元素用到了一个动态的关系那就不太容易理解.*

Structures determine the shape of our system. The shape is important since it decides the quality attributes and other properties your users will experience. In the next section you’ll see how to use structures to reason about quality attributes, but first, it’s time get your hands dirty with a quick exercise.

*结构定义了我们系统的形态,这个形态很重要因为它决定了质量属性和其他用户体验相关的特性,在下一节你会看到怎样使用结构体来定位质量属性,但首先你的做一个小测试.*

## Get Your Hands Dirty: Elements, Relations, and Structures

Find a few teammates from a recent project. Working alone, list or sketch module, component and connector, and allocation structures from that project. Share your lists with one another. How do they compare? Are there structures your teammates identified that you didn’t? Discuss the similarities and differences in the structures different teammates identified.

*找一些最近在同一个项目工作的同事,回忆之前那个项目,先独自列出或者画出模块,组件和连接器以及依赖结构.把你们总结的内容和别的同事分享,怎么比较呢?有没有你同事识别出来但是你没有的结构?然后再讨论这些不同的同事提出的结构的差异和相同之处.*

Here are some things to think about:

*有一些值得思考的地方:*

Be specific when naming the elements. Don’t forget about the relations!

*在给元素命名的时候需要精确,不要忘了它们之间的关系.*

Think about the module structures: What methods or classes are used? Do the classes live in different packages or namespaces? What dependencies are included in package managers or build scripts?”

*思考下模块结构:用到了什么方法和类?类是否存在于不同的包和命名空间中?包管理器或者构建脚本依赖了什么东西?*

Think about the C&C structures: Does the software interact with other processes or systems at runtime? Who calls the system and how does it change in response?

*思考下组件+连接器结构:软件有没有和其他进程或者系统有运行时的交互?谁在负责调用,它是怎样修改响应的.*

Think about the allocation structures: Who is responsible for building different parts of the software? How is the software deployed?

*思考下分工结构:谁负责搭建软件不同的部分?软件是如何部署的?*

### Reason about Quality Attributes (and Other System Properties)

Say you’re building a calculator app and you want to add two numbers together. Sounds easy, right?

*假设你要开发一个计算器软件将2个数相加,听起来很简单对吧?*

Wait. Did you want a calculator that adds two numbers and is fast, reliable, scalable, and maintainable? Why didn’t you say so! If we hadn’t asked about these quality attributes, we might have designed the wrong system altogether.

*等等,你希望这个计算器不止做到把两个数做加法而且速度快,而且可靠性,扩展性和可维护性都很强吗?为什么要这样问呢?如果我们不去考虑这些质量属性,我们可能就会设计出一个完全错误的系统.*


A quality attribute is any externally visible characteristic by which stakeholders judge a software system’s goodness. Some examples include scalability, availability, maintainability, and testability. You experience quality attributes when you interact with the software.

*质量属性是相关人员可以判断一个软件系统是否优秀的可见特性,比如包括扩展性,可用性,可维护性以及可测试性.你使用某个软件的时候就会体会到这些质量属性的影响.*

When you choose an architectural structure, you are choosing the quality attributes you want to be promoted in the software system. Thinking about software architecture makes sure you design a software system that supports the quality attributes you want within the context of all the other concerns vying for attention.

*当你选择一个组织架构的时候,你实际上就是在选择能满足软件系统需求的质量属性.对软件架构的思考确保你设计出来的软件系统能够满足那些能够引人瞩目的质量属性.*

Quality attributes make software unique. The circumstances of every system are different—different team, different budget, different market conditions, even different technology trends. As a result, no two architectures will ever be the same even if the feature sets are identical.

*质量属性让软件变的独一无二,每个不同的系统都是由不同团队开发的,有不一样的预算,不同的市场前景,甚至不同的技术趋势,所以即使功能是一样的,对不同的系统也不会没有两种一模一样的架构.*

Up for the challenge? In the next section, you’ll learn some strategies for becoming your team’s architect.

*准备好迎接挑战了吗?下一节,你会学到一些能帮助你成为团队中的架构师的策略.*

### Become an Architect for Your Team

On some teams, architect is an official team role. On other teams, there is no explicit role and teammates share the architect’s responsibilities. Some teams say they don’t have an architect, but if you look closely, someone is fulfilling the architect’s duties without realizing it.

*有的团队中架构师是一个官方授权的角色,而在有些团队没有一个明确的架构师的角色,所有的成员都会承担架构师的任务,有些团队宣称他们没有架构师但是如果你仔细观察,其实已经有人在承担架构师的角色了,只是他没有意识到而已.*

Architects are leaders, but being a software architect also implies a person who thinks about software design in a certain way. No matter what the title on your business card reads (mine still reads software engineer, my choice), you can be a software architect. Every team has at least one architect. The best teams have several.

*架构师是技术领袖,但是作为一个架构师同样表明你是一个对软件设计有着独到看法的人,不管你的名片上的职务是什么(我的名片上依然是软件工程师,我更喜欢这样)你都可以做架构师的工作,每个团队都需要至少一名架构师,最好同时有多个.*

If your team doesn’t have an architect, congratulations, you’ve got the job! You don’t need permission to inject architectural thinking into your team’s design discussions. Start asking questions about quality attributes. Point out when the team makes trade-offs. Volunteer to write up design decisions and begin accepting more architecture design responsibilities.

*如果你的团队没有架构师,恭喜你,说明你已经在承担这个职责了,你不需要授权就主动的将架构思维运用到了平时团队的技术讨论中,开始关注质量属性,指出团队需要做的技术决策,主动编写设计文档并且开始承担更多的架构设计工作.*

If your team already has an architect, then ask that person how you can help. When possible, work closely with your architect and take advantage of every learning opportunity you can. Developing a software system is a big job. The more people who pay attention to the details, the greater your chance of success. Every team should be so lucky as to have many knowledgeable software architects!

*如果你的团队已经有一名架构师了,那可以问问他你怎样能让你帮到他,如果可能喝你的架构师紧密的合作,利用每次可以学习的机会.开发一个软件系统是一个庞大的工作,越多人参与到细节的考虑,那成功的几率就越大,如果一个团队同时有多名知识丰富的架构师那就太幸运了.*

### Make the Move from Programmer to Software Architect

An average software architect has developed three to five software systems with increased technical responsibility on each software system. Depending on the software you build, as your architecture responsibilities grow you may find you have less time for programming. This is normal, though software architects should never stop programming altogether.

*一个普通的软件架构师一般能在3到5个软件系统上逐渐承担更多的职责,根据不同的软件的情况,你会发现当你的架构师职责变多的时候就更少有时间写程序了,这很正常,虽然软件架构师不应该远离代码编写.*

To measure your growth from programmer to software architect, create a project portfolio. For every software system you build, no matter your role, briefly describe the software system and what you learned during your time developing it. This kind of reflective practice is essential for all technical leaders but especially software architects.

*为了测量你从程序员到架构师的距离,可以创建一个项目文件夹用来大概描述这个软件系统和你在开发过程中学到的东西,这种反应式的练习对所有技术领袖都是有必要的特别是对软件架构师.*

Here are some questions you should answer about each project in your portfolio:

*这里有一些针对每个项目你都应该尝试回答的问题:*

Who were the stakeholders and what were the primary business goals?
What did the high-level solution look like?
What technologies were involved?
What were the biggest risks and how did you overcome them?
If you could do it all over again, how would you do it differently?
Whether your goal is promotion or simply professional growth, be patient. You might have the chance to design a software system of meaningful complexity only every three to five years. If you are lucky, you will see between 8 and 15 software systems throughout your entire career. Be prepared to take advantage of architecting opportunities as they arise. Work with your teammates to give everyone a chance to grow their skills. I promise there is more than enough interesting architecture work for everyone!

*
相关的人员有哪些以及主要的商业目标是什么?
高层的解决方案是怎样的?
使用了哪些技术?
最大的风险以及怎样去克服的?
不管你的目标是晋升还是简单的职业成长,都需要耐心点.你可能每三到五年才有机会去设计一个非常复杂的大型软件系统,如果你足够幸运,你会在自己整个职业生涯参与8到15个软件系统的开发,抓住有机会做架构工作的优势,和你的队友一起合作让大家都有机会去提升自己的技能,我保证肯定会有足够多的有趣的架构工作可以让大家都来参与.
*

Always remember, software architect is a way of thinking, not just a role on the team. When you’re wearing your programmer hat, you’ll make dozens of design decisions daily. Some of these decisions have architectural significance. Anyone who makes a decision that influences the structures of the software system becomes the architect pro tempore. It’s up to you to make good decisions and uphold architectural integrity no matter what the title on your business card reads.

*一定要牢记,软件架构师是一种思维方式,而只是团队中的一个角色,当你做为程序员时你每天可能会做成千上万的技术决定,其中部分决定包含架构的意义,任何做出了影响系统结构的技术决定的人都是零时的架构师.你完全可以自己作出好的技术决策然后承担架构工作而不需要名片上的一个职务.*

### Build Amazing Software

There are lots of things that have to go right when building a software system. Architecture connects them all together and provides a foundation for success. Here are six ways software architecture helps you in your quest to build spectacular software that your stakeholders will love:

*在搭建一个软件系统的时候需要做好很多事情,架构师会把这些事情都联系起来为项目的成功打好基础.下面是六种架构师能帮助你创造出让用户喜爱的软件系统的方式:*

1. Software architecture turns a big problem into smaller, more manageable problems.
Modern software systems are large and complex, and they have many moving pieces. The architecture precisely explains how to partition the system into smaller, bite-sized chunks while also ensuring the system as a whole is greater than the sum of its parts.

*1.架构师把一个大的问题切分成更小,更容易管理的问题.
现代的软件系统变的规模更大更复杂,而且分为很多不断变化的部分,架构师能精确的解释怎样把系统拆分为更小的部分,同时保证这些部分被整合起来形成一个整体的时候能发挥更大的作用.*

2. Software architecture shows people how to work together.
Software development is as much about human communication as it is technology. Software architecture describes how the whole system comes together, including the people who build it. When you know the architecture, then you can see how people can collaborate to develop software. The larger the software system, the more important this becomes.

*2.架构师展示了合作的能力
软件开发中沟通能力和技术能力一样重要,架构师描述了整体系统是如何组织的,包括开发人员,当你了解整个架构时,你就知道人们是如何合作去开发软件的.软件系统越大,沟通也就越重要.*

3. Software architecture provides a vocabulary for talking about complex ideas.
If I don’t understand what you’re talking about, then we won’t be able to collaborate. Instead of spending all our time inventing vocabulary and concepts, we can use the essential concepts and core vocabulary of architecture as the starting basis for collaboration. Now we can spend our time solving our users’ real problems.

*3.软件架构师为讨论复杂的想法提供了词汇表
如果我不知道你在说些什么,那么我们没法合作,我们可以先使用基础的概念和核心的一些架构相关的词汇来作为合作的基础而不是一直忙于发明新的术语,这样我们才有时间去解决真正用户的问题.*


4. Software architecture looks beyond features and functionality.
Features and functionality are important, but they are not the only thing that determines whether or not software is awesome. When designing architecture, you’ll consider not only the features but also costs, constraints, schedules, risk, the ability of the team to deliver, and most importantly quality attributes—things like scalability, availability, performance, and maintainability.

*4.软件架构超越了特性和功能.
特性和功能很重要,但是他们不是唯一决定软件是否出色的因素,当设计软件架构时,你不止会考虑功能同时也要考虑成本,限制因素,排期,风险,团队交付的能力,最重要的是质量属性,比如扩展性,可用性,性能和可维护性.*

5. Software architecture helps you avoid costly mistakes.
In Who Needs an Architect?, Martin Fowler defines software architecture as “…the important stuff. Whatever that is.” The important stuff is nearly always what we think will be difficult to change without significantly increasing complexity. Grady Booch echoes Fowler’s sentiment by defining architecture as the “…significant design decisions (where significant is measured by the cost of change).”[2] Software architects are not omniscient, but designing an architecture will help you discover the challenging (and interesting) parts of the problem that might cause big trouble later.

*5.架构师能帮助你避免高代价的错误.
在<谁需要架构师?>中,Martin Fowler把架构称为"不管从哪方面讲都是重要的事情".而我们认为的重要的方面都是那些必须付出巨大的复杂性提升的代价才能改变的事情.Grady Booch回应了Fowler的说法讲架构定义为"重大的设计决策(重大的程度取决于未来改变这个设计的成本)".架构师不是无所不知的,但是架构设计会帮助你从问题中发现那些有挑战(或者有趣的)的部分,这部分问题可能在未来引发巨大的麻烦.*

6. Software architecture enables agility.
Your software should respond to change like water, by bending around obstacles with ease. If software is like water, able to take any shape, then software architecture is the container that holds it. That container can be rigid like a box or flexible like a plastic bag. It can be thick and heavy or lightweight. Without an architecture, software, like water, follows the path of least resistance and sprawls uncontrollably. A software system’s architecture provides the structure within which change is possible.

We’ll expand on these ideas throughout the remainder of the book.

*6.软件架构驱动着敏捷
你的软件系统就应该像水一样灵活,能够轻松的在障碍物间穿梭,如果软件像水一样能变成任何形状,那么架构就是包裹它的容器,这个容器可以像盒子一样坚固也可以像口袋一样轻巧,它可以厚重也可以轻便,没有架构的话,软件会像水流一样沿着最省力的路径不受控制的流淌开,软件系统架构提供了未来去改变系统的可能性.

我们会在以后的章节展开讲解这些概念.*

