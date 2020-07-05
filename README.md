# Go 语言编程之旅：一起用 Go 做项目

## 本书定位

本书不直接介绍 Go 语言的语法基础，内容将面向项目实践，同时会针对核心细节进行分析。而在实际项目迭代中，常常会出现或多或少的事故，因此本书也针对 Go 语言的大杀器（分析工具）以及常见问题进行了全面讲解。

本书适合已经大致学习了 Go 语言的基础语法后，想要跨越到下一个阶段的开发人员，可以填补该阶段的空白和进一步拓展你的思维方向。

## 读者定位

- 基本了解 Go 语言的语法和使用方式的开发人员。
- 想要进行 Go 相关项目实践和进一步摸索的开发人员。
- 希望熟悉 Go 常用分析工具的开发人员。

## 本书内容

本书针对常见的项目类型，主要细分为 5 + 1 板块，分别是命令行、HTTP、RPC、Websocket 应用、进程内缓存以及 Go 中的大杀器。

同时我们在项目开发、细节分析、运行时分析等方方面面都进行了较深入的介绍和说明，能够为 Go 语言开发者提供相对完整的项目实践经验，而如果深入阅读第六章的章节，更能够为未来各类问题出现时的问题排查提供一份强大的知识板块。

如下为本书的思维导图概览：

![image](https://image.eddycjy.com/e5eafb17140fdc06830b838eb7fb0468.png)

## 关于本书的想法

实际上写面向实践类的图书是一个比较大的考验，因为不管是章节篇幅、叙事顺序和结构以及代码的结构性，只要其中一点做的不好，就会影响读者阅读此书时的知识领域、感官，因此为了更贴合现实中的实践，针对本书我们划分为了如下三个方向：

![image](https://image.eddycjy.com/65e1e9cbfd14617fd054970e3d474e64.png)

笔者认为 “实践”，大体就是三个方向，分别是 “做、学、排”，做好你需要的项目，学习优秀的开源/私有项目，并据此不断精进你所负责的项目。而既然是企业项目，那么在长期的迭代中一定会遇到或大或小的事故，因此知道如何排查和分析问题就显得非常重要。

同时这里还有一个隐藏的方向，那就是归纳总结，你做好项目、学习了优秀项目，排查和分析问题后，都应当进行对所学知识的审读，将你的思维聚拢并归纳记录下来，这也是为什么我们会在章节中会有 “小结” 的原因。

## 为什么要写这本书

在数年前，我司开始尝试进行技术栈的转型，当时我运气很好，恰好被抽调到了新业务的突破组，因此需要负责相关技术推进，但是当时网上并没有成体系成结构化的教材，因此我写了一些中文连载系列，希望借此将知识分享给广大的 Go 语言爱好者。

而回到 2020 年，我观察到这几年 Go 语言的火热程度不断上升，Go 语言相关的图书也越来越多，几乎方方面面的领域都已经涉及到了，但依然没有出现相对完整的项目实践类别的图书，因此我决定再次行动起来，希望将这一块的知识更体系更呈结构化的分享给大家。

## 社区支持

如果有任何疑问，欢迎通过各种方式联系到本书作者，我一定会回复你，并且我们还建立了官方网站 go-programming.cn 和相应的知识星球，我们会对本书进行长期维护，也希望这一个平台，能够给你带来更大的思维拓展和认识到更多的志同道合的朋友。

另外，我们只是喜欢分享的普通 Go 语言爱好者，技术水平有限，如果你发现任何疑似问题或错误，不要迟疑，马上联系我们，我们会进行处理。

## 版权声明


## 致谢

感谢徐新华（polaris1119）和在 Go 语言社区中的爱好者们，如果没有你们的鼓励，这本书不可能出版。最后感谢为本书牺牲了大量业余时间进行 Review 的朋友们：

- [盛傲飞（aofei）](https://github.com/aofei)
- [石太彬（shitaibin）](https://github.com/shitaibin)
- [曾晓东（teroy）](https://github.com/teroy)