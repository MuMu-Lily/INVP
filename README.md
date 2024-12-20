# INVP
 一个全面的框架，用于评估LLMs在社会环境中的决策过程中的价值优先级。它包括基于Schwartz价值观理论的独立和非独立决策情境。


# 价值观优先级评估数据集与代码库

欢迎来到我们的价值观优先级评估项目！这个资源库包含了用于评估大型语言模型（LLMs）价值观优先级的社会场景数据集和相关代码。这些资源是为了促进对AI基于价值观进行决策的理解。

## 数据集

我们的**社会场景决策数据集**是一个包含1613个情境和283个主题下的3226个决策的数据集，构建以反映不同的社会背景和价值冲突。

### 数据集结构

数据集以csv格式存储，每个条目包含：

- **theme**： 数据集涵盖了十个日常生活领域：家庭、婚姻、育儿、工作场所、友谊、娱乐、教育、精神性、公民身份和身体健康。

- **topic**： 在每个领域内，涉及多个主题，反映了需要解决的具体问题，并展示不同的价值优先级。

- **scenario&decision**情境和决策： 每个情境都旨在突出决策冲突，提供两种可能的决策，反映了不同的价值优先级。

- **value pair**： 基于Schwartz的价值观理论，每个场景包括一对价值观。

## 提示&代码

我们提供了用于独立决策选择和非独立决策选择的相关提示和代码实力，具体内容可在prompt_code_for_eval中找到。


## 引用
如果您在研究中使用了这个数据集或代码，请引用我们的论文：
What's the most important value? INVP: INvestigating the Value Priorities of LLMs through Decision-making in Social Scenarios



# INVP 
A comprehensive framework for assessing the value priorities of Large Language Models (LLMs) in social context decision-making processes. It includes independent and non-independent decision-making scenarios based on Schwartz's value theory.

# Value Priority Assessment Dataset and Code Repository

Welcome to our Value Priority Assessment project! This repository contains a dataset of social scenarios and related code for assessing the value priorities of Large Language Models (LLMs). These resources are designed to promote understanding of AI decision-making based on values.

## Dataset

Our **Social Scenario Decision Dataset** is a dataset that includes 1613 scenarios and 3226 decisions across 283 topics, constructed to reflect different social contexts and value conflicts.

### Dataset Structure

The dataset is stored in csv format, with each entry containing:

- **theme**: The dataset covers ten daily life domains: Family, Marriage, Parenting, Workplace, Friendship, Recreation, Education, Spirituality, Citizenship, and Physical Well-being.

- **topic**: Within each domain, there are multiple topics that reflect specific issues requiring resolution and demonstrate different value priorities.

- **scenario & decision**: Each scenario is designed to highlight decision-making conflicts, offering two possible decisions that reflect different value priorities.

- **value pair**: Based on Schwartz's value theory, each scenario includes a pair of values.

## Prompts & Code

We provide prompts and code for independent decision-making and non-independent decision-making, which can be found in the prompt_code_for_eval.

## Citation

If you use this dataset or code in your research, please cite our paper:
What's the most important value? INVP: INvestigating the Value Priorities of LLMs through Decision-making in Social Scenarios.

