# 服务端测试

# 测试自动化

从传统角度讲，由个人设计的测试用例主要用于确定软件是否能够在不同情况下正确运行。在通常情况下，质量保证(简称 QA)工程师负责创建并运行此类测试用例。但到现在，由于测试驱动开发的兴盛，软件工程师正在逐渐接过传统 QA 团队的测试职责。换言之，开发人员开始在整个持续集成(简称 CI)流程中执行测试。很明显，测试会给开发人员带来新的负担，进而降低其生产效率水平。

我们相信企业需要一种能够自动设计、运行并报告结果的软件测试解决方案。通过对接持续集成系统，实时检查新代码以及添加与人类工程师类似的注释内容，这类解决方案需要有能力实现无摩擦介入。另外根据我们的观察，这类测试解决方案还应通过用户界面(简称 UI)进行测试，以确保工程师能够通过 UI 查找问题并减少漏报机率。

软件测试自动化的实现将有助于减少修复错误所需要的资源。一旦自动化软件识别出错误，其即可自动生成错误修复程序。简单的错误可以通过自动补丁修复，而复杂的错误则可利用人工设计的模板或者“基于异常的修复”解决——这些修复机制会对代码进行小幅更改，直到问题彻底消失。此外，推荐引擎能够利用先前工程师修复的数据进行训练，并在人工批准之前预先测试以提供明智的建议。
