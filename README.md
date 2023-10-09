# Resources to guide your LLM finetuning quest
Resources to aid your learning of LLM finetuning.  Guides for starters, intermediate and advamced users.


> **Shortcut to media of choice:**
> - [Reading Materials](#reading-materials)
> - [Videos](#videos)
> - [Code Samples](#code-samples)
> - [Whitepapers](#whitepapers)


## Reading Materials
| Content / Blog | Description | 
| ----------- | ----------- | 
| [RAG vs Finetuning](https://towardsdatascience.com/rag-vs-finetuning-which-is-the-best-tool-to-boost-your-llm-application-94654b1eaba7) | RAG vs Finetuning — Which Is the Best Tool to Boost Your LLM Application? The definitive guide for choosing the right method for your use case | 
| [RAG, Fine-tuning or Both?](https://www.matrixflows.com/blog/retrieval-augmented-generation-rag-finetuning-hybrid-framework-for-choosing-right-strategy) | RAG, Fine-tuning or Both? A Complete Framework for Choosing the Right Strategy | 
| [Optimizing LLMs](https://blog.lancedb.com/optimizing-llms-a-step-by-step-guide-to-fine-tuning-with-peft-and-qlora-22eddd13d25b) <h6>_[Accompanying code](https://pbase.ai/FineTuneLlama)_</h6><h6>_Good read_</h6>| Optimizing LLMs: A Step-by-Step Guide to Fine-Tuning with PEFT and QLoRA (A Practical Guide to Fine-Tuning LLM using QLora) |
| [Parameter-Efficient Fine-Tuning (PEFT)](https://huggingface.co/docs/peft/index) | PEFT methods only fine-tune a small number of (extra) model parameters, significantly decreasing computational and storage costs because fine-tuning large-scale PLMs is prohibitively costly. |
| [A guide to parameter efficient fine-tuning (PEFT)](https://www.leewayhertz.com/parameter-efficient-fine-tuning/) <h6>_Good read_</h6>| This article will discuss the PEFT method in detail, exploring its benefits and how it has become an efficient way to fine-tune LLMs on downstream tasks.|



## Videos
| Video | Description | 
| ----------- | ----------- | 
| [Efficient Fine-Tuning for Llama-v2-7b on a Single GPU](https://www.youtube.com/watch?v=g68qlo9Izf0) <h6>_Suggested watch_</h6> | This session will equip ML engineers to unlock the capabilities of LLMs like Llama-2 on for their own projects.  
| [Efficiently Build Custom LLMs on Your Data with Open-source Ludwig](https://www.youtube.com/watch?v=NAyKpcOdHLE)  <h6>_[Accompanying code](https://pbase.ai/3YDMrcz)_</h6> | detail for the video | 
| [Introduction to Ludwig - multi-model sample](https://www.youtube.com/watch?v=K7yLtB2yaPg) <h6>_[Accompanying code](https://colab.research.google.com/drive/1jJcikGm8lSZtWIfw5yAWHmQuALPsU_4p?usp=sharing)_</h6>| Train and Deploy Amazing Models in Less Than 6 Lines of Code with Ludwig AI|
|[Ludwig: A Toolbox for Training and Testing Deep Learning Models without Writing Code]() <h6>_Beginner friendly_</h6> | Ludwig, an open source, deep learning toolbox built on top of TensorFlow that allows users to train and test machine learning models without writing code. |


## Code Samples
| Sample | Description |
| ----------- | ----------- |
| [Parameter-Efficient Fine-Tuning (PEFT)](https://github.com/huggingface/peft) | PEFT methods only fine-tune a small number of (extra) model parameters, significantly decreasing computational and storage costs because fine-tuning large-scale PLMs is prohibitively costly. | 
| <a id="qloracode"></a>[QLoRA: Efficient Finetuning of Quantized LLMs](https://github.com/artidoro/qlora) <h6>_[whitepaper](#qlorawp)_</h6> | QLORA - an efficient finetuning approach that reduces memory usage enough to finetune a 65B parameter model on a single 48GB GPU while preserving full 16-bit finetuning task performance | 
| [Ludwig](https://github.com/ludwig-ai/ludwig) | Low-code framework for building custom LLMs, neural networks, and other AI models |
| [Ludwig 0.8: Hands On Webinar](https://colab.research.google.com/drive/1lB4ALmEyvcMycE3Mlnsd7I3bc0zxvk39#scrollTo=xb1aLHZRFrwA) <h6>[Webinar video](https://www.youtube.com/watch?v=NAyKpcOdHLE)</h6> | How integrations with Deepspeed and parameter-efficient fine-tuning techniques make training LLMs with Ludwig fast and easy |


## Whitepapers
| Sample | Description |
| ----------- | ----------- |
| [LoRA: Low-Rabm Adaptation of Large Language Models](https://arxiv.org/pdf/2106.09685.pdf)| Train with significantly fewer GPUs and avoid I/O bottlenecks. Another benefit is that we can switch between taskswhile deployed at a much lower cost by only swapping the LoRA weights as opposed to all the parameters|
| <a id="qlorawp"></a>[QLORA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/pdf/2305.14314.pdf) <h6>_[code sample](#qloracode)_</h6> | QLORA - an efficient finetuning approach that reduces memory usage enough to finetune a 65B parameter model on a single 48GB GPU while preserving full 16-bit finetuning task performance|

