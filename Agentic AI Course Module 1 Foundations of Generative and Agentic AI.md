# Learning Outcomes
#### **Course learning outcomes addressed in this module:**
- Explain the evolution and landscape of generative AI
- Distinguish between major AI model types and terminology
- Evaluate the strategic value of AI functionalities such as chatbots, reasoning, and multimedia
#### **Module learning outcomes addressed:**
1. Evaluate the strategic value of AI functionalities such as chatbots, reasoning, and multimedia
2. Construct an evaluation of the cost of an AI system
3. Distinguish between major AI model types and terminology
## content

- generative AI is powered by **machine learning,** the foundational technology of LLMs. 
	- Machine learning involves training algorithms on large data sets to recognize patterns, make predictions, and improve performance over time, without being explicitly programmed.
- old: predictive AI vs now: generative AI
- **Neural networks** are the engines that power LLMs and enable them to model and learn complex relationships at scale (Stöffelbauer, 2023).
- The term “**deep learning**” refers to the fact that neural networks can be made up of large numbers of layers (in other words, they are deep). In deep learning, data is processed in a hierarchical manner, extracting complex features at each level.
- Generative adversarial networks (GANs) consist of two neural networks: a **generator** and a **discriminator**. The generator creates fake data, while the discriminator evaluates whether the data is real or fake.
- **Natural language processing** encompasses the broader field of teaching machines to understand and generate human language.
- Transformers use a mechanism called **self-attention** to weigh the importance of each word against all others in the input data.This allows them to maintain context over long passages, which is essential for chatbots’ text generation capabilities. Unlike traditional neural networks, transformers are probabilistic. ChatGPT, starting with GPT-3, was a milestone in the evolution of transformer-based models.
- LLMs undergo multistage training process
	- pre training - the LLM adjusts the internal weightages to determine strength of connections in the neural networks
	- fine tuning - trained on a specialized set of data, e.g. purpose-fully trained for the tasks, like customer service. 
	- reinforcement learning - human evaluators review the model outputs, scoring for accuracy, relevance and style. these give feedback to the LLM to correct 
- Prompt engineering

## Activity
- chatbots
	-  basic, conversational, generative AI
- Reasoning models: These models are trained to spend more time processing queries and thinking through problems before responding
- **Chain-of-thought prompting** is designed to significantly improve the ability of LLMs to perform complex reasoning. It involves generating a series of intermediate natural language reasoning steps that lead to the final answer for a problem, simulating a human-like thought process for arriving at a solution.

## 3. Cost-Optimized Models and Performance Trade-Offs

1. The Equipment (Compute Infrastructure)
2. The System (AI Model Choice and Tokens)
3. The Energy (Electricity and Environmental Cost)

Performance trade-offs
- **Accuracy vs. Cost**
- **Speed vs. Power**
- **Context Length vs. Efficiency**
## 4. Multimodal AI: Audio, Image, and Language Systems

At first glance, speech and voice interaction seem simple because we use them every day. In reality, enabling machines to understand and generate speech requires sophisticated AI systems. This section introduces the key technologies behind audio and language interaction and how organizations use them in practice.

Along with these technologies comes a wide range of options. As we have seen in other areas of digital transformation, choosing wisely ensures not only technical appropriateness but also alignment with your business’s financial goals.

Before diving deeper, let’s establish some basic definitions. This will help you make valuable distinctions between seemingly similar functionalities, participate more effectively in stakeholder conversations, and conduct more nuanced research.

|                              |                                                             |                                                                         |                                                                |                                                                  |
| ---------------------------- | ----------------------------------------------------------- | ----------------------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------------- |
| **Level**                    | **Description**                                             | **Example Tools**                                                       | **Best For**                                                   | **Trade-Offs**                                                   |
| **Off-the-Shelf APIs**       | Hosted models you call via API. No setup. Pay-per-use.      | DALL-E 3 (OpenAI API), Stability AI’s DreamStudio, Adobe Firefly        | Quick prototypes, marketing images, general content needs      | Limited fine-tuning. Pay for every call. Potential data lock-in. |
| **Open-Source Local Models** | Install models on your own servers (or in a private cloud). | Stable Diffusion (base and XL), HuggingFace Diffusers                   | More control over images, privacy, brand consistency           | Setup cost, compute expense, need in-house AI expertise.         |
| **Custom Fine-Tuned Models** | Train a model on your proprietary style/data.               | DreamBooth (for style), LoRA fine-tuning, custom Stable Diffusion forks | High-volume, brand-specific content, “signature style” visuals | Very expensive training. Must maintain and update models.        |

## 5. AI Tools and the Shift Toward Agentic AI

As we have seen throughout this module, generative AI is already reshaping how organizations create text, audio, visual content, and more. But content creation is only the beginning. The next frontier of digital transformation lies in agentic AI—systems that do not just respond to commands but also take initiative, make decisions, and coordinate across tools autonomously. Imagine AI that can not only write a marketing email but also generate graphics, schedule a campaign, respond to performance data, and refine its approach over time. These agents represent a shift from passive tools to active collaborators, and in the next module, we will explore how this evolution opens up new possibilities for automation, personalization, and digital intelligence at scale.

#AI #MIT #agenticAI #learning #course


## assignment 1: Tokens and APIs

tools
- OpenAI GPT API Pricing Calculator
  https://gptforwork.com/tools/openai-chatgpt-api-pricing-calculator
- OpenAI's large language models process text using **tokens**, which are common sequences of characters found in a set of text. The models learn to understand the statistical relationships between these tokens, and excel at producing the next token in a sequence of tokens. [Learn more](https://platform.openai.com/docs/concepts#tokens)
  - https://platform.openai.com/tokenizer
- Learning Facilitator David Whyte's github repo
  https://github.com/dlwhyte/AgenticAI_foundry
- LF David's google drive
  https://drive.google.com/drive/folders/1jLPjSBhO_-Hpi9RYD25Vc-hR30BODCiw
- 