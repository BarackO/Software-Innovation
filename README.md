# Project Goal
Write a simplest application to go through the DevOps flow.<br>

# What is DevOps
DevOps is a term used to refer to a set of practices that emphasize the collaboration and communication of both software developers and information technology (IT) professionals while automating the process of software delivery and infrastructure changes. <br>
It aims at establishing a culture and environment where building, testing, and releasing software can happen rapidly, frequently, and more reliably.<br>
## Practice
Version control<br>
Continuous integration<br>
Trunk-based development<br>
Automation<br>

## Continuous delivery
Test automation<br>
Deployment automation<br>
Continuous integration<br>
Trunk-based development<br>
Comprehensive version control<br>

## Test automation
Unit Test<br>
UI Test<br>
Integration Test <br>
Validation Test <br>
System Test <br>

# Devops Toolchain
Code - Code development and review, version control tools, code merging;<br>
Build - Continuous integration tools, build status;<br>
Test - Test and results determine performance;<br>
Package - Artifact repository, application pre-deployment staging;<br>
Release - Change management, release approvals, release automation;<br>
Configure - Infrastructure configuration and management, Infrastructure as Code tools;<br>
Monitor - Application performance monitoring, end-use experience.<br>

# Minimum DevOps Platform
## Code
代码开发、评审、版本控制以及合并。<br>
## CI
持续集成（CONTINUOUS INTEGRATION）
在持续集成环境中，开发人员将会频繁的提交代码到主干。这些新提交在最终合并到主线之前，都需要通过编译和自动化测试流进行验证。这样做是基于之前持续集成过程中很重视自动化测试验证结果，以保障所有的提交在合并主线之后的质量问题，对可能出现的一些问题进行预警。<br>
## CD
持续交付（CONTINUOUS DELIVERY）
持续交付就是讲我们的应用发布出去的过程。这个过程可以确保我们尽可能快的实现交付。这就意味着除了自动化测试，我们还需要有自动化的发布流，以及通过一个按键就可以随时随地实现应用的部署上线。通过持续交付，您可以决定每天，每周，每两周发布一次，这完全可以根据自己的业务进行设置。但是，如果您真的希望体验持续交付的优势，就需要先进行小批量发布，尽快部署到生产线，以便在出现问题时方便进行故障排除。<br>

持续部署（CONTINUOUS DEPLOYMENT）
如果我们想更加深入一步的话，就是持续部署了。通过这个方式，任何修改通过了所有已有的工作流就会直接和客户见面。没有人为干预（没有一键部署按钮），只有当一个修改在工作流中构建失败才能阻止它部署到产品线。
持续部署是一个很优秀的方式，可以加速与客户的反馈循环，但是会给团队带来压力，因为不再有“发布日”了。开发人员可以专注于构建软件，他们看到他们的修改在他们完成工作后几分钟就上线了。基本上，当开发人员在主分支中合并一个提交时，这个分支将被构建、测试，如果一切顺利，则部署到生产环境中。<br>
## Infrastructure
基础设施。<br>
## Monitor
监控应用性能，终端用户体验。<br>

