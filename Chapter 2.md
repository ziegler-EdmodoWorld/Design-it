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

### Make the Architecture Tangible

While the structures in the architecture can exist in code, this does not make the architecture any more tangible. Code is difficult to read and does not make discussions about quality attributes, coarse-grained components, design rationale, or the consequences of our decisions any easier. If we want to share an architecture with others, then we need to make it real in a way code by itself will not allow.

*架构中的各种结构体可以存在于代码中,这并没有增强架构的可见性,代码不太容易阅读而且没有引入关于质量属性,粗颗粒度的组件,设计思想或者之前我们决策的实施结果的讨论.如果我们想要分享架构给其他人,那么我们需要找到一种代码无法替代的表现方式.*

There are many ways to make architecture tangible. Draw it. Make it come alive in the code you write. Build prototypes that let people experience structures and quality attributes. Create simple models that show how some part of the architecture works. Create relatable metaphors. Act out parts of the control flow of the system.

*有很多方法可以实现架构的可见性,比如画图,让架构图和你编写的代码报纸一致.画原型图可以让人们感受到架构的结构和质量属性.用简单的模型展示架构中某些部分是怎样工作的.用相关的隐喻来表示系统的控制流程.*

The tangibility rule is closely related to the Human rule. Humans must be able to relate to ideas to internalize them. The only way to share an architecture is to make it tangible.

*可见性规则和以人为本的规则很相似,人类必须要先能把想法联系起来才能去内化他们.唯一能分享架构的方式就是让他们变得可见.*

The HART principles form the philosophical basis of our architecture design approach. These principles guide our decision making and permeate our thinking. These four principles describe why we do things the way we do them. Now that you understand the underlying principles behind design thinking, let’s explore how to apply these principles by learning how to select architecture-focused design practices.

*HART原则产生于我们的架构设计方法论的哲学基础.这些原则知道我们作出决策同时贯穿到我们的想法里.这四个原则描述了我们采取对应行动的原因.现在你应该了解了设计思维背后的原则了,让我们继续探索怎样通过学习选择以架构为中心的设计实践来应用这些原则.*

### Adopt a Design Mindset

Designing a software system requires us to think about the architecture from the perspective of different design mindsets. A design mindset is a way of thinking about the world so that we focus our attention on the right details at the right time.

*设计一个软件系统需要我们从不同的设计思维出发去思考整个架构.设计思维就是一种能让你准确而及时的对外部世界进行思考的方式.*

There are four design mindsets: understand, explore, make, and evaluate. Each design mindset comes with a set of practices. To design the architecture, we’ll choose a mindset, pick a practice in that mindset, apply the practice to learn something new about the architecture, and repeat.

*有四种设计思维:理解,探索,行动和评估.每种设计思维都源于一些实践, 为了设计一种架构,我们会选择一种思维方式,选取一种实践,然后再将实践应用到现实中来学到更多关于架构的知识,之后不断重复这个过程.*

The chapters in Part II will show you how to put each mindset into practice. Look for the icon, shown in the image, at the start of each chapter to tell you what the focus will be. For now, let’s learn what it means to embrace each of the four design mindsets.

*第二部分的章节会想你展示怎样将每种思维模式应用到实践中,每章开头的图标和图片会告诉你这章要讲的重点,但是现在我们先学习怎样去拥抱这四种思维模式.*

### Understand the Problem

In the understand mindset we actively seek information from stakeholders and work to describe the problem. The understand mindset is as much about requirements as it is empathy. To understand the problem, we must learn about the people who will be touched by our system and what they need.

*在理解思维中我们积极的从相关人员那儿获取信息并得到清楚的问题描述.这种思维既是需求的来源也是对用户的一种同理心.为了理解问题,我们必须学习那些用户对系统的使用方式和他们的需求.*

To understand the problem, we’ll need to investigate business goals and quality attributes that are important to our stakeholders. We’ll also have to learn how our team operates and get a deeper sense of the priorities and trade-offs among design decisions.

*为了了解问题,我们需要调查对相关人员很重要的商业目标和质量属性,同样也要了解团队是如果工作,对设计的优先级和取舍有一个更深入的理解.*

### Explore Ideas

In the popular ethos, design thinking is all about brainstorming and sticky notes. Brainstorming is powerful, but it is only one practice in the explore mindset. When we explore, we create multiple design concepts and identify engineering approaches for solving some aspect of a problem.

*在传统的观念里,设计思想就是头脑风暴和百事贴.头脑风暴是有强大的,但是它只是一种拓宽思维的实践方式,当我们去做思维发散的时候我们是在创建多种设计概念来在工程上通过各种方法来解决特定的问题.*

Exploring software architecture means we try combinations of structures until we find a combination that best promotes desired quality attributes. To find the best mix of structures, we’ll need to survey a broad range of patterns, technologies, and development practices. When we’re planning the architecture, we’ll spend a lot of time in the exploration mindset, but this mindset is also useful when working with stakeholders.

*扩展软件架构意味着我们要试着不断尝试各种组合的直到我们找到能最大化的满足我们的质量属性的方案.为了找到最佳的组合,我们需要对大量的模式,技术和开放实践进行调研,当我们计划作出架构设计时,我们会很多时间在扩展思维上,但是这些思维方式在和相关人员一起工作的时候同样是有用的.*
### Make It Real

As you learned in "Make the Architecture Tangible", ideas are great but if you can’t transfer them from your brain into someone else’s brain, then your ideas are useless. Making ideas real gives us a way to share them but also provides an opportunity for testing an idea. In the make mindset we turn our design concepts into real-world artifacts.

*在“让架构变得可见”这节中你已经了知道有想法是好的,但是如果不把自己大脑中的想法灌输给其他人,那这些想法就毫无用处.将想法落地给了我们一种能去分享的机会同样也获得了试错的机会.在"实践思维"中我们就是把设计概念落实到真实世界的交付物中.*

The most common ways we make architecture real is by creating models. Making goes way beyond box and line diagrams. You can make the architecture real by building prototypes, writing documents, crunching numbers, and a variety of other approaches.

*最常见的把架构落地的方式就是创建模型,不止是框图和线条,你同样可以通过建立原型,输出文档,处理数字以及其他很多方式来做到.

The make mindset is useful for communicating our plans. We’ll also make the architecture real as we build the system—for example, by organizing our code so that it’s possible to see module structures in the architecture. Making is also an excellent way to push your team out of analysis paralysis.

*"实践思维"在交流大家的计划的时候很有用,我们同样也可以就像真正的来构建系统一样来尝试让架构落地,比如查看代码来梳理架构里面的模块结构,实践和落地是一种十分有用的方法能让团队不仅仅局限于分析和论证.*

### Evaluate Fit

How do you know if a design decision will solve the problem? When we embrace the evaluate mindset, we determine the fitness of our design decisions relative to our current understanding.

*怎样评估设计决策的效果呢?当我们抱着不断评估的态度时,我们就在基于我们当前的理解在探查我们的设计的适用性.*

Evaluation is not an all or none proposition. We can evaluate all or part of the architecture, even only a single model, concept, or idea. The most common approach is to walk through a piece of the architecture with different scenarios, but we can also test design decisions directly by running experiments or examining the risks surrounding a decision.

*评估那种要么不做要么全做的事情,我们可以对架构的部分进行评估,甚至只针对其中一个单独的模块,概念或者想法.最常见的评估的方式是针对不同的场景对一个架构进行评估,但是我们也可以通过实验或者发现技术决策的风险来做评估.*

The evaluate mindset comes in handy when we want to verify the planned or built architecture, but this is only the beginning. This mindset will help us inspect anything we make and decide whether that artifact is serving our need.

*基于评估的思维在我们想验证计划或者创建架构的时候就能派上用场,但这只是开始,这种思维帮组我们深入了解各种我们的输出和决策,不管它们是不是有用的.*

Using design mindsets requires a process with a tight feedback loop so we can quickly move from one mindset to the next. In the next section, we’ll learn how to use a simple, iterative approach to help us choose and use design mindsets.

*使用设计思维需要一种能及时反馈的流程闭环,这样我们就能快速的在不同的思维模式之间切换,在下一节中我们会学到怎样使用简单,可迭代的方式来帮助我们选择和使用设计思维.*

### Think, Do, Check
Every day, for as long as we work on a software system, we learn interesting things about the software. Every new thing we learn might force the architecture to evolve to reconcile the new information. For us to keep tabs on this ever changing landscape, we need a design approach with a tight feedback loop that gives us the opportunity to change our mindsets often.

*每天,只要我们从事软件系统的开发,我们就会学到有关软件的有趣的东西.每件新学到的东西都可能会推动软件架构融入我们新获取的知识.为了让我们能追踪这些不断变化的状态,我们需要一种经过设计的方式来形成一个紧密反馈循环使得我们有机会经常改变我们的想法.*

There are three steps in our approach: think, do, and check. Each iteration of the think-do-check cycle focuses on a particular design mindset.

*在这种方法中包含三个步骤:想,做和检查.每个迭代中的不同步骤都需要一个特定的设计思维来支持.*

### Iterate to Learn
An iteration can be as brief as a few minutes or as long as a few days. We prefer shorter cycles over longer ones, but sometimes more time is required for in-depth research. Every iteration follows the same steps, though the execution will vary depending on the design mindset we adopt.

*一次迭代可以是几分钟也可以是几天,我们更喜欢利用短时间的循环,但是有时需要深入的调查还是需要更多的时间.每次迭代都遵循同样的步骤,但是具体的执行方式会跟我们所依赖的设计思维相辅相成.*

#### Think
What do we hope to learn? What questions do we need answered? What are our top risks? Thinking involves creating a plan to learn what we need to answer specific questions or reduce risks.

*我们想学习到什么?我们想寻求什么问题的答案?最大的风险是什么?思考会驱使我们去制定对应的计划来弄清楚我们要搞清楚的具体问题或者降低风险.*

#### Do
Execute the plan. Create something tangible that quickly and cheaply uncovers information needed to check our thinking and share our ideas.

*执行计划就是制定一些可见且能以快速廉价的方式来获取印证我们想法的信息或者分享我们的观点.*

#### Check
Critically examine what we accomplished during the do step so we can decide our next move. The insights coming out of the check step tell us what to do next. Repeat at the think step.

*认真的回顾我们在执行这一步所取得的成果并决定下一步要做的事.在回顾这步中我们获取的洞察力可以帮助我们找到前进的方向,然后再次回到思考这步.*

A software system is never finished; it is only released. Since software is never done, our design approach has no end. Anytime you need to revisit some aspect of the architecture, whether it’s to evolve an existing design or create something new, the same approach applies.

*一个软件系统的开发只会停止而永远也不会结束,因为软件是永远也不会真正的完成所有的需求,所以我们的设计也没有尽头.任何时间你都需要重新去审视软件架构,不管是评估一个已有的设计还是创造新的设计,都是适用的.*

### Adopt Mindsets in Any Order

Think of the four design mindsets like four tool boxes, each containing tools tuned for a particular type of design work. When the need arises, embrace the mindset required to learn more about the world or reduce a risk.

*可以将四种设计思维堪称四个工具箱,每个工具箱都装着适合某种设计工作的工具,当有需求的时候找到需要的思维方法来探索这个世界活着降低风险.*

In the understand mindset, we’ll focus on stakeholders needs and how to specify those needs as requirements. In the explore mindset, we’ll brainstorm ways to solve the problem as we understand it by looking at patterns, technology, and other solutions. In the make mindset, we’ll model the system so we have something concrete to reason about and share. In the evaluate mindset, we’ll put our models and requirements to the test.

*在"理解"这种思维方法中,我们会聚焦在相关人的需求和如果把他们的需求转化为开发需求.在"探索"这种思维中,我们会通过头脑风暴,采取深入了解问题的规律,技术以及其他解决方案来解决问题."实践"的思考方式会让我们对系统建立模型使得我们有具体的东西可以用来探究和分享.在"回溯"这种思维方式中,我们会把我们建立的模型和需求进行验证.*

Mindsets shift frequently and quickly. During a single conversation, we might change mindsets several times. During a workshop, we will create situations that force participants to adopt new mindsets so that we can arrive at a desirable outcome. You’ll see an example of this in Chapter 9, Host an Architecture Design Studio.

*我们的想法经常会变化,在一次交谈中我们就可能多次改变想法.在一次工作会议中,我们会创造条件来迫使与会者接受我们的新的想法,这样大家就在会议输出上可以达成一致.你会在第九章<<主持一个架构设计会议>>中看到具体的例子.*

Experienced architects are often unaware that they attack architecture from varying perspectives. They fly by instinct and adopt different mindsets intuitively (thanks to years of practice). Awareness of the four design mindsets gives us new techniques for getting out of a rut. If you get stuck, choose a new mindset to get yourself unstuck.

*有经验的架构师经常会在不经意中从很多方面改变架构设计,他们会依靠直觉,以及本能地采用不同的思考方式(多亏了长年的实践).对四种思考方式的使用让我们有了新的方法来推进和追溯我们的工作,你可以选择一种新的思考方式来避免被困住.*

### Plot Your Course: Think-Do-Check and Mindsets in Action

Let’s see a concrete example of how the think-do-check cycle and design mindsets might play out in practice. Say a stakeholder just gave us a new constraint and this increases the risk that the architecture will be unable to satisfy performance requirements.

*让我看一个具体的计划-实施-检验的迭代和思维方式在实际应用中的例子,假设有人刚给了我们一个新的需求但是这会导致未来可能架构无法满足性能需求.*

Think. We know system performance is important, but we don’t know what it means to have good performance. Since we need information about the problem, let’s adopt the understand mindset. Looking through some practices in Chapter 14, ​Activities to Understand the Problem​, we decide to capture quality attribute scenarios.

*思考:我们知道系统性能是很重要的,但是我们可能不知道怎样定义系统有好的性能.因为我们需要足够的参考来定位问题,让我们使用"理解"这个思考方式,看看第十四章<怎样理解问题>里面的一些实践,这会让我们决定应该关注质量属性相关的场景.*

Do. We brainstorm some performance scenarios and record them in a document.

*实施:我们会通过头脑风暴来把想到的关于性能的场景记录下来.*

Check. The team and stakeholders review the scenarios and provide feedback.

*检验:团队所有相关人员一起审查这些场景并提出反馈.*

Based on what we learned, new risks arise. Can we achieve the performance quality attribute scenarios given the new constraint?

*基于我们取的的进展,会有新的问题出现.那就是我们能够满足新的需求所涉及的相关质量属性吗?*

Think. Since we need to verify that our decisions promote a specific quality attribute let’s adopt the evaluate mindset. We plan an experiment so we can directly test the constraint’s impact on performance.

*思考:因为我们需要去验证我们提出的为了满足某个质量属性的决策,我们可以采用评估这种思维方式.我们可以创建一个实验来直接的测试新需求对性能的影响.*

Do. We write some simple scripts to drive existing parts of the software system and collect data. We run the experiment.

*实施:我们可以编写一些简单的脚本来运行软件系统已经存在的部分同时收集数据,这就是我们刚提到的实验.*

Check. With data in hand, we examine the results and conclude that the new constraint negatively impacts performance but only by a few 100 milliseconds.

*检验:用了收集的数据,我们就可以检查结果同时发现新的需求只会对性能产生小于100毫秒的负面影响.*

We think we’ve done a thorough job, but performance is funny. Hurting performance might not be a big deal until it degrades too
 much. We need to share these results with our stakeholders and discuss the implications of the new constraint.

*我们认为自己已经完成了一项坚实的工作,不是性能问题是很有趣的.一般性能的降低只有在产生特别明显的现象的时候才会被发现.我们需要和相关人员共享这些结果然后一起讨论新需求的影响.*

Think. Since making ideas tangible facilitates communication, we’ll adopt the make mindset and create a simple prototype. We want stakeholders to experience the impact of the new constraint. Graphs aren’t enough.

*思考:将想法可视化是非常有助于交流的,我们会采用"行动"的方式来创建一个简单的原型,希望相关人员能感受到新需求所带来的影响,因为只依靠图像是不够的.*

Do. We develop a throwaway prototype that demonstrates the application workflow and simulates different assumptions about performance.

*行动:我们会开发一个一次性的原型来展示应用的工作流程同时模拟关于性能在不同场景下的不同表现.*

Check. We give the prototype to our stakeholders and explain why the performance of the system was impacted. On paper, a few 100 milliseconds is tiny, but experiencing the slowdown firsthand shows that this dip in performance isn’t acceptable.

*检验:我们相相关人员展示我们的原型并且解释为什么系统的性能受到了影响.在纸面上的几百毫秒的性能损失不会引人注意,但是一旦在系统中真实的遇到这种性能下降的问题人们就会发现这是完全不可接受的.*

The prototype helped our stakeholders learn something about the problem nobody knew was important until now. Next, we’ll adopt the understand mindset and refine our new requirements. We check our understanding a few minutes in the same meeting by selecting the explore mindset. And the cycle continues.

*我们创建的原型帮助相关人员意识到之前从来没有注意到的那些重要问题.然后我们会采用"理解思维"来重新定义我们的新需求.我们在会议上花几分钟来梳理我们的理解然后在进行下一次迭代.*

The think-do-check cycle is extremely flexible. How you use it depends on the complexity and size of the system, your team’s size and skills, and your experience with having simultaneous design initiatives in flight.

*“思考-行动-回溯”的循环是非常灵活的,如何使用这种方法完全取决于系统的复杂性和大小以及团队的大小和水平,同时也会考验你实时的做出相对应的设计的经验和能力.*

### Next Up
Design thinking gives us a way to connect the highly technical world of software development with the humans affected by the software we build. The four HART principles are the means by which we’ll give our software heart (pun 100 percent intended). Design mindsets are the way we’ll decide what needs to be done to help our stakeholders.

*设计思维让我们能把高度抽象的软件开发的技术领域和相关的人为因素联系在一起.之前提到的四种HART原则就是能赋予软件灵魂的方法.设计思维就是来找出需要帮助相关人士解决问题的核心.*

Now that we’ve covered the theory, it’s time to get down to business.

*现在我们已经介绍完了理论知识,该把理论应用到现实中了.*

Since the invention of software, we have debated how much architecture design should happen up front and how much can emerge as we implement a solution. Like any discussion about extremes, the real answer lies somewhere in the middle. In the next chapter, you’ll see how to define a design strategy appropriate to your situation and choose design mindsets by considering the risks in the software system.

*自从软件被发明以来,人们对于哪些软件架构应该提前做出设计,哪些架构应该在实现过程中再考虑争论不休.就像然后针对极端情况的争论,最终的结论都是中立的.在下一章中,你会看到你如何定义一种正确的设计策略同时针对系统风险来选择对应的设计思维方法.*
