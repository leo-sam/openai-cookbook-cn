# OpenAI Cookbook

OpenAI Cookbook分享了一些使用 [OpenAI API] 的示例代码.

要运行这些示例，您需要一个OpenAI帐户和API密钥 ([创建一个免费账号][api signup]).
(国内无法正常注册)

大多数代码示例都是用Python编写的，当然，你用任何语言实现都可以。

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=468576060&machine=basicLinux32gb&location=EastUs)

## 最近更新 🆕 ✨

- [如何使用Embeddings来实现问答系统（如何根据用户提出的问题，从给定的文本语料库中找到相应的答案）](examples/Question_answering_using_embeddings.ipynb) [Apr 14th, 2023]
- [如何使用向量数据库进行嵌入搜索（如何使用向量数据库来存储和搜索嵌入向量，以实现更加高效和快速的相似度搜索）](examples/vector_databases/) [various dates]
- [如何使用ChatGPT和自己的数据来提升产品（如何使用ChatGPT模型和自己的数据，来训练一个定制化的对话生成模型，以用于支持产品的自然语言处理功能）](apps/chatbot-kickstarter/powering_your_products_with_chatgpt_and_your_data.ipynb) [Mar 10th, 2023]
- [如何为ChatGPT模型格式化输入（如何将输入文本转化为适合于ChatGPT模型输入的格式，以便进行对话生成任务。）](examples/How_to_format_inputs_to_ChatGPT_models.ipynb) [Mar 1st, 2023]


## 使用指南 & 例子

- API 的使用
  - [如何处理限速](examples/How_to_handle_rate_limits.ipynb)
    - [通过并发解决限速问题的例子](examples/api_request_parallel_processor.py)
  - [如何计算消耗的token](examples/How_to_count_tokens_with_tiktoken.ipynb)
  - [流式生成文本的例子（使用"流式生成"可以实现用户输入文本时，实时生成文本补全或建议）](examples/How_to_stream_completions.ipynb)
- ChatGPT
  - [如何为ChatGPT模型格式化输入（如何将输入文本转化为适合于ChatGPT模型输入的格式，以便进行对话生成任务。）](examples/How_to_format_inputs_to_ChatGPT_models.ipynb)
  - [如何使用ChatGPT和自己的数据来提升产品（如何使用ChatGPT模型和自己的数据，来训练一个定制化的对话生成模型，以用于支持产品的自然语言处理功能）](apps/chatbot-kickstarter/powering_your_products_with_chatgpt_and_your_data.ipynb)
- GPT
  - [如何使用大型语言模型（如何使用大型语言模型，包括GPT和GPT-2等模型，以及如何在训练、调整和使用这些模型时避免常见的问题和挑战）](how_to_work_with_large_language_models.md)
  - [如何提高可靠性（一些可以提高模型可靠性的技术和方法，以确保模型在实际应用中的稳定性和准确性）](techniques_to_improve_reliability.md)
  - [如何使用多步骤提示编写单元测试(如何使用多步骤提示来编写自然语言处理模型的单元测试，以保证模型的准确性和稳定性)](examples/Unit_test_writing_using_a_multi-step_prompt.ipynb)
- Embeddings（Embeddings是指将输入的文本序列中的每个单词或字符转换为向量表示的过程。）
  - [文本比较示例（如何使用工具库实现文本比较任务，包括计算相似度、距离和匹配度等指标，以及应用于文本分类、信息检索、语义分析等自然语言处理任务）](text_comparison_examples.md)
  - [如何获取embeddings（如何使用预训练的嵌入模型或自定义的嵌入模型来获取文本的嵌入向量，以用于自然语言处理任务，如文本分类、相似度匹配、对话生成等）](examples/Get_embeddings.ipynb)
  - [如何在问答系统中使用embeddings（如何使用embeddings来实现问答系统，即根据用户提出的问题，从给定的文本语料库中找到相应的答案）](examples/Question_answering_using_embeddings.ipynb)
  - [如何使用向量数据库进行嵌入搜索（如何使用向量数据库来存储和搜索嵌入向量，以实现更加高效和快速的相似度搜索）](examples/vector_databases/Using_vector_databases_for_embeddings_search.ipynb)
  - [如何在搜索中使用embeddings（如何使用embeddings来实现语义搜索，即根据用户输入的查询，从给定的文本语料库中找到与查询最相关的文本）](examples/Semantic_text_search_using_embeddings.ipynb)
  - [如何在推荐系统中使用embeddings（如何使用embeddings来实现推荐系统，即根据用户的历史行为和喜好，推荐与之相关的商品、文章或其他内容）](examples/Recommendation_using_embeddings.ipynb)
  - [如何使用embeddings进行聚类分析（如何使用embeddings来实现聚类分析）](examples/Clustering.ipynb)
  - [如何二维可视化embeddings（如何使用工具库，将高维度的嵌入向量映射到二维空间中，并使用散点图等可视化工具来展示数据点之间的关系和相似度）](examples/Visualizing_embeddings_in_2D.ipynb) or [3D](examples/Visualizing_embeddings_in_3D.ipynb)
  - [长文本如何使用embeddings（如何使用工具库来对长文本进行embeddings的生成和处理）](examples/Embedding_long_inputs.ipynb)
- Fine-tuning GPT-3（训练自己的模型）
  - [微调GPT-3进行文本分类的最佳实践（如何使用GPT-3模型进行文本分类任务，并提供了一些最佳实践和技巧）](https://docs.google.com/document/d/1rqj7dkuvl7Byd5KQPUJRxc19BJt8wo0yHNwK84KfU3Q/edit)
  - [微调模型（如何使用预训练模型进行文本分类任务，并通过微调预训练模型来适应特定的任务和数据集）](examples/Fine-tuned_classification.ipynb)
- DALL-E（DALL-E能够通过给定的自然语言描述生成相应的图像）
  - [如何使用DALL-E模型生成和编辑图像](examples/dalle/Image_generations_edits_and_variations_with_DALL-E.ipynb)
- Azure OpenAI （Azure OpenAI和GPT API都是基于OpenAI GPT模型的API服务，但它们是由不同的公司提供的，具有不同的功能和定价模式）
  - [如何通过Azure OpenAI使用ChatGPT](examples/azure/chat.ipynb)
  - [如何使用Azure OpenAI获取文本自动补全](examples/azure/completions.ipynb)
  - [如何使用Azure OpenAI获取embeddings](examples/azure/embeddings.ipynb)
  - [如何使用Azure OpenAI微调模型](examples/azure/finetuning.ipynb)
- Apps
  - [基于文件的问答系统](apps/file-q-and-a/)
  - [基于网络的问答系统](apps/web-crawl-q-and-a)

## 相关资源

除了这里的代码示例，您可以从以下资源中了解[OpenAI API]:

- 尝试使用 [ChatGPT]
- 试用API [OpenAI Playground] 
- 阅读API文档 [OpenAI Documentation]
- 在论坛中讨论 [OpenAI Community Forum]
- 寻求帮助 [OpenAI Help Center]
- 查看例子 [OpenAI Examples]
- 追踪博客 [OpenAI Blog]

## 贡献

如果有你想看的例子或指南，请在[issues page]提出建议。

[chatgpt]: https://chat.openai.com/
[openai api]: https://openai.com/api/
[api signup]: https://beta.openai.com/signup
[openai playground]: https://beta.openai.com/playground
[openai documentation]: https://beta.openai.com/docs/introduction
[openai community forum]: https://community.openai.com/top?period=monthly
[openai help center]: https://help.openai.com/en/
[openai examples]: https://beta.openai.com/examples
[openai blog]: https://openai.com/blog/
[issues page]: https://github.com/openai/openai-cookbook/issues
