# 个人技术主页 - 内容清单

> 请审核并补充/修正以下内容，确认后我将基于此构建网站。
> 标记 `[待补充]` 的地方需要你提供信息。

---

## 1. 个人介绍

| 字段 | 内容 |
|------|------|
| 姓名 | YuanBo Li (李元博) |
| 职位 | GenAI Specialist Solution Architect @ AWS |
| 团队 | AWS GCR SSO (Greater China Region, Specialist Solution Organization) |
| 一句话介绍 | 专注于大语言模型推理优化、AI应用平台和检索增强生成，服务头部互联网客户 |
| Email | ybalbert@amazon.com |
| 微信公众号 | [AI猿智慧](https://mp.weixin.qq.com/s/4KoSQbxQyIjiE4hBkqTh1g)，关注数 1209，文章数 49 |
| B站 | [前滩猿神](https://space.bilibili.com/259231104)，粉丝 210，播放量 3028，视频 13 |

---

## 2. 技术研究方向（逆序）

---

### 2.1 LLM Inference（2025 ~ 至今）

**简介**: 研究 AWS 上部署运行 DeepSeek 等开源大模型的最佳实践，SGLang 等推理引擎在 AWS GPU 实例上的性能评测，多机型性价比评测（B200等新一代 GPU）。

#### 技术输出

| 类型 | 内容 | 备注 |
|------|------|------|
| 自媒体(B站) | [大模型推理-深入浅出系列](https://space.bilibili.com/259231104/lists/8200803) | 播放量[3028] |

---

### 2.2 GenAI 平台 - Dify on AWS（2024 ~ 2025）

**简介**: Dify Top contributor，打造 Dify 中的 AWS 生态，使 Bedrock 成为 Dify 支持最好的模型供应商，支持 SageMaker 私有化部署的 5 类 GenAI 模型接入 Dify。

#### 技术输出

| 类型 | 内容 | 备注 |
|------|------|------|
| GitHub | [aws-samples/dify-aws-tool](https://github.com/aws-samples/dify-aws-tool) | ⭐178 Fork:40, Dify 的 AWS 插件集 |
| GitHub | [langgenius/dify](https://github.com/langgenius/dify) | Top Contributor，贡献 SageMaker Provider、Bedrock 跨区域推理、Prompt Cache等 |
| 中文博客 | 集成 Dify 和 AWS Service 实现更具灵活性的翻译工作流 | https://aws.amazon.com/cn/blogs/china/integrate-dify-and-aws-services-to-enable-more-flexible-translation-workflows/ |
---

### 2.3 LLM Translation（2024 ~ 2025）

**简介**: 大模型翻译场景最佳实践：专词映射、RAG优化、Finetune、工作流构建。发布翻译技术白皮书，在上海 Summit 对外发布。

#### 技术输出

| 类型 | 内容 | 备注 |
|------|------|------|
| GitHub | [aws-samples/rag-based-translation-with-dynamodb-and-bedrock](https://github.com/aws-samples/rag-based-translation-with-dynamodb-and-bedrock)  | 基于 AWS 服务实现具备专词映射能力的大语言模型翻译 |
| AWS白皮书 | [亚马逊云科技生成式AI时代的大模型翻译创新与实践](./亚马逊云科技生成式AI时代的智能翻译创新与实践-白皮书.pdf) | 2025 上海 Summit 发布 |
|公开演说| 基于LLaMA Factory开源框架，无代码实现大模型的微调训练 | https://emxpb.xetlk.com/sl/1zRMz6 |
| 中文博客 | 基于 AWS 服务实现具备专词映射能力的大语言模型翻译 | https://aws.amazon.com/cn/blogs/china/implementing-llm-translation-with-word-mapping-capabilities-based-on-aws-services/ |
| 中文博客 | LLM 微调实践 – 利用大语言模型微调进行翻译质量检测（上） | https://aws.amazon.com/cn/blogs/china/translation-quality-detection-using-llm-fine-tuning-part-one/ |
| 中文博客 | LLM 微调实践 – 利用大语言模型微调进行翻译质量检测（下） | https://aws.amazon.com/cn/blogs/china/translation-quality-detection-using-llm-fine-tuning-part-two/ |
| 中文博客 | 基于 Amazon SageMaker 和 LLaMA-Factory 打造一站式无代码模型微调部署平台 Model Hub | https://aws.amazon.com/cn/blogs/china/building-llm-model-hub-based-on-llamafactory-and-easyr1/ |

---

### 2.4 RAG 检索增强生成（2023 ~ 2024）

**简介**: GCR RAG知识问答解决方案的主要维护者。

#### 技术输出

| 类型 | 内容 | 备注 |
|------|------|------|
| GitHub | [aws-samples/private-llm-qa-bot](https://github.com/aws-samples/private-llm-qa-bot)  | 基于AWS服务和LangChain的生产级知识问答Chatbot,  ⭐285 Fork:69|
|公开演讲|基于 RAG 构建生成式 AI 应用最佳实践与“避坑指南” | https://www.infoq.cn/video/mggw3JCRiXY1TKIN8GPy?utm_source=album_info&utm_medium=video |
| 中文博客 | 基于大语言模型知识问答应用落地实践 – 知识库构建（上） | https://aws.amazon.com/cn/blogs/china/practice-of-knowledge-question-answering-application-based-on-llm-knowledge-base-construction-part-1 |
| 中文博客 | 基于大语言模型知识问答应用落地实践 – 知识库构建（下） | https://aws.amazon.com/cn/blogs/china/practice-of-knowledge-question-answering-application-based-on-llm-knowledge-base-construction-part-2 |
| 中文博客 | 基于大语言模型知识问答应用落地实践 – 知识召回调优（上） | https://aws.amazon.com/cn/blogs/china/practice-of-knowledge-question-answering-application-based-on-llm-knowledge-base-construction-part-3/ |
| 中文博客 | 基于大语言模型知识问答应用落地实践 – 知识召回调优（下） | https://aws.amazon.com/cn/blogs/china/practice-of-knowledge-question-answering-application-based-on-llm-knowledge-base-construction-part-4 |
| 中文博客 | 基于大语言模型知识问答应用落地实践 – 使用 TruLens 做自动化 RAG 项目评估测试 | https://aws.amazon.com/cn/blogs/china/automated-rag-project-assessment-testing-using-trulens/ | 
| Global 博客 | Integrate sparse and dense vectors to enhance knowledge retrieval in RAG using Amazon OpenSearch Service | https://aws.amazon.com/blogs/big-data/integrate-sparse-and-dense-vectors-to-enhance-knowledge-retrieval-in-rag-using-amazon-opensearch-service |

---

## 3. 书籍翻译

| 字段 | 内容 |
|------|------|
| 书名（中文） | 生成式AI入门与AWS实战 |
| 书名（英文） | Generative AI on AWS: Building Context-Aware Multimodal Reasoning Applications |
| 豆瓣评分 | 8.8 |
| 豆瓣链接 | https://m.douban.com/book/subject/36906611 |
| 角色 | 译者之一 |
| 荣誉 | 2024 年度影响力译者奖、2024 年度影响力新书奖 |

