
# 相关术语
在该项目里，我首先收集了一些相关资料，供大家参考。
术语|说明
--|--
API|应用程序接口（API：Application Program Interface），应用程序接口是一组定义、程序及协议的集合，通过 API 接口实现计算机软件之间的相互通信。
IDP|内部开发者平台。将所有的技术和工具绑定在一起，设计和构建工具链和工作流程，涵盖应用程序整个生命周期的操作需要，让软件工程团队具备自助服务能力。
GitOps|用于持续部署应用程序的软件开发框架。并确保这些更新与使用 git 存储库的软件基础架构保持同步,使用 Git 存储库实时同步应用程序中的更改。
CI|持续集成(Continuous Integration): 持续频繁的（每天多次）将本地代码“集成”到主干分支，并保证主干分支可用.
CD|持续交付（Continuous Delivery）: 是持续集成的下一步，持续频繁地将软件的新版本交付到类生产环境（类似于预发），交付给测试、产品验收。
CD|持续部署（Continuous Deployment）: 是持续交付的下一步，“自动”将代码部署到生产环境。
Kubernetes（K8S）|部署和管理基础设施的事实标准，是构建平台的工具，容器集群管理系统。目标是让部署容器化的应用简单并且高效，提供了应用部署，规划，更新，维护的一种机制。
# 报告与白皮书

标题|简介|作者/来源
--|--|--
[Team Topologies: Organizing Business and Technology Teams for Fast Flow](https://teamtopologies.com/book)|在云原生时代，如何定位自身与团队？提及了平台团队拓扑。|Matthew Skelton， Manuel Pais
[The Rise of the Internal Developer Platform](https://info.container-solutions.com/the-rise-of-the-internal-developer-platform)|对IDP的概念进行了解释，为建立IDP提供了一些案例和建议。|Container-Solutions
[Building Software Platforms](https://leanpub.com/software-platforms)|策划了一系列AWS创新，描述了如何使用AWS云服务设计和实现许多建议。|Pablo Bermejo
[The Platform Engineering Guide: Principles and Best Practices](https://www.infoq.com/minibooks/platform-engineering-guide/)|从许多不同的软件领导者那里提取并收集了专业知识，以帮助读者构建、操作和进化他们自己的平台和平台团队。|InfoQ
[Understanding Platform Engineering](https://solutions.insight.com/Resources/eBooks/ebooks/Understanding-Platform-Engineering)|提出平台工程的概念及如何构建一个成功的平台工程队伍。|Insight eBook
[Announcing A White Paper On Platforms For Cloud Native Computing](https://aster.cloud/2023/04/20/announcing-a-white-paper-on-platforms-for-cloud-native-computing/)|通过描述内部平台提供的价值、它们解决的问题、跟踪它们成功的方法以及它们所需要的属性和能力，来教育和建议组织领导者和潜在的平台建设者。|CNCF
[The Definitive Guide to Internal Developer Portals](https://www.getport.io/blog/guide-to-internal-developer-portals)|本文介绍了构建内部开发人员门户的原因和方法，以及它们如何影响开发人员的经验和工作效率。|eBook

# 国内国外团队
- [mia Platform](https://blog.mia-platform.eu/en)
- [Humanitec](https://humanitec.com/blog)
- [CloudKnit](https://www.cloudknit.io/blog)
- [蚂蚁集团 KusionStack](https://gitee.com/kusionstack)
- [Devtron](https://devtron.ai/blog/)
- [阿里云云开发平台](https://workbench.aliyun.com/)
# 相关文章
## 相关中文文章
- [谷歌、Netflix和亚马逊都说好的IDP是怎样炼成的？](https://new.qq.com/rain/a/20210508A017YT00)
- [如何设计一个内部开发者平台](https://blog.csdn.net/community_717/article/details/128281237)
- [论平台工程的价值](https://www.infoq.cn/article/IKV0beLrg2fsFlm61wmg)
- [建立云原生组织的8个要素](https://www.modb.pro/db/394258)
- [“扯淡的DevOps，我们开发者根本不想做运维！”](https://www.163.com/dy/article/HFKER3AL0511D3QS.html)
- [DevOps已死，平台工程才是未来](https://www.infoq.cn/article/7porVp7qVF03BVc2tDd6)
- [聊聊平台工程](https://mp.weixin.qq.com/s/7imERbIC2PFBuksVW-CZ7g)
- [IDP 与 DevOps平台：相似之处与关键差异](https://www.bilibili.com/read/cv23728574?from=search&spm_id_from=333.337.0.0)
- [企业如何构建内部开发者平台？](https://www.bilibili.com/read/cv22390943?from=search&spm_id_from=333.337.0.0)
- [平台工程 | 内部开发者门户权威指南](https://www.bilibili.com/read/cv23345374?from=search&spm_id_from=333.337.0.0)
- [蚂蚁规模化平台工程实践两年多，我们学到了什么](https://www.sohu.com/a/594309889_355140)
- [软件工程的第一性原理](https://www.smartide.cn/zh/blog/2022-1022-software-engineering/)
- [平台工程：微服务DevOps 进化还是花哨的重命名？](https://mp.weixin.qq.com/s/DOHfKJaKC3pC9bQDTKDHUw)
- [研发效能｜DevOps 已死平台工程永存带来的焦虑](https://baijiahao.baidu.com/s?id=1748301770586019606&wfr=spider&for=pc)
- [关于平台工程的开发者工具链，你还想加点啥？](https://mp.weixin.qq.com/s/dba1GNZmM7FjfmaOgemlMg)
- [平台工程中认知负荷的挑战](https://www.sohu.com/a/624647320_355140)
- [平台工程解Kubernetes之痛](https://mp.weixin.qq.com/s/W1hYKA8ZqkK0YWNd3a7w3g)
- [DevOps 缺少定义,平台工程需要指导性路线图](https://new.qq.com/rain/a/20230118A03HMM00)
- [超越DevOps的平台工程：云计算背景下的平台战略和实施](https://insights.thoughtworks.cn/beyond-devops/)
- [平台工程的 2023：助力云原生重构研发组织文化与组织架构](https://zhuanlan.zhihu.com/p/617542339)
- [Netflix 是如何利用联合平台控制台统一工程体验的](https://it.sohu.com/a/656813382_355140)
- [云原生趋势下的平台工程](https://www.infoq.cn/theme/183)
## 相关外文文章
- [What is "Platform Engineering"?](https://diff.wikimedia.org/2011/08/17/what-is-platform-engineering/)
- [Platform engineering product teams](https://www.thoughtworks.com/radar/techniques/platform-engineering-product-teams)
- [How to build a platform team now! the secrets to successful engineering](https://hackernoon.com/how-to-build-a-platform-team-now-the-secrets-to-successful-engineering-8a9b6a4d2c8)
- [The Platform Engineer of the Future](https://cloudytechnologist.com/2019/04/05/the-platform-engineer-of-the-future/)
- [Platform Engineering](https://wichon.com/platform-engineering)
- [On the Value of Platform Engineering](https://ulrichkautz.com/posts/2021-03-11_value-of-platforming-engineering/)
- [How to build an internal developer platform, from those who have done it](https://www.infoworld.com/article/3611369/how-to-build-an-internal-developer-platform-from-those-who-have-done-it.html)
- [Platform Engineering as a (Community) Service](https://www.infoq.com/articles/platform-engineering-as-community-service/)
- [What Is Platform Engineering? The Concept Behind the Term](https://www.liatrio.com/blog/what-is-platform-engineering-the-concept-behind-the-term)
- [Engineering Your Organization: Services, Platforms, and Communities](https://www.infoq.com/presentations/engineering-organization-services-platforms-communities/)
- [7 core components of an Internal Developer Platform](https://blog.mia-platform.eu/en/seven-core-components-internal-developer-platform)
- [Platform Engineering: The Definitive Guide](https://loft.sh/blog/platform-engineering-the-definitive-guide/)
- [Announcing a white paper on Platforms for Cloud Native Computing](https://www.cncf.io/blog/2023/04/11/announcing-a-white-paper-on-platforms-for-cloud-native-computing/)
- [Internal Developer Portals Can Do More than You Think](https://thenewstack.io/internal-developer-portals-can-do-more-than-you-think/)
- [What Is Platform Engineering? Role, Principles & Benefits](https://spacelift.io/blog/what-is-platform-engineering)





