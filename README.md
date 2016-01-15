# python
========
python资源集合 。 [python 中文学习大本营](http://www.pythondoc.com/) 。

###  目录
- [网页框架](#网页框架)
- [用户图形接口](#用户图形接口)
- [网络相关](#网络相关)
- [数据库相关](#数据库相关)
- [游戏相关](#游戏相关)
- [开源框架](#开源框架)
- [大数据相关](#大数据相关)
- [测试](#测试)
- [破解脚本](#破解脚本)
- [图表](#图表)
- [运维相关](#运维相关)
- [树莓派](#树莓派)
- [其他](#其他)

========
### 具体内容 =============================
========
#### 网页框架
 * [tornado](https://github.com/tornadoweb/tornado) - tornado是非阻塞式 Web 服务器框架，而且速度相当快。[官网](http://www.tornadoweb.org)，[Introduction to Tornado 中文翻译](http://demo.pythoner.com/itt2zh/index.html) , [中文教程](http://www.tornadoweb.cn/ )。
 * [Django](https://www.djangoproject.com/) - Django。 
 * [flask](http://flask.pocoo.org/) - flask， [官方教程中文翻译1](http://www.pythondoc.com/flask/index.html) ，[官方教程中文翻译2](http://docs.jinkan.org/docs/flask/),[Flask使用小结](http://python.jobbole.com/84003/),[Flask开发团队Pocoo的内部编码风格指南| 编程派 | Coding Python.html](http://www.codingpy.com/article/pocoo-internal-style-guide-cn/)。 
 * [Bottle](http://bottlepy.org/docs/dev/index.html) - Bottle是一个小型的轻量网络开发框架，同时速度也很快。
 * [Wooey](https://github.com/wooey/Wooey) - Wooey 是一个简单的Python脚本的Web UI 界面。它能够提供日常数据分析，文件处理等功能。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [Channels](https://github.com/andrewgodwin/channels) - Channels旨在增强Django的异步能力，同时让Django不仅仅局限于Request-Response模型，能够支持WebSocket、HTTP2推送和背景任务。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [Django-Baker](https://github.com/krisfields/django-baker) - Django Baker可以帮助开发者快速启动项目。只要提供app名称，Django Baker就可以根据models.py文件中的models，自动生成视图、表单、URL、admin页面以及模板。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [Django-Q](https://github.com/Koed00/django-q) - Django Q是一个原生Django分布式任务队列处理应用，通过Python的mutliprocessing模块功能实现。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [django-webpack-loader](https://github.com/owais/django-webpack-loader) - Django webpack loader对[webpack-bundle-tracker](https://github.com/owais/webpack-bundle-tracker)的输出结果进行处理，让你可以在自己的Django应用中使用生成的bundles。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。
 * [django-hackathon-starter](https://github.com/DrkSephy/django-hackathon-starter) - django-hackathon-starter这是一个Django Web应用模板程序，可以帮助你快速生成应用。必定能够为你节省大量的开发时间，同时这个库也能用作开发者的学习指南。[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。

========
#### 用户图形接口
 * [pyglet](https://bitbucket.org/pyglet/pyglet/wiki/Home) - Pyglet是一个纯Python语言编写的跨平台框架，用于开发多媒体和窗口特效应用。

========
#### 网络相关


========
#### 数据库相关
 * [Peewee](ttps://github.com/coleifer/peewee) - Peewee是一个小型但是十分强大的库，支持通过ORM的方式访问数据库，原生支持SQLite、MySQL和PostgreSQL等数据库。

========
#### 游戏相关


========
#### 开源框架
 * [高效的Python数据分析框架Ibis](https://github.com/cloudera/ibis) - 高效的Python数据分析框架Ibis  [ibis-project](http://www.ibis-project.org/) , [通过IPN了解Ibis](http://nbviewer.ipython.org/github/cloudera/ibis-notebooks/tree/master/basic-tutorial/).
 * [RabbitMQ](http://www.rabbitmq.com/download.html) - 一个工业级的消息队列服务器，[RabbitMQ+Python入门经典-兔子和兔子窝](http://blog.csdn.net/linvo/article/details/5750987)

========
#### 大数据相关
 * [pandas](https://github.com/pydata/pandas) - 为 Python 编程语言提供高性能，易用数据结构和数据分析工具。在数据改动和数据预处理方面，Python 早已名声显赫，但是在数据分析与建模方面，Python 是个短板。Pands 软件就填补了这个空白，能让你用 Python 方便地进行你所有数据的处理，而不用转而选择更主流的专业语言，例如 R 语言。
 * [pulp](https://github.com/pulp/pulp) - PuLP 是一个用 Python 编写的线性编程模型。它能产生线性文件，能调用高度优化的求解器，GLPK，COIN CLP/CBC，CPLEX，和GUROBI，来求解这些线性问题。
 * [Matplotlib](https://github.com/matplotlib/matplotlib) - Matplotlib是基于 Python 的 2D（数据）绘图库，它产生（输出）出版级质量的图表，用于各种打印纸质的原件格式和跨平台的交互式环境。matplotlib 既可以用在 python 脚本, python 和 ipython 的 shell 界面 (ala MATLAB® 或 Mathematica®)，web 应用服务器，和6类 GUI 工具箱。matplotlib 尝试使容易事情变得更容易，使困难事情变为可能。你只需要少量几行代码，就可以生成图表，直方图，能量光谱（power spectra），柱状图，errorcharts，散点图（scatterplots）等。
 * [Scikit-Learn](https://github.com/scikit-learn/scikit-learn) - Scikit-Learn是一个简单有效地数据挖掘和数据分析工具（库）。关于最值得一提的是，它人人可用，重复用于多种语境。它基于 NumPy，SciPy 和 mathplotlib 等构建。
 * [Spark](https://github.com/apache/spark) -Spark 由一个驱动程序构成，它运行用户的 main 函数并在聚类上执行多个并行操作。Spark 最吸引人的地方在于它提供的弹性分布数据集（RDD），那是一个按照聚类的节点进行分区的元素的集合，它可以在并行计算中使用。RDDs 可以从一个 Hadoop 文件系统中的文件（或者其他的 Hadoop支持的文件系统的文件）来创建，或者是驱动程序中其他的已经存在的标量数据集合，把它进行变换。用户也许想要 Spark 在内存中永久保存 RDD，来通过并行操作有效地对 RDD 进行复用。最终，RDDs 无法从节点中自动复原。Spark 中第二个吸引人的地方在并行操作中变量的共享。

========
#### 测试
 * [splinter](http://splinter.cobrateam.info/) - Python自动化测试工具Splinter，不仅可以当web自动化测试工具 同时也可以当抓取交互式网站的爬虫程序来用的，不用去分析ajax请求数据了，可以模拟登录，[用Python开发自动化测试脚本-splinter](http://python.jobbole.com/84012/)。
 * [swarm](https://github.com/duhoobo/swarm) - 是一个简单的使用 gevent 开发的支持自定义协议的长连接压测框架。

========
#### 破解脚本
 * [ibrute](https://github.com/hackappcom/ibrute) - 一个攻击iCloud账户的Python脚本,2014年很多明星的账号就是被这个脚本攻破的，苹果已经修改这个漏洞了。
 * [bruteforce_py](https://github.com/rischanlab/bruteforce_py) - 暴力破解脚本，ssh bf, wordpress bf, cpanel bf, mysql bf, etc ... 可以说是暴力破解大全。
 * [keychain-bruteforce](https://github.com/ziman/keychain-bruteforce) - 暴力破解MAC OS X 的密码管理。
 * [gamblerbfe](https://github.com/mthbernardes/gamblerbfe) - 路由器也可以暴力破解了。
 * [AndroidPINCrack](https://github.com/PentesterES/AndroidPINCrack) - android的pin密码破解。
 * [rarPasswordCrackere](https://github.com/GauthamGoli/rarPasswordCrackere) - rar加密文件破解。
 * [Python-ZIP-Cracker](https://github.com/agusmakmun/Python-ZIP-Cracker) - zip加密文件破解。


========
#### 图表
 * [vincent](https://github.com/wrobstory/vincent) - Python 构建的专为运用 D3.js 进行可视化的 vega 转换工具。


========
#### 运维相关
 * [pywebsocketserver](https://github.com/suxianbaozi/pywebsocketserver) - 程序Log实时监控 – python + websocket。
 * [pupy](https://github.com/n1nj4sec/pupy) - Pupy是一个远程管理工具（Administration Tool），开源并且支持多个平台。Pupy还内置了一个Python解释器，可以从内存中加载Python包，访问远程Python对象。
 * [Invoke](http://www.pyinvoke.org) - Invoke让你通过一个Python库便捷地执行系统管理任务。如果你想使用稳定的工具（即使是不再积极开发），可以考虑Invoke的前身——Fabric。
 * [DeployDjango](https://github.com/yask123/DeployDjango) - 不到一分钟安全部署Django应用的脚本，[操作教程](http://codingpy.com/article/deploy-django-app-in-less-than-one-minute/)。
 * [HealthChecks](https://github.com/healthchecks/healthchecks) - HealthChecks基于 cron 的监控服务。在 cron 里配置好监控只需要几分钟时间，却能让你晚上睡得更好！[2015年出现的十大流行Python库](http://codingpy.com/article/top-10-django-libraries-started-in-2015/) 。

========
#### 树莓派
 * [图片自动发邮箱](https://github.com/dungeonsnd/toolkit/blob/master/rpi/rpi_auto_send_motion_files.py) - 报警图片自动发邮箱功能。
 * [自动更新树莓派的内网、外网IP地址到 自己的github上](https://github.com/dungeonsnd/toolkit/blob/master/rpi/rpi_auto_send_ip_to_github.py) - 自动更新树莓派的内网、外网IP地址到 自己的github。
 * [rpi-start](http://conanwhf.gitcafe.io/2016/01/12/rpi-start/) - 树莓派初始配置指南（2代B型）。

========
#### 其他
 * [IoTNotes](http://ideatouch.github.io/IoTNotes/) - 开源硬件记录。
 * [GitHub上Star最多的100个python repository](http://www.jianshu.com/p/110f2a221096) - GitHub上Star最多的100个python repository。
 * [10个Python 模块](http://www.imooc.com/article/1138) - 你该了解的10个 Python 模块。
 * [dask](https://github.com/ContinuumIO/dask) - 【(Python)集成任务调度/阻塞算法的数据并行处理库Dask】支持大数据集的分割多核并行处理，[Doc](http://dask.pydata.org/en/latest/)。 
 * [Phonenumbers](https://pypi.python.org/pypi/phonenumberslite/7.0.2) - Phonenumbers 小巧，实用简便，没有地理代编码，运营商，时区等metadata数据。它能识别多种格式，然后使用不同的格式/样式进行有效匹配。
 * [toyplot](https://github.com/sandialabs/toyplot) - Python交互绘图库Toyplot，[文档doc](http://toyplot.readthedocs.org/en/latest/)。
 * [pythalesians](https://github.com/thalesians/pythalesians/) - Python金融(分析工具)库PyThalesians。
 * [20个机器学习开源项目](http://mp.weixin.qq.com/s?__biz=MzAwNTA4OTc3OQ==&mid=207199077&idx=1&sn=039cda9e698a85bc32d336c6f84dd059) - 20 个顶尖的 Python 机器学习开源项目 Scikit-learn、Pylearn2、NuPIC…… 
 * [Seaborn](http://web.stanford.edu/~mwaskom/software/seaborn/) - 用 Seaborn 画出好看的分布图, [使用说明](http://staticor.io/post/2015-06-10seaborn-distribution-plot)  。
 * [Python_Coding_Rule](http://ssv.sebug.net/Python_Coding_Rule) - 【Python代码指南】，这篇文档改编自Guido最初的《Python风格指南》一文，希望对初学Python的朋友们有所借鉴。
 * [GGTinypng](https://github.com/ylovern/GGTinypng) - 批量压缩png和jpg图片python脚本，已经支持子文件夹里面的图片，会按原始的相对路径存放到输出文件夹内。
 * [sinaweibopy](https://github.com/michaelliao/sinaweibopy) - 新浪微博Python SDK。
 * [keras](https://github.com/fchollet/keras) - Keras是一个高度模块化的神经网络库，用Python语言编写，可以基于TensorFlow或Theano框架运行。
 * [yapf](https://github.com/google/yapf) - yapf是一个Python文件代码格式化工具，但与其他类似工具采取了不同的算法。它脱胎于由 Daniel Jasper 开发的 clang-format。
 * [tqdm](https://github.com/tqdm/tqdm) - tqdm可以在长循环中添加一个进度提示信息，用户只需要封装任意的迭代器 tqdm(iterator)，是一个快速、扩展性强的进度条工具库。
 * [pyvim](https://github.com/jonathanslenders/pyvim) - pyvim用Python语言实现的Vim编辑器。
 * [snake](https://github.com/amoffat/snake) - Snake用来取代Vim的VimScript进行Vim的插件编程，借由Python的强大，让插件编程如虎添翼。
 * [pyxley](https://github.com/stitchfix/pyxley) - 使用Flask和React.js，快速开发数据面板（dashboard。在网页上显示一个数据面板是与人分享数据科学发现的最直观方法。对R语言来说有Shiny来简化数据科学家开发网页的工作，而Pyxley就相当于Python版的Shiny。使用Pyxley不光不用写HTML、CSS，你还可以加入自己的JavaScript来进行定制。
 * [Tomorrow](https://github.com/madisonmay/Tomorrow) - Tomorrow为Python 2.7中的异步代码提供了神奇的装饰器语法实现。
 * [ibis](https://github.com/cloudera/ibis) - Ibis是Cloudera Labs推出的一个新项目，目前还是预览版。它试图解决的就是数据集规模的问题，但对用户提供的确是单机上Python的体验，而且能够与现有的Python数据生态圈（Pandas、Scikit-learn、Numpy）进行集成。未来它还计划加入与机器学习和高级分析集成的功能。
 * [ipython](https://github.com/ipython/ipython) - IPython 是一个在多种编程语言之间进行交互计算的命令行 shell，最开始是用 python 开发的，提供增强的内省，富媒体，扩展的 shell 语法，tab 补全，丰富的历史等功能
 * [Arrow](https://github.com/crsmithdev/arrow) - Arrow这个库可以更好地处理Python中的日期和时间（data/time）。

 * [awesome-python](https://github.com/vinta/awesome-python) - Awesome可能是GitHub上寻找和整理开源项目最好的方式。 

