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

