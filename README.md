# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0372springboot驾校预约学习系统--论文pf

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1T1bpekEK7?p=45)


# 第1章 绪论
## 1.1 课题背景
二十一世纪互联网的出现，改变了几千年以来人们的生活，不仅仅是生活物资的丰富，还有精神层次的丰富。在互联网诞生之前，地域位置往往是人们思想上不可跨域的鸿沟，信息的传播速度极慢，信息处理的速度和要求还是通过人们骑马或者是信鸽传递，这些信息传递都是不可控制的，中间很有可能丢失，信息的传递水平决定了人们生活的水平。如今大家都在使用互联网软件产品，从内部管理设置计算机管理，提高内部信息化的管理水准，从外部市场也可以用计算机获取相关数据进行处理，如今各行各业已经严重依赖于计算机了。

本课题研究和开发驾校预约学习系统管理系统，让安装在计算机上的该系统变成管理人员的小帮手，提高驾校预约学习系统信息处理速度，规范驾校预约学习系统信息处理流程，让管理人员的产出效益更高。
## 1.2 课题意义
传统处理数据，必须是一张张纸，然后处理完毕又是统计在一张张纸上面，不断的重复处理，最终有个结果给最高层作为参考，这个模式在互联网没有出现之前，是一种常见的事情，信息管理的效率提不上去，人多不一定力量大，因为人多肯定更加消耗资源，并且因为人类需要休息，需要管理，思想会不统一，会偷懒，所以人们研究出专门帮助人们计算的机器，就是计算机的前身，到了互联网时代，人们发现完全可以让程序供应商提供解决方案，自己挑选自己合适的方案来提高自己的产出比。所以在日常工作和生活中会发现各种各样方便人们的工具。

本课题研发的驾校预约学习系统管理系统，就是提供驾校预约学习系统信息处理的解决方案，它可以短时间处理完信息，并且这些信息都有专门的存储设备，而且数据的备份和迁移都可以设定为无人值守，从人力角度和信息处理角度以及信息安全角度，驾校预约学习系统管理系统是完胜传统纸质操作的。
## 1.3 研究内容
本文对驾校预约学习系统管理系统的设计与实现分成六个章节来说明。

第1章：研究驾校预约学习系统管理系统的背景，以及开发驾校预约学习系统管理系统的意义。

第2章：对开发驾校预约学习系统管理系统的环境还有技术进行说明。

第3章：分析驾校预约学习系统管理系统的可行性，性能，流程以及功能。

第4章：设计驾校预约学习系统管理系统的功能结构，设计数据库E-R图以及对数据表的存储结构进行设计。

第5章：实现驾校预约学习系统管理系统的功能并进行功能界面展示。

第6章：对系统测试进行阐述，以及对本系统部分功能进行检测。
# 第2章 开发环境与技术
本章节对开发驾校预约学习系统管理系统需要搭建的开发环境，还有驾校预约学习系统管理系统开发中使用的编程技术等进行阐述。

2.1 MySQL数据库

MySQL是一种具有安全系数、安全系数、混合开发性、高效化等特征的轻量关联数据库智能管理系统。MySQL由C语言和C语言构成  由C语言和C语言撰写成的，由于C语言和C语言  这是混合开发的，因此MySQL源码是生命期的。MySQL提供多种多样数据种类，常见的数据种类包含[34]。伴随着数据库技术发展，MySQL逐步形成数据库管理方法的重要工具之一。它不仅能提供简单实用的操作作用，还能实现复杂多变的数据检索方法和查询记录导出方式。因为MySQL具有较好的兼容模式和扩展性，因而广泛应用于各行各业。

MySQL在WEB行业越来越受单位和个人开发者的亲睐。大部分大中小型网址都采用MySQL数据库，它不仅可以提供简单高效的数据浏览作用，还会对数据进行相应的剖析解决。因为Linux电脑操作系统和MySQL数据库全是开源系统免费体验，能够为公司节约许多费用，让很多企业使用Linux   MySQL做为网址数据库，体型小，启动速度快，也不会影响网址性能，导致用户体验感极差。

MySQL数据库能够支持各种各样操作系统的运作，包含AIX、HP-UX、OS/2 Wrap、Solaris、Mac OS、Linux和Windows等。性能好，使用便捷。因而，MySQL数据库已成为当下数据库行业最流行产品之一。MySQL数据库系统使用面向对象设计方式，客户至上开展编程设计。是利用面向对象观念来达到各项功能。它不仅能管理方法大中型数据表或关系数据库，还可以把这种复杂且庞大信息系统集成到一个简单的中小型数据库系统内。现阶段，中国很多公司早已运用了这一尖端技术。但是由于该操作系统是根据远程服务器/服务器结构的（C/S），因而，存在一些缺陷：最先，系统软件不可以提供完备的数据访问接口，客户只能依靠浏览器浏览所需要的数据；次之，系统软件并没有统一的标准，不同类型的客户端难以实现数据分享；第三，系统软件没有很好的权限管理体制。
## 2.2 Java语言技术
Java语言已经存在了25年有余。通过这些年的发展趋势，it行业在市场占有率上仍然占据一半，仍然受到了很多程序员的工作钟爱。许多从业者都是在学习培训。近年来随着从业者的提高，Java语言的位置并没减少，算得上是常青藤。Java语言学习培训比较简单，自然，它是对于C前辈们的  而言的，C  语言非常强劲。Java取消了许多特点，如go这种描述，也取消了主文件，让所有文件夹全是类，类是二维数组以及各种对象，也使Java处理一些对象的引入和回收利用，让开发者只需建立对象，应用对象，编写代码逻辑，不需要留意性能，让各种各样文件存储给Java自己解决，你能花很多时间科学研究应用软件相互关系，使研发更为集中化，如同跑车驾驶员一样，只要了解各种汽车的性能，实际操作，不需要科学研究如何生产车轮子，使软件开发更为详尽。
## 2.3 Spring Boot框架
Spring Boot框架是一个SpringMVC架构的快速轻量快速框架，能够帮助开发人员迅速搭建靠谱高效率的应用程序。依据自动部署和协议书，改善了Spring的研究过程，使开发人员可以更加专注于领域模型。

Spring Boot有许多特性，当中最主要的是它提供了内置Tomcat、Jetty、Undertow等Web网络服务器能够轻松搭建Web应用程序。除此之外，它也提供自动部署、无需撰写XML文件等功能。这种功能使开发人员能够迅速建立和布署应用程序，而无需解决繁杂的环境变量和其它繁琐复杂每日任务。

开发系统时，Spring Boot能够帮助开发人员完成模块化设计和松耦合的代码结构，从而更好地日常维护拓展应用程序。除此之外，它也提供了很多常见的库和部件，如Spring Data、Spring Security等，能够轻松集成化这种部件，完成数据库操作、验证、受权等功能。

## 2.4 其他技术使用
Spring-jdbc联接：

这是一个专业生产制造Connection对象工厂类，大部分全部用以建立数据库联接框架都是会完成这一插口，Springjdbc包就实现了这一插口，实现类是DriverManagerdasource、现阶段的项目是由DataSource的getconection方式获得配备MYSQL5.7数据库连接信息。

提交Fileupload文件：

项目中应用Fileupload完成文件提交，通常是Fileupload前面提交文件提交请求，请求形式为POST：<form action="uploadServlet" method="post" ....="">请求编码方式：等候文件提交，启用Fileitem的isformField()方式，判断出表格域到底还是不是表格域，文件提交到后台管理，应用Fileupload接受文件信息，并把文件解决包存储在硬盘和库中。

Alibaba驱动：

比照各大网站Alibaba.Druid是JAVA语言中比较好的数据库连接池。Druid可提供强有力的拓展和监控功能。该项目应用Alibababa.Druid开展数据库系统连接，Druid 0.1.18 以后，全部版本号都分享到maven中央仓库，在项目pome中.在xml里加入dependency就可以使用。

log4j日志：

驾校预约学习系统其全世界错误处理和日志信息纪录，应用log4j开展日志日常维护管理与查询，其核心优势是错误处理：在logback中，应用软件里的出现异常不被应用软件认知，特性提升，关键或没有废弃物体制，log4j在很多情况下，可采取设计的一套无废弃物体制，防止经常日志搜集所引起的jvm gc。操作方法很简单，在pom中.新增log4j有关jarxml就可以。

# 第3章 系统分析
本文作者在确定了研究的课题之后，从各大数字图书馆下载文献来阅读，并了解同类型的网站具备的大致功能，然后具体事务具体分析，得出本系统要研究的具体功能与性能。虽然分析系统这一阶段性工作主要是确定功能，但它却影响着后面系统开发环节的进展，系统分析这个环节是不能少的。
## 3.1 可行性分析
从三个不同的角度来分析，确保开发成功的前提是有可行性分析，只有进行提前分析，符合程序开发流程才不至于开发过程的中断。
### 3.1.1技术可行性分析
研发设计程序流程挑选面向对象设计、功能齐全、简单实用的Java编程设计核心理念。MySQL数据库存储数据。IDEA工具作为编程软件，Windows 10计算机操作系统作为应用系统，以及数据库可视化工具等技术职称。一般来说，该程序流程的开发能够从技术上开展是可行的。
### 3.1.2经济可行性分析
开发的程序并不是向着商业程序方向设计与开发的，反而是做为一个新的毕业论文新项目开发的。它主要运用于检测小朋友们在院校所学的知识，并锻练客户使用网络、书籍和其他方式自学能力。因而，程序软件的开发不容易涉及到边际收益，也不会为软件的挑选付钱。你可以在开发软件的官网上下载所需要的软件，并依据所需要的安装方法将应用安装到你的电脑里。一般来说，开发这一程序并没有社会经济发展花费。
### 3.1.3运行可行性分析
由于程序软件就是针对大部分一般操作用户，考虑到他的知识与文化水准，尤其开发了一个可操作度高的程序软件，能够轻而易举地让用户应用，数据可视化操作页面。一般来说，从用户操作程序的角度看，这一程序其实并不难操作。只需用户开启程序，就能避免专职人员学习培训开展程序作用操作。
## 3.2 系统流程
驾校预约学习系统管理系统投入使用后，使用者如果能看到相应的流程操作图会提高程序的理解能力。
### 3.2.1 操作流程
使用者在操作驾校预约学习系统管理系统中，应该按照本系统提供的操作流程（图3.1即为本系统的操作流程图）进行操作，可以减少操作失误，从而节省进入驾校预约学习系统管理系统的时间。

![](/md/blog.001.png)

图3.1 系统操作流程
### 3.2.2 登录流程
驾校预约学习系统管理系统通过登录功能（图3.2即为其登录的流程）引导使用者进入指定的功能操作区，也避免非本系统的用户享受本系统提供的服务以及查看本系统提供的信息，进而保证用户安全。

![](/md/blog.002.png)

图3.2 登录流程
### 3.2.3 删除信息流程
驾校预约学习系统管理系统在经过长期使用后，会产生很多的数据信息。为了腾出存储空间存放更多的数据，本系统数据库中存储的数据，一些没有参考价值的数据需要进行删除（图3.3即为删除信息的流程），删除数据过程中，为避免误删，使用者要根据系统的提示来决定是否删除数据。

![](/md/blog.003.png)

图3.3 删除信息流程
### 3.2.4 添加信息流程
驾校预约学习系统管理系统提供可视化的功能操作区，非常方便使用者进行数据操作，当使用者往系统中录入数据时（图3.4即为添加信息的流程），本系统也会进行数据合法性的判断，符合要求的数据才能够在数据库指定表中进行登记。

![](/md/blog.004.png)

图3.4 添加信息流程
## 3.3 性能需求
需求分析少不了对项目用到的硬件设备进行分析，这样才符合正常的分析流程。只谈功能需求不谈性能需求，是一件很严重的事情，可能会导致一些不可控的问题出现。

以下从这几个角度来分析系统性能。

(1)系统数据的容量：从数据角度来分析，每个表和每个数据库，达到的数据量到一定的程度，是否需要分表或者是分库，超过了数据的设定限度，可能会导致数据反映迟钝，容错量增加。

(2)数据精度的要求：需要对需求分析里面数据设定环节，考虑相应的数据精度问题，需要发现数据是常用的精度还是非常用的精度，进而设定不同的数值。

(3)时间响应要求：从用户提交操作，到页面反映，中间有个数据处理的问题，需要考虑预测数据量的大小，提前预案分库分表的设计，数据量再大就要考虑增加列式数据库的问题，这些都不是一拍脑门就能决定的，都需要经验和同行业的数据分析研判，才能符合用户的要求，毕竟响应时间太久操作起来也不舒服。

(4)普适性问题：用户使用应该不需要感知服务端的数据量问题或者响应问题，只需要任意一台电脑，不需要更多的操作，打开浏览器就能用，太多的设置以及操作，不符合普适性操作。

(5)页面设计问题：功能符合要求之后，肯定是要丰富页面的。页面设计才是用户长时间面对的问题，首先考虑数据的整洁性，让页面看起来更加的清爽。颜色与数据方面，该不同颜色就不同颜色，降低用户长时间使用出现的视觉疲劳，让用户使用起来心情不至于太差。

(6)系统的稳定性：正常用户操作系统页面，必须是该提交提交，正常输入符合逻辑，不能随随便便的就出各种问题，导致用户操作疲惫，并且输入的数据和回显的数据符合用户的要求。如果正常操作都会出现问题，那设计就是不稳定的，这一点肯定不行。只要是与数据进行交互的系统，都必须稳定。系统稳定从开发部署角度上来分析，可以考虑数据的冗余备份功能，自动值守功能，机房数据同步，机房分开的功能，这些都可以让系统的稳定性得到提升。

系统的性能需求需要对业务很熟练的情况下判断然后分析，再从系统性能需求来逐条实现，可以让设计的系统有使用价值。
# 第4章 系统设计
用户对着浏览器操作，肯定会出现某些不可预料的问题，但是不代表着系统对于用户在浏览器上的操作不进行处理，所以说，要提前考虑可能会出现的问题。
## 4.1 系统设计思想
系统设计，肯定要把设计的思想进行统一，只有统一的思想才能指导程序的开发，并且可以让众多的程序开发人员更快速的进入状态，提高开发速度。根据当前系统的既定需求，下面将进行本系统设计思想的阐述。

(1)扩展性：开发任何一个系统的时候不可避免要考虑这个问题。软件版本的更迭是一种常识，任何一个软件都不会一次性开发就成永恒，软件是一个不断成长的东西。所以考虑问题的时候需要对当前问题进行数据上的扩大化，然后进行归纳整理，最终形成具有一定扩展性的程序。程序的可扩展性必然会影响开发进度，所以最终需要综合评估程序的可扩展程度，进而有的放矢，循序开发。

(2)实用性：程序设计是一个先高屋建瓴式的设想，然后再具体化，实用性就是具体化的第一个步骤，要充分考虑使用者是不懂程序设计的这一点，使用者只是懂得常规性的上网操作步骤，并不需要对程序进行理解，所以一定要让使用者感觉到便利，感觉到实用性的存在，如果使用者使用程序过程中没发现使用程序的好处，那么程序设计的实用性将大大降低。

(3)安全性：当使用者使用的过程中，会产生大量的相关数据，这些数据必须有安全性的保证，否则当使用者发现数据出现问题的原因是程序设计问题的时候，将会对程序开发者失去信任，甚至可能会产生大量的费用赔偿问题，这是一个不可避免的问题。所以安全性关系开发与使用者双方的经济利益，程序的安全性是一定要保证的。

(4)先进性：程序设计的先进性是开发者进行考虑的，必须要在满足系统功能的前提下，必须要选择好当下最合适的技术。最合适的技术要从开发成本，使用成本以及维护成本里面综合分析，经过综合分析后要让技术实现最优解，保持先进的技术生产力。

(5)维护性：程序开发之初就要考虑以后的维护问题。维护是在程序开发完毕，已经上线可以运作，进入生产试用过程和使用过程中才会发现需要维护的必要。要通过各方面降低维护成本，不是说维护的越少就代表程序开发的越完美，程序既然是人类进行设计制造的，肯定有很多不可避免的问题产生，那么如何维护好程序的正常运作也是一门很重要的学问。
## 4.2 功能结构设计
图4.1即为设计的管理员功能结构，管理员权限操作的功能包括管理公告，管理驾校预约学习系统信息，包括学习资料管理，培训管理，考试管理，薪资管理等，可以管理公告。

![结构设计图](/md/blog.005.jpeg "结构设计图")

图4.1 管理员功能结构
## 4.3 数据库设计
驾校预约学习系统管理系统运行中产生的数据需要按照提前设置的存储规则进行保存，设计出一个符合项目的最优数据存储格式，因为它能减少用户的等待时间，还可以对系统的请求在最短时间内进行响应。所以，对数据库设计时，需要对功能需求进行详细的拆分，以及对业务状态的细分，然后设计具体的存储规则，保证数据库能正常运作，缩短数据处理时间，并在一定程度上降低数据冗余，节省存储空间。
### 4.3.1 数据库概念设计
实体-联系图还有一个名称即E-R图，是Entity Relationship Diagram各英文单词首字母的缩写，它这种概念模型通常用于对现实世界进行描述。同时它还是一种能够直观表达数据中实体，联系，属性的有效手段。绘制E-R图能够选择的工具也有很多，但是Office Visio 这款软件在E-R图的绘制上一般都是作为首选工具，因为它是基于可视化处理，使用它创建E-R图非常简单。使用基本的E-R图构成元素，比如椭圆，菱形，矩形，还有实线段来表达对应的信息，椭圆代表属性，即实体的特征，矩形代表实体，即数据库中的一个具体数据表，菱形代表实体中相互关系，实线段主要是完成椭圆，矩形，菱形的连接。

（1）下图是用户实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\用户.jpg](/md/blog.006.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\用户.jpg")
用户实体属性图

（2）下图是考试记录表实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\考试记录表.jpg](/md/blog.007.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\考试记录表.jpg")
考试记录表实体属性图

（3）下图是答题详情表实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\答题详情表.jpg](/md/blog.008.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\答题详情表.jpg")
答题详情表实体属性图

（4）下图是公告信息实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\公告信息.jpg](/md/blog.009.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\公告信息.jpg")
公告信息实体属性图

（5）下图是教练实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\教练.jpg](/md/blog.010.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\教练.jpg")
教练实体属性图

（6）下图是试卷选题实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\试卷选题.jpg](/md/blog.011.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\试卷选题.jpg")
试卷选题实体属性图

（7）下图是学习资料收藏实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\学习资料收藏.jpg](/md/blog.012.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\学习资料收藏.jpg")
学习资料收藏实体属性图

（8）下图是错题表实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\错题表.jpg](/md/blog.013.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\错题表.jpg")
错题表实体属性图

（9）下图是教练预约实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\教练预约.jpg](/md/blog.014.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\教练预约.jpg")
教练预约实体属性图

（10）下图是学习资料实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\学习资料.jpg](/md/blog.015.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\学习资料.jpg")
学习资料实体属性图

（11）下图是留言板实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\留言板.jpg](/md/blog.016.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\留言板.jpg")
留言板实体属性图

（12）下图是学习资料留言实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\学习资料留言.jpg](/md/blog.017.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\学习资料留言.jpg")
学习资料留言实体属性图

（13）下图是试卷实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\试卷.jpg](/md/blog.018.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\试卷.jpg")
试卷实体属性图

（14）下图是试题表实体和其具备的属性。

![C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\试题表.jpg](/md/blog.019.jpeg "C:/Users/Administrator/Desktop/temp111\1\\_\_\_\_img\试题表.jpg")
试题表实体属性图
### 4.3.2 数据库物理设计
本小节主要任务即是根据上述内容进行数据存储结构的设计，实体的属性就用来表示字段名称，不同的字段表示的数据类型以及取值都不相同，以及该表各个字段是否能够保持空等进行说明，设计完成一张数据表的结构之后，在保存时同样要命名，尽量选择英文名称进行命名并保存，还不容易导致系统出错。接下来就对设计的表进行简单说明。

表4.1字典表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|dic\_code|String|字段|是|
|3|dic\_name|String|字段名|是|
|4|code\_index|Integer|编码|是|
|5|index\_name|String|编码名字|是|
|6|super\_id|Integer|父字段id|是|
|7|beizhu|String|备注|是|
|8|create\_time|Date|创建时间|是|
表4.2试卷表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|exampaper\_name|String|试卷名称|是|
|3|exampaper\_date|Integer|考试时长(分钟)|是|
|4|exampaper\_myscore|Integer|试卷总分数|是|
|5|kemu\_types|Integer|科目|是|
|6|exampaper\_types|Integer|试卷状态|是|
|7|zujuan\_types|Integer|组卷方式|是|
|8|exampaper\_delete|Integer|逻辑删除（1代表未删除 2代表已删除）|是|
|9|create\_time|Date|创建时间|是|
表4.3试卷选题表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|exampaper\_id|Integer|试卷|是|
|3|examquestion\_id|Integer|试题|是|
|4|exampapertopic\_number|Integer|试题分数|是|
|5|create\_time|Date|创建时间|是|
表4.4试题表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|examquestion\_name|String|试题名称|是|
|3|kemu\_types|Integer|科目|是|
|4|examquestion\_options|String|选项，json字符串|是|
|5|examquestion\_answer|String|正确答案|是|
|6|examquestion\_analysis|String|答案解析|是|
|7|examquestion\_types|Integer|试题类型|是|
|8|examquestion\_sequence|Integer|试题排序，值越大排越前面|是|
|9|create\_time|Date|创建时间|是|
表4.5考试记录表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|examrecord\_uuid\_number|String|考试编号|是|
|3|yonghu\_id|Integer|考试用户|是|
|4|exampaper\_id|Integer|所属试卷id（外键）|是|
|5|total\_score|Integer|所得总分|是|
|6|insert\_time|Date|考试时间|是|
|7|create\_time|Date|创建时间|是|
表4.6答题详情表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|examredetails\_uuid\_number|String|试卷编号|是|
|3|yonghu\_id|Integer|用户id|是|
|4|examquestion\_id|Integer|试题id（外键）|是|
|5|examredetails\_myanswer|String|考生答案|是|
|6|examredetails\_myscore|Integer|试题得分|是|
|7|create\_time|Date|创建时间|是|
表4.7错题表表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户id|是|
|3|exampaper\_id|Integer|试卷（外键）|是|
|4|examquestion\_id|Integer|试题id（外键）|是|
|5|examredetails\_myanswer|String|考生作答|是|
|6|insert\_time|Date|记录时间|是|
|7|create\_time|Date|创建时间|是|
表4.8公告信息表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|gonggao\_name|String|公告名称|是|
|3|gonggao\_photo|String|公告图片|是|
|4|gonggao\_types|Integer|公告类型|是|
|5|insert\_time|Date|发布时间|是|
|6|gonggao\_content|String|公告详情|是|
|7|create\_time|Date|创建时间|是|
表4.9教练表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jiaolian\_name|String|教练姓名|是|
|3|jiaolian\_phone|String|教练手机号|是|
|4|jiaolian\_id\_number|String|教练身份证号|是|
|5|jiaolian\_photo|String|教练头像|是|
|6|jiaolian\_email|String|电子邮箱|是|
|7|create\_time|Date|创建时间|是|
表4.10教练预约表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|jiaolian\_yuyue\_uuid\_number|String|报名编号|是|
|3|jiaolian\_id|Integer|教练|是|
|4|yonghu\_id|Integer|用户|是|
|5|jiaolian\_yuyue\_text|String|报名理由|是|
|6|insert\_time|Date|教练预约时间|是|
|7|jiaolian\_yuyue\_yesno\_types|Integer|报名状态|是|
|8|jiaolian\_yuyue\_yesno\_text|String|审核回复|是|
|9|jiaolian\_yuyue\_shenhe\_time|Date|审核时间|是|
|10|jiaolian\_yuyue\_time|Date|预约时间|是|
|11|create\_time|Date|创建时间|是|
表4.11留言板表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_id|Integer|用户|是|
|3|liuyan\_name|String|留言标题|是|
|4|liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.12用户表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|yonghu\_name|String|用户姓名|是|
|3|yonghu\_phone|String|用户手机号|是|
|4|yonghu\_id\_number|String|用户身份证号|是|
|5|yonghu\_photo|String|用户头像|是|
|6|yonghu\_email|String|电子邮箱|是|
|7|create\_time|Date|创建时间|是|
表4.13学习资料表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|ziliao\_name|String|学习资料名称|是|
|3|ziliao\_uuid\_number|String|学习资料编号|是|
|4|ziliao\_photo|String|学习资料照片|是|
|5|zan\_number|Integer|赞|是|
|6|cai\_number|Integer|踩|是|
|7|ziliao\_types|Integer|学习资料类型|是|
|8|ziliao\_video|String|学习资料视频|是|
|9|ziliao\_file|String|学习资料下载|是|
|10|ziliao\_content|String|学习资料介绍|是|
|11|ziliao\_delete|Integer|逻辑删除|是|
|12|insert\_time|Date|录入时间|是|
|13|create\_time|Date|创建时间|是|
表4.14学习资料收藏表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|ziliao\_id|Integer|商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|ziliao\_collection\_types|Integer|类型|是|
|5|insert\_time|Date|收藏时间|是|
|6|create\_time|Date|创建时间|是|
表4.15学习资料留言表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|ziliao\_id|Integer|商品|是|
|3|yonghu\_id|Integer|用户|是|
|4|ziliao\_liuyan\_text|String|留言内容|是|
|5|insert\_time|Date|留言时间|是|
|6|reply\_text|String|回复内容|是|
|7|update\_time|Date|回复时间|是|
|8|create\_time|Date|创建时间|是|
表4.16管理员表

|序号|列名|数据类型|说明|允许空|
| :-: | :-: | :-: | :-: | :-: |
|1|Id|Int|id|否|
|2|username|String|儿童名|是|
|3|password|String|密码|是|
|4|role|String|角色|是|
|5|addtime|Date|新增时间|是|

第5章 系统实现

编程人员在搭建的开发环境中，会让各种编程技术一起呈现出最终效果。本节就展示关键部分的页面效果。
## 5.1 管理员功能实现
### 5.1.1 学习资料管理
图5.1 即为编码实现的学习资料管理界面，管理员在学习资料管理界面中可以对界面中显示，可以对学习资料信息的学习资料状态进行查看，可以添加新的学习资料信息等。

![](/md/blog.020.png)

图5.1 学习资料管理界面
### 5.1.2 考试管理
图5.2 即为编码实现的考试管理界面，管理员在考试管理界面中查看考试种类信息，考试描述信息，新增考试信息等。

![](/md/blog.021.png)

图5.2 考试管理界面
### 5.1.3 公告管理
图5.3 即为编码实现的公告管理界面，管理员在公告管理界面中新增公告，可以删除公告。

![](/md/blog.022.png)

图5.3 公告管理界面
### 5.1.4 公告类型管理
图5.4 即为编码实现的公告类型管理界面，管理员在公告类型管理界面查看公告的工作状态，可以对公告的数据进行导出，可以添加新公告的信息，可以编辑公告信息，删除公告信息。

![](/md/blog.022.png)

图5.4 公告类型管理界面
# 










