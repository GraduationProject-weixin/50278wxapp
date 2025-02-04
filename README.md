# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50278wxapp微信小程序的体育课评分系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)]()


# 研究背景和来源
目前的网站平台类系统已各种各样，涉及到生活中的每一个部分。购物类、管理类、信息统计类、办公类、官网类等非常丰富。我国各类系统的发展已非常成熟，这些系统依靠网络和计算机技术不断完善发展为人们带来更好的生活体验。而微信小程序类的网站更是多种多样，像企业网、各种订票网等拥有的客户群体都非常大。

受我国教育理念的影响，每个家庭都非常注重学生的体育锻炼，为学生提供最好的锻炼辅助。我国人口众多，竞争压力也越来越大，随着国民经济水平的提升，越来越多的家庭都认识到身体素质的重要性。我国的体育课教育还处在基础阶段，学生锻炼的主要途径是通过老师在学校里传授，这种方式由于学生接受能力不同而造成学生的锻炼效果不同。如果可以由学生为教师打分并提供建议，就可以方便教师根据情况随时调整教学方案。并且教师可以根据不同学生的身体素质记录不同的锻炼数据将会使学生的锻炼事半功倍。
## 1.2课题研究现状
目前对体育课评分的主要途径还是通过传统方式。采用发放问卷由学生填写再由老师统计结果的方式，这种方式对于人数少的学校来说非常适合，但对人数多的学校来说非常困难，统计结果需要大量人员和时间才可以完成。想要提高效率就必需采用其它辅助手段，最有效的方式就是利用管理系统来实现。

我国微信小程序的发展已形成一定的规模，在众多微信小程序里还没有一种是帮助学校来对体育课评分。现在也有一些对老师进行评价的系统，但这类系统是需要借助电脑才可以使用，借助电脑就需要固定地点，使用非常不方便。
## 1.3课题开发的目的和意义
本系统的实现目的在于帮助学校的体育课评分。和传统的评分方式相比，本系统针对性更强，向使用用户展示最为详细的体育教案，学生可以浏览进行评分、发表建议。本系统为免费的体育课评分系统，为老师的体育教学提供帮助。本系统的核心在于内容，以丰富的体育内容取胜，去繁留简，使本系统的用户更容易抓住重点，找到核心内容，减少用户烦躁心理。本系统的实现拥有更大的意义：

1. 本系统功能简单、针对性强，使系统用户更为直观，操作也更为简单，只要有上网经验的用户都可以轻松掌握；
1. 本系统采用多种体育种类，用户可以根据自己的需求选择功能进行操作；
1. 本系统中的体育教案信息都是由老师发布，可以做到正确、精准；
1. 本系统中设有建议功能，可以为老师的教学提供建议，方便老师调整教学方法。
## 1.4课题开发内容
本基于微信小程序的体育课评分系统采用微信端+管理端的方式进行设计。微信端主要为学生操作的功能，管理端为管理员、教师可以操作的功能。在微信端的内容里包括体育教案推荐、校园风采和我的信息。体育教案详情里发布评分和建议。学生在微信端里可以浏览校园风采信息并可以收藏，也可以管理教学评分、学生心率和进行身体素质测评、管理教学比赛成绩、查看运动报告记录。教师可以发布体育教案和查询评分信息以及管理学生的比赛成绩、运动报告记录、心率等信息。管理员在后台的功能为类别管理、用户管理、点名册管理、审核体育教案和评分、管理学生心率和管理比赛成绩以及进行课堂小结管理等。
## 1.5论文结构安排
本篇论文分为摘要、目录、绪论、系统开发关键技术介绍、系统分析、系统设计和系统实现、系统测试、总结、致谢、参考文献。本篇论文的核心集中在系统设计和系统实现部分。绪论部分为基础调研，在系统分析中阐述系统的需求分析、可行性分析和数据流程图、用例图等。

# 第2章 系统开发关键技术介绍
## 2.1系统开发使用的关键技术
本系统在开发中选择微信小程序技术进行设计，语言采用Java，数据库采用Mysql，并在设计中加入Vue技术、SSM框架，本系统的管理端运行环境为IDEA，微信端运行环境为微信开发者工具。

2.2 SSM框架介绍

SSM可以理解为是一个简化版的Spring框架模型，可以直接独立运行于各种开发应用中，从而开发各种产品应用。SSM结合了很多框架到一起的，建立好框架模型好，就可以直接自动生成所需要的所有Spring组件，非常的智能化，不需要自己在单独去写各种xml配置，可以自动配置各种所需要的文件包，使开发更加的简化，如果有自己额外需求，也可以手动进行修改默认值。SSM还直接集成了嵌入式的Servlet容器，所以不需要在额外打包WAR包，可以直接进行自动配置和版本控制。不需要多余的代码生成，开箱即用，这样可以减少垃圾，提高系统的运行效率。而SSM最核心的特色功能就是可以生成独立的微服务单元，就是把所有的代码模块都写在一个单独的应用里，这样功能代码直接的粘合度就非常的高，兼容性更好，而且还可以进行每个功能模块单独部署，不同的模块都能生成不同的小型服务，从而可以进行单独升级，然后实现应用之间的通信。用SSM建立项目的首要步骤就是先配置SSM依赖，建立的时候不需要单独设置版本，直接通过系统自带的场景启动器，就可以直接导入项目所需要的各种web模块，然后在把所需要的功能场景调取出来，生成一个启动器，直接在项目里引入各种依赖的组件就行，然后需要什么功能就导入什么场景就可以了。
## 2.3 Vue框架介绍
Vue是一个用来开发前台界面的JavaScript框架，体积非常的小，所以运行效率非常的高，可以直接通过虚拟设定的 DOM进行各种JavaScript计算，因为操作过程中相当于是一个预处理，所以并没有真实的DOM，也可以称作为一个虚拟的DOM。Vue还可以进行双向的数据绑定，这样操作起来更加的简单，使用户可以不用管DOM对象，直接去操作业务逻辑就可以了，可以应用的场景非常的多，而且开发成本也非常的低。目前的市场后已经有很多成熟稳定的框架组件，可以直接拿来使用，对于初学者来说非常的方便。目前也有好多的前台框架都可以使用，为什么要选择Vue框架呢：因为随着目前科技的进步，前端也需要有很大的业务工作需要处理，网页功能也需要变的更加的强大，才能满足前端开发的需求，而这些都离不开JavaScript框架，现在开发的前台代码都是直接生成到浏览器里来执行，这就自动生成了很多JavaScript代码，然后这些代码是和各种页面布局和样式文件结合在一起的，通过Vue可以进行各种融合；其次通过Vue创建的代码维护性更好，还有很好的可测试性，比如你已经有了服务端的代码应用，可以直接嵌入到Vue中进行使用，从而有更好的交互体验，更好的满足用户需求，也可以根据你的需求直接把业务代码逻辑放到前段代码里实现，满足用户的各种需求，可以进行各种定制化操作。Vue还可以把前台网页代码进行重复使用，直接使用到需要网页渲染的地方，通过Vue进行执行命令，使开发更加的简单。
## 2.4 IDEA介绍
IDEA是公认的最好用Java开发工具之一，常见最多的都是用来跟eclipse进行比较，eclipse可以说是最简单的，但是在兼容方面，代码设计方面明显不足。而IDEA就是在eclipse基础上进行了整合升级，更加智能。IDEA最大的创新就是有智能代码助手，可以实现代码提示，还能进行代码重构，代码审查，非常适合新手的使用。IDEA的宗旨就是实现智能编码，使编码更加的简单，所以在IDEA上有很多其他软件所没有的特色功能，比如进行智能选取，不需要开发者在手动操作，还有各种丰富的导航模式可供选择，可以直接导入就能使用，不需要开发者在重新建立，还有历史记录功能，在误删误操作的情况下，通过这个功能就可以直接恢复。而且idea相比eclipse调试也更简单，通过eclipse调试的时候需要选定表达式，否则就没办法查看它的值，而通过idea则不需要进行任何操作，idea会自动理解你所需要的表达式，然后给你建议参考值。而且在编码方面更加智能，会自动跳出需要的变量和参数，然后建议你最优选择。所以说相比eclipse来说，用idea开发更加的简单方便，更适合新用户的开发使用。
## 2.5 Mysql数据库介绍
数据库主要就是用来存储和管理系统数据的，按照数据结构来进行组织和存储的，数据库都有自己独立的接口来进行创建，访问，管理等，也可以直接用文件的形式进行数据存储，但是读写速度比较慢，效率不高，所以一般都是采用专门的数据库软件来进行数据库存储和管理，这样可以更加科学有效的实现数据的存储，也更加的安全。而mysql就是一个关系型数据库管理系统，可以把各种不同的数据库存储到不同的表结构中 ，这样可以提高查找效率。Mysql是一个开源软件，是面向用户免费的，适合小型项目的开发和使用，而且存储的数据非常的多，存储方式是标准的sql语句形式。支持多种不同的语言开发，比如java ，php，c++等都能很好的兼容，非常适合web语言的开发。而且对于有个性化要求的开发者来说，还支持定制，因为采用的开源的GPL协议，所以开发者可以直接通过修改代码的方式来达到自己的需求。Mysql是一个c/s架构的数据库管理软件，可以直接通过数据库客户端来进行管理操作，主要分为服务端和一个客户端，服务端是安装的时候自动跟谁系统启动的，一般不需要额外操作，使用的时候直接打开客户端就可以，然后输入端口和安装时候设置的密码就可以登录，不用的时候可以断开数据库链接，从而保证数据安全。
## 2.6微信小程序介绍
微信小程序是近几年兴起的一种不需要安装App就可以使用的应用。它是借用微信进行运行的，不占内存，使用方便所以在现实生活中使用率非常大。微信小程序可以通过搜索、扫码就打开应用，属于新的技术，现在多种行业都加入到微信小程序里来，比如各种购物平台、移动运营商、火车票、汽车票等，非常受欢迎。

# 第3章 系统分析
## 3.1系统设计流程分析
一个好的系统在系统设计时需要采用一定的流程才可以顺利开发。首先需要调研使用用户的需求，这里的使用用户不单单普通用户还指系统的管理人员、工作人员，只有充分了解他们的需求才可以设计也符合要求的系统，其次，选择要使用的开发语言和技术、环境，开发语言和技术、环境的选择非常重要，开源的、生命周期长的、兼容性强的技术、环境、语言才可以保证系统的生命周期，接着是研究目前已有相关类似系统的问题和找出可行的解决方案，最后，也是最重要的，需要尽可能的保证系统的先进性，这样才不会过早的被淘汰。
## 3.2系统需求分析
需求分析指在系统开发前确定系统开发是要解决什么问题，以及在系统中如果输入了什么信息，想要得到什么结果，最后呈现了什么结果。简单来说，需求分析就是在问“想要干什么”然后通过“想要干什么”的问题找寻答案。需求分析是非常重要的过程，也是非常困难的过程。需求分析具有系统是否要开发的决定权，同时也为系统后期的开发提供基石。在需求分析阶段需要注意由于系统的使用者和开发者之间难以形成交流而且系统使用者的需求会一直变化，所以在需求分析时要采用动态发展的眼光看问题。

`    `目前想要对体育课评分还是采用传统的方式，效果不好，评分结果也不好统计，不能充分调动老师的教学积极性。想要真正的提高学生的成绩最根本需要老师和学生的共同配合。而本基于微信小程序的体育课评分系统提供体育教案详情，由学生打分和发表建议，还可以提供心率、比赛成绩、身体素质测评和考勤的功能，本基于微信小程序的体育课评分系统前景非常好。
## 3.3系统可行性分析
可行性分析主要是先进行初步调查，然后从各个方面进行系统可行性研究，比如系统需要做什么，采用什么技术，进行各种分析研究，然后得到一个可行性的方案。然后在对方案进行各个功能模块的设计，进行系统设计分析，研究系统设计可行性。所以要从多方面进行考虑，而本文主要从技术上，经济上，操作上，法律上进行研究分析。

3.3.1技术可行性

随着技术的快速发展，各种软件开发技术也在不停的更新，不断的发展，大家都在选择适合自己水平的，能达到开发需求的软件技术和开发环境。所以根据我的开发需求，然后决定开发本系统采用Java语言SSM框架来完成，开发出来的系统可以满足功能需求，而且操作界面美观，符合目前的审美，最重要的是开发相对简单，可以自动生成所需要的框架结构。前端框架采用VUE，数据库Mysql，体积更小，存储速度快，可以满足本次开发的需求。
### 3.3.2经济可行性
经济可行性分析主要是对前期投资进行分析，对系统维护费用分析，对开发完成后取得的经济收益进行分析。因为本系统完全是自己开发的，作为毕业设计用途的，只需要基础的设施就行，需要电脑硬件，开发软件等，不需要额外的投入，完全满足开发需求。而系统开发完成后可以方便用户使用，还能带来一定的经济效益，所以开发本系统在经济上是可行的。
### 3.3.3运行可行性分析
开发本系统过程中已经充分考虑了使用者的感受，界面美观，而且有功能导航栏，方便用户很好的掌握，而且还有各种提示符，哪怕对计算机操作不熟练的也能使用本系统。所以综合考虑，本系统在运行方面是可行的。
### 3.3.4法律可行性
开发本系统过程中参阅的相关资料都是在学校图书馆参阅的，均为正规渠道，而且开发均是本人独立开发的，均是自己的知识储备，全是自己原创的，不存在知识产权，所以才法律上是可行的。
## 3.4系统功能分析
本系统采用功能针对性强、文字描述精确的方式进行设计。本基于微信小程序的体育课评分系统是关于评分的系统，在设计功能时只取用最基础的功能，目的是提供最精准的服务。本系统包括微信端和管理端两部分。

微信端的功能为：

1. 体育教案：展示所有教案信息，学生可以浏览并且进行打分、收藏和建议；
1. 校园风采信息，展示校园风采详情，并且展示校园风采发布时间方便用户了解；
1. 体育教室信息，以图片方式展示体育教室列表，点击体育教室图片展示详情体育教室的描述，感兴趣的体育教室可以查看；
1. 我的功能，在我的功能里用户可以管理点名册、教学评分、学生心率、身体素质测评、教学比赛成绩和运动报告记录、我的收藏信息。

管理端管理员功能：

1. 个人中心，实现密码和个人信息的修改；
1. 类型管理功能，可以更新和删除、修改类型；
1. 点名册管理功能，审核学生的签到信息；
1. 校园风采信息管理功能，可以更新校园风采和进行校园风采的修改、删除；
1. 体育教案管理功能，实现课程的更新和检查；
1. 教学评分功能，查询教师的评分详情；
1. 用户管理功能，实现学生、教师的检查管理；
1. 学生心率管理功能，可以查看学生的心率详情；
1. 身体素质测评管理功能，查看学生的详细身体素质测评内容；
1. 课堂小结管理功能，进行课堂小结；
1. 运动报告记录管理功能，记录学生的运动详情。

教师的功能只有学生管理、点名册管理、体育教案管理、教学评分管理、学生心率管理和身体素质测评管理、课程小结管理、运动报告记录管理、教学比赛成绩管理。这些功能与管理员的相对应功能设计的内容一致。

管理员用例图如下图3.1所示：

![](/md/blog.001.png)

图3.1管理员用例图

学生用例图如下图3.2所示：

![](/md/blog.002.png)

图3.2学生用例图

教师用例图如下图3.3所示：

![](/md/blog.003.png)

图3.3教师用例图
## 3.5系统性能分析
系统性能方面包括系统的框架、系统的开发理念、系统的开发界面原则、系统开发标准、系统开发流程、系统开发安全性、系统运行稳定性等。具体性能分析如下：

1. 本系统是面向所有人群而开发的网站平台，所以在管理端采用的框架模式为B/s，B/s模式是借助浏览器进行系统访问的平台，所有信息可以共享；
1. 系统在设计中采用结构化方式，首先将功能分为大的方面，再由大方面分为小方面，最后分为小细节再整合成完整的系统；
1. 系统在界面设计时采用Vue框架，可以使界面更丰富，元素更多；
1. 系统的操作流程采用简单的思路，使使用用户可以快速掌握本系统；
1. 系统的运行速度要快，所有操作可以快速反映；
1. 在系统开发时要注意系统的资源占用，以最少占用为标准进行设计；
1. 采用发展的眼光看待问题，把系统的生命周期延长到最大；
1. 调查所有使用用户的需求尽可能的满足。
## 3.6业务流程分析
`    `业务流程涉及到系统的每个部分，调查系统在运行中数据会流动的每个环节，以学生注册开始到学生进行评分进行业务流程分析。确保所有信息的流入、流出以及数据的完整性和处理问题的方法。本系统的流程为用户首先通过注册，注册成功后进行登录，登录后可以浏览校园风采信息、体育教案信息，在教案详情里可以收藏教案和评分、发表建议留言，还可以进行身体素质测评和点名、查询比赛成绩等。教师负责添加体育案例信息和点名信息、查询评分信息和进行课程小结等。管理员的功能比教师的多了类型管理、系统管理。本系统的业务流程图如下图3.3所示：

![](/md/blog.004.png)图3.3系统业务流程图
## 3.7系统的界面设计
### 3.7.1界面设计的原则
系统在界面设计时如果遵循一定的原则可以使设计更加顺利，可以减少错误的发生和减少修改错误的次数。系统的界面设计同样非常重要，只有一个好的界面才可以吸引用户使用，也才可以保证留住用户。界面设计的原则一般为：

1. 对于相同功能，比如不同角色的修改个人资料管理采用相同风格进行设计，这样可以养成用户的操作习惯，一眼看过去就知道本功能的作用，不需要再仔细研究；
1. 不同角色的操作界面可以分开设计，这样可以区别角色，在角色的操作界面也需要设置提醒信息，方便用户可以一眼看到当前所登录的角色；
1. 在界面设计时尽量设计可以减少手动打字，手动打字需要时间和精力，并且错误率也会提高，如果改变方式，改成选择、自动这种方式就可以减少用户的打字压力。比如在用户注册时的性别输入上、信息输入的类别上等；
1. 在操作时可以设置尽量多的提示词和提示框来防止用户错误操作和为用户的操作提示指导，比如用户登录不成功后可以提示为什么登录不成功是密码错误还是账号错误。
### 3.7.2信息输入功能的设计原则
为了提高信息输入的正确率，减轻用户的信息输入压力，可以在信息输入功能设计时采用尽可能减少手动输入的原则进行设计。信息输入功能的设计原则有：

1. 可以多选用选择框、列表框等方式减少手动输入，在需要输入大量文字时可以设计可以复制、粘贴，也可以使用特定缩写来代替；
1. 采用固定格式设计来减少用户的错误输入，比如在输入联系方式时，只可以输入数字，当输入其它信息时会提示“格式不正确”，在输入数量时，也可以规定好只可以输入数字。









# 第4章 系统设计
## 4.1系统详细设计和设计原则
详细设计就是首先要确定好打算具体怎么实施这个系统，也就是说，通过这个过程，就要完成系统的具体功能的描述和规划，这样就可以在程序编码的时候直接根据自己规划好的功能模块进行开发。详细设计阶段还并不没有到程序开发阶段，而是要先把程序设计出来，相当于就是一个草稿，先规划好设计的每个步骤，然后代码实施的时候直接编码就行了，不需要在进行系统设计。所以说系统详细设计也是很重要的一步，设计的质量高低也决定了你程序最终的质量，所以首先要进行系统的合理化详细设计，然后还有读懂理解透彻这个程序的设计规划，这样编写代码的时候才不会出现错误，还要检验逻辑是否正确，性能是否满足用户需求，还要看是否容易理解，是否方便操作，要把所有需要考虑的问题都设计好。这样编写代码的时候才能更省事。

开发一个成功的系统首先要有一个明确的定位，就是开发这个系统的目的，然后确定系统的具体实施功能，具体需要投入的费用，然后进行市场可行性分析，最终确定系统是否可行，然后才能开展下一步的工作。只有经过了详细的前期调研，才能避免在系统开发中出现的很多其他问题，保障系统顺利开发进行。所以说一个成功的系统，首先必须方案思路正确，然后在根据需求设计对应的数据结构，开发环境，网络架构，然后构成一个完整的系统，只有这样才能使系统发挥更大的用处。所以通过本思路，开发本系统采用以下具体原则来进行：
`   `（1） 有效性：这里的有效性主要是通过两个层面，首先是有用性，其次还要有可用性。有用性主要是指开发的这个系统有市场需求，是站在用户角度就是实施的，，可用性主要是指用户使用后能满足用户的需求。所以说两个方面都要同时兼顾到，这样开发的系统才是一个好的系统，是一个成功的系统，才能让用户满意。
`   `（2） 兼容性：一个成功的系统必须是可以兼容不同的环境的，要充分考虑到用户不同的硬件下，可以达到一样的效果，必须保证非常好的兼容性。
`   `（3） 安全性：用户安全也是最重要的一个环节，因为目前随着网络信息的发展，用户的数据安全，信息安全，隐私安全都是非常重要。既然把硬件和软件进行合理的充分利用，保证用户资源共享的情况下，还要保证系统数据安全，还要有备份和恢复的功能。每个权限的用户，有自己不同的操作权限，从来保证数据信息安全。
`   `（4） 先进性：开发本系统采用目前比较流行的SSM框架，可以满足开发本系统的所有功能，数据库采用Mysql，数据也有很好的安全存储，采用微软平台上进行开发，这样很好的保证了系统的兼容性和易维护性。
`   `（5） 采用标准技术：开发本系统所用到的各种技术标准均是目前国际现行标准，从而使系统有很好的开放性。
## 4.2系统功能结构设计
`     `本系统的功能界面设计为三个，学生界面、教师界面和管理员界面。根据不同用户的不同需求分开设计功能。学生界面的功能为体育教案、教学评分、学生心率、运动报告记录、身体素质测评、教学比赛成绩等，管理员界面的功能为个人中心、类型管理、校园风采管理、点名册信息管理等。教师界面的功能和管理员的功能少了类型管理和校园风采管理、管理员管理。本系统的功能结构图如下图4.1所示：

![](/md/blog.005.png)                       图4.1系统功能结构图
## 4.3系统数据库设计
数据库就是数据的存储仓库，按照计算机的格式进行数据存入。为了使数据库具有独立性，防止因为系统崩溃而数据有损的问题在数据库建立时都采用单独的数据库。数据库具有共享性和单独性，在系统运行时会自动和相对应的数据进行通讯连接。本基于微信小程序的体育课评分系统采用Mysql数据库设计，身份验证为Root，密码为Root。
### 4.3.1数据库设计过程
数据库主要作为数据库存储，也是系统重要的一步，数据库设计的过程也分为三个阶段来实施，首先是进行数据库需求分析，其次对数据库建立概念模型，最后就是数据库逻辑设计。数据库需求分析就是要弄清楚用户对开发这个系统的明确需求，就是从这个数据库需要实现什么信息，然后具体建立什么类型的表，每个表对应什么数据存储，以及每个字段的设计都要考虑到，为了数据库的安全可靠，所以设计的时候必须站在系统工程的角度进行思考。需求分析阶段，还要站在用户的立场进行考虑，进行数据安全分析，同时进行数据统计和分析用户的需求。数据库建立阶段首先要考虑各个数据字段，日常数据是否能满足基本需求，系统是否安全可靠，性能是否良好，操作是否方便，还有后期维护等。最后就是数据库功能实施阶段，主要就是数据的增删改查，是否能正确的进行操作，是否满足系统需求。

数据库设计分为两部分，数据库概念设计和数据库逻辑设计。数据库概念设计主要是设计数据的ER图，数据库逻辑设计主要是设计数据的数据库表。
### 4.3.2数据库ER图设计
数据库ER图设计时采用的是自底向上的方式，首先从使用者的角色进行视图设计，然后把设计的这些视图进行整合，最后根据整合进行分析，得出结果。ER图是采用实体、联系的方式进行设计，ER图中的内容包括实体、属性、关系。实体是指系统中在工作时所使用的数据，属性是实体所包括的内容描述，关系是指实体与实体之间的联系。

根据分析所得本系统中主要的数据为管理员、学生、体育教案信息、校园风采信息、身体素质信息、心率信息等。所以本节针对这些数据画出数据ER图。

（1）管理员实体的属性为用户名和密码。管理员实体ER图如下图4.2所示：

![](/md/blog.006.png)

图4.2管理员实体ER图

（2）学生实体的属性为编号、姓名、班级、专业等。学生实体ER图如下图4.3所示： 

![](/md/blog.007.png)

图4.3学生实体ER图

（3）体育教案信息实体的属性包括标题、图片、内容等。体育教案信息实体ER图如下图4.4所示：

![](/md/blog.008.png)

图4.4体育教案信息实体ER图

（4）校园风采实体的属性包括编号、标题、内容、添加时间等。校园风采实体的ER图如下图4.5所示：

`　　　　　　`![](/md/blog.009.png)

图4.5校园风采实体ER图

（5）类别信息实体的属性包括编号和名称。类别信息实体ER图如下图4.6所示：

`　`![](/md/blog.010.png)

图4.6类别信息实体的ER图

（6）本系统的关系ER图如下图4.7所示：

![](/md/blog.011.png)

图4.7系统关系ER图
### 4.3.3数据库表设计
本系统针对体育课的网上评分而设计，所以本系统的数据库表围绕体育课而建立。本系统的数据库表包括体育教案信息表、用户信息表、教学评分信息表等。本系统的数据库表结构如下图4.1－4.16 所示：

表4.1 config

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|name|varchar|100| | | | |否| | |
|3|value|varchar|100| | | | |是| | |

||
| :- |
表4.2 dianmingce

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|qiandaobianhao|varchar|200| | | | |是| | |
|4|riqi|date| | | | | |是| | |
|5|jiaoshixingming|varchar|200| | | | |是| | |
|6|kaoqinzhuangkuang|varchar|200| | | | |是| | |
|7|beizhu|varchar|200| | | | |是| | |
|8|qiandaotupian|varchar|200| | | | |是| | |
|9|xuehao|varchar|200| | | | |是| | |
|10|xingming|varchar|200| | | | |是| | |
|11|userid|bigint|20| | | | |是| | |

||
| :- |
表4.3 discusstiyujiaoan

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|refid|bigint|20| | | | |否| | |
|4|userid|bigint|20| | | | |否| | |
|5|nickname|varchar|200| | | | |是| | |
|6|content|longtext| | | | | |否| | |
|7|reply|longtext| | | | | |是| | |

||
| :- |
表4.4 jiaoshi

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|jiaoshixingming|varchar|200| | | | |否| | |
|4|mima|varchar|200| | | | |否| | |
|5|xingbie|varchar|200| | | | |是| | |
|6|zhicheng|varchar|200| | | | |是| | |
|7|dianhua|varchar|200| | | | |否| | |
|8|youxiang|varchar|200| | | | |是| | |
|9|touxiang|varchar|200| | | | |是| | |
|10|banji|varchar|200| | | | |否| | |
|11|beizhu|varchar|200| | | | |是| | |

||
| :- |
表4.5 jiaoxuebisaichengji

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|yundongxiangmu|varchar|200| | | | |否| | |
|4|xingming|varchar|200| | | | |是| | |
|5|xiangmutupian|varchar|200| | | | |是| | |
|6|xuehao|varchar|200| | | | |是| | |
|7|chengji|varchar|200| | | | |否| | |
|8|pingyu|varchar|200| | | | |是| | |
|9|riqi|date| | | | | |是| | |
|10|jiaoshixingming|varchar|200| | | | |是| | |
|11|userid|bigint|20| | | | |是| | |

||
| :- |
表4.6 jiaoxuepingfen

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|ketangmingcheng|varchar|200| | | | |是| | |
|4|jiaoshixingming|varchar|200| | | | |是| | |
|5|leixing|varchar|200| | | | |是| | |
|6|tupianfengmian|varchar|200| | | | |是| | |
|7|jiaochengfenxi|varchar|200| | | | |是| | |
|8|shejilinian|varchar|200| | | | |是| | |
|9|jiaoxuemubiao|varchar|200| | | | |是| | |
|10|jiaoxuezhunbei|varchar|200| | | | |是| | |
|11|jiaoxuezhongdian|varchar|200| | | | |是| | |
|12|jiaoxuepingfen|float| | | | | |否| | |
|13|yijianjianyi|varchar|200| | | | |是| | |
|14|pingfenshijian|datetime| | | | | |是| | |
|15|xuehao|varchar|200| | | | |是| | |
|16|xingming|varchar|200| | | | |是| | |

||
| :- |
表4.7 ketangxiaojie

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|ketangmingcheng|varchar|200| | | | |否| | |
|4|ketangneirong|longtext| | | | | |否| | |
|5|xiaojieneirong|longtext| | | | | |否| | |
|6|yijian|varchar|200| | | | |否| | |
|7|ketangshijian|datetime| | | | | |是| | |
|8|banji|varchar|200| | | | |是| | |
|9|jiaoshixingming|varchar|200| | | | |是| | |
|10|dengjishijian|datetime| | | | | |是| | |

||
| :- |
表4.8 leixing

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|leixing|varchar|200| | | | |否| | |

||
| :- |
表名：news

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|title|varchar|200| | | | |否| | |
|4|introduction|longtext| | | | | |是| | |
|5|picture|varchar|200| | | | |否| | |
|6|content|longtext| | | | | |否| | |

||
| :- |
表4.9 shentisuzhiceping

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|xuehao|varchar|200| | | | |是| | |
|4|xingming|varchar|200| | | | |是| | |
|5|zhaopian|varchar|200| | | | |是| | |
|6|xingbie|varchar|200| | | | |是| | |
|7|jiaoshixingming|varchar|200| | | | |是| | |
|8|shengao|float| | | | | |是| | |
|9|tizhong|float| | | | | |是| | |
|10|xuetang|float| | | | | |是| | |
|11|xinlv|float| | | | | |是| | |
|12|xiongwei|float| | | | | |是| | |
|13|xuezhi|float| | | | | |是| | |
|14|feihuoliang|float| | | | | |是| | |
|15|woli|varchar|200| | | | |是| | |
|16|beizhu|varchar|200| | | | |是| | |
|17|dengjishijian|date| | | | | |是| | |
|18|userid|bigint|20| | | | |是| | |

||
| :- |
表4.10 storeup

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|userid|bigint|20| | | | |否| | |
|4|refid|bigint|20| | | | |是| | |
|5|tablename|varchar|200| | | | |是| | |
|6|name|varchar|200| | | | |否| | |
|7|picture|varchar|200| | | | |否| | |
|8|type|varchar|200| | | | |是|1| |
|9|inteltype|varchar|200| | | | |是| | |

||
| :- |
表4.11 tiyujiaoan

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|ketangmingcheng|varchar|200| | | | |是| | |
|4|jiaoshixingming|varchar|200| | | | |是| | |
|5|leixing|varchar|200| | | | |是| | |
|6|tupianfengmian|varchar|200| | | | |是| | |
|7|jibenshuoming|longtext| | | | | |是| | |
|8|jiaochengfenxi|varchar|200| | | | |是| | |
|9|shejilinian|varchar|200| | | | |是| | |
|10|jiaoxuemubiao|varchar|200| | | | |是| | |
|11|jiaoxuezhunbei|varchar|200| | | | |是| | |
|12|jiaoxuezhongdian|varchar|200| | | | |是| | |
|13|jiaoxuewenjian|varchar|200| | | | |是| | |
|14|zhidingshijian|datetime| | | | | |是| | |
|15|clicktime|datetime| | | | | |是| | |

||
| :- |
表4.12 token

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|userid|bigint|20| | | | |否| | |
|3|username|varchar|100| | | | |否| | |
|4|tablename|varchar|100| | | | |是| | |
|5|role|varchar|100| | | | |是| | |
|6|token|varchar|200| | | | |否| | |
|7|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|8|expiratedtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |

||
| :- |
表4.13 users

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|username|varchar|100| | | | |否| | |
|3|password|varchar|100| | | | |否| | |
|4|role|varchar|100| | | | |是|管理员| |
|5|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |

||
| :- |
表4.14 xuesheng

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|xuehao|varchar|200| | | | |否| | |
|4|xingming|varchar|200| | | | |否| | |
|5|mima|varchar|200| | | | |否| | |
|6|xingbie|varchar|200| | | | |是| | |
|7|shenfenzheng|varchar|200| | | | |是| | |
|8|shouji|varchar|200| | | | |是| | |
|9|youxiang|varchar|200| | | | |是| | |
|10|xueyuan|varchar|200| | | | |是| | |
|11|zhuanye|varchar|200| | | | |是| | |
|12|banji|varchar|200| | | | |是| | |
|13|zhaopian|varchar|200| | | | |是| | |
|14|jiaoshixingming|varchar|200| | | | |是| | |

||
| :- |
表4.15 xueshengxinlv

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|xuehao|varchar|200| | | | |是| | |
|4|xingbie|varchar|200| | | | |是| | |
|5|xingming|varchar|200| | | | |是| | |
|6|zhaopian|varchar|200| | | | |是| | |
|7|wodexinlv|int|11| | | | |是| | |
|8|beizhu|varchar|200| | | | |是| | |
|9|jiaoshixingming|varchar|200| | | | |是| | |
|10|dengjishijian|datetime| | | | | |是| | |
|11|userid|bigint|20| | | | |是| | |

||
| :- |
表4.16 yundongbaogaojilu

||
| :- |

|序号|列名|数据类型|长度|小数位|标识|主键|外键|允许空|默认值|说明|
| :- | :- | :- | :- | :- | :- | :- | :- | :- | :- | :- |
|1|id|bigint|20| |是|是| |否| |auto\_increment|
|2|addtime|timestamp| | | | | |否|CURRENT\_TIMESTAMP| |
|3|baogaomingcheng|varchar|200| | | | |否| | |
|4|yundongdidian|varchar|200| | | | |是| | |
|5|yundongshizhang|varchar|200| | | | |是| | |
|6|yundongtupian|varchar|200| | | | |是| | |
|7|yundongneirong|longtext| | | | | |是| | |
|8|baogaoneirong|longtext| | | | | |是| | |
|9|jiluriqi|date| | | | | |是| | |
|10|beizhu|varchar|200| | | | |是| | |
|11|xuehao|varchar|200| | | | |是| | |
|12|xingming|varchar|200| | | | |是| | |
|13|banji|varchar|200| | | | |是| | |
|14|jiaoshixingming|varchar|200| | | | |是| | |
|15|userid|bigint|20| | | | |是| | |

||
| :- |



# 第5章 系统实现
## 5.1微信端界面的实现
### 5.1.1首页界面的实现
`   `本功能设计的目的是帮助用户一键返回首页，在首页里的元素包括图片、列表框、文字、导航栏等。在首页的上半部分轮播图、中间是体育教案推荐、下面是体育教案。导航栏里是首页、体育教案、校园风采、我的功能按键。首页界面的实现界面如下图5.1所示：

![](/md/blog.012.png)

图5.1首页界面的实现效果
### 5.1.2体育教案功能的实现界面
在体育教案功能里可以看到课程类型，点击体育教案功能可以看到教案的详情，并可以对教案进行评分和提出建议。体育教案功能的实现界面如下图5.2所示：

![](/md/blog.013.png)

图5.2体育教案功能的实现界面

学生评分的实现界面如下图5.3所示：

![](/md/blog.014.png)

图5.3学生评分的实现界面
### 5.1.3校园风采功能的实现界面
本界面里可以看到校园的风采信息，实现界面如下图5.4所示：

![](/md/blog.015.png)

图5.4校园风采的功能实现界面
### 5.1.4教学评分功能的实现界面
在本功能模块里展示已评分的体育教案，想要看具体的评分详情需要点击教案标题进入详情页。教学评分功能的实现界面如下图5.5所示：

![](/md/blog.016.png)

图5.5教学评分功能的实现界面
### 5.1.5学生心率功能的实现界面
学生可以添加和管理自己的心率，在填写心率时可以选择教师。添加学生心率信息功能的实现界面如下图5.6所示：

![](/md/blog.017.png)

图5.6添加学生心率信息功能的实现界面
### 5.1.6身体素质测评功能的实现界面
本界面展示了学生的具体身体素质各项数据。学生查询身体素质测评功能的实现界面如下图5.7所示：

![](/md/blog.018.png)

图5.7查询身体素质测评功能的实现界面
### 5.1.7教学比赛成绩功能的实现界面
学生可以查询比赛的成绩。查询教学比赛成绩功能的实现界面如下图5.8所示：

![](/md/blog.019.png)

图5.8查询比赛成绩功能的实现界面
### 5.1.8运动报告记录功能的实现界面
同样学生也可以查询自己的运动报告记录数据。运行报告记录功能的实现界面如下图5.9所示：

![](/md/blog.020.png)

图5.9运行报告记录功能的实现界面
## 5.2管理员功能的实现界面
管理员的功能为管理微信端信息和更新微信端信息以及管理用户信息。管理的微信端信息包括体育教案信息、校园风采信息和类型信息、用户信息等。管理员功能的实现界面如下图5.10所示：

![](/md/blog.021.png)

图5.10管理员功能的实现界面
## 5.3教师管理功能的实现界面
教师的功能与管理员的功能类似，缺少管理员信息管理、系统管理和类型管理。教师管理的实现界面如下图5.11所示：

![](/md/blog.022.png)

图5.11教师管理功能的实现界面
# 系统测试










