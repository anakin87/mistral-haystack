# 📌 mistral-haystack collection
 **Mistral + Haystack Collection: build RAG pipelines that rock 🤘**

 Collection of notebooks and resources to build Retrieval Augmented Generation pipelines using:
 - [Mistral](https://mistral.ai/) models 🤖
 - [Haystack](https://github.com/deepset-ai/haystack) LLM orchestration framework 🏗️.


 <img src="https://static.otta.com/uploads/images/company-logos/17023-r1fn8E7CIWJX0L-iFw8YivXD9C37itYuFvVWW_xFh5k.svg" width="270" style="display:inline;"><img src="https://img.freepik.com/premium-vector/electric-guitar-fire-hot-rock-music-guitar-flames-hard-rock-rock-roll-concert-festival-label-night-club-live-show-vector-logo-emblem_570429-23178.jpg?w=2000" width="180"><img src="https://haystack.deepset.ai/images/haystack-ogimage.png" width="360" style="display:inline;">

 💻 **For other great Haystack Notebooks, check out the 👩🏻‍🍳 [Haystack Cookbook](https://github.com/deepset-ai/haystack-cookbook)**


## 📓 Notebooks

| **Model**                | **Haystack version** | **Link** | **Details**                                             | **Author** |
|--------------------------|----------------------|----------|---------------------------------------------------------|------------|
| Mistral-7B-Instruct-v0.1 | 1.x                  |  [🎸 Notebook](mistral_haystack.ipynb) | RAG on a collection of Rock music resources, using the free Hugging Face Inference API | [@anakin87](https://github.com/anakin87)   |
| Mixtral-8x7B-Instruct-v0.1 | 1.x                  |  [📄🚀 Notebook](https://colab.research.google.com/drive/1rH8df-C3P9pL4yrC2qSae9IOtx5Mr1N_) | RAG on a PDF File, using the free Hugging Face Inference API (using the free Hugging Face Inference API) | [@AlessandroDiLauro](https://github.com/alessandrodilauro)   |
| Mixtral-8x7B-Instruct-v0.1 | 1.x                  |  [🛒 Notebook](https://colab.research.google.com/drive/1LGaA2TcabnqU6jNrI6i598BeYWAX_xU-) <br/> [📊🔍 Blog post](https://medium.com/@alessandrodilauro72/enhancing-csv-data-retrieval-and-product-description-analysis-with-haystacks-retrieval-augmented-89140237110c) | RAG from CSV, Product description analysis | [@AlessandroDiLauro](https://github.com/alessandrodilauro)   |
| Mixtral-8x7B-Instruct-v0.1 | 2.x                  |  [🕸️💬 Notebook](https://colab.research.google.com/github/deepset-ai/haystack-cookbook/blob/main/notebooks/mixtral-8x7b-for-web-qa.ipynb) | RAG on the Web, using the free Hugging Face Inference API | [@TuanaCelik](https://github.com/tuanacelik)   |
| Zephyr-7B Beta | 2.x                  |  [🪁 Article and notebook](https://haystack.deepset.ai/blog/guide-to-using-zephyr-with-haystack2) | Article on how make  this great model (fine-tuned from Mistral) run locally on Colab | [@TuanaCelik](https://github.com/tuanacelik) [@anakin87](https://github.com/anakin87)   |
| Mixtral-8x7B-Instruct-v0.1 | 2.x                  |  [🩺💬 Article and notebook](https://haystack.deepset.ai/blog/mixtral-8x7b-healthcare-chatbot) | Healthcare chatbot with Mixtral, Haystack, and PubMed | [@annthurium](https://github.com/annthurium)   | |
| Mixtral-8x7B-Instruct-v0.1 | 2.x                  |  [🇮🇹🇬🇧🎧 Notebook](https://github.com/deepset-ai/haystack-cookbook/blob/main/notebooks/multilingual_rag_podcast.ipynb) | Multilingual RAG from a podcast | [@anakin87](https://github.com/anakin87)   | |
| Mixtral-8x7B-Instruct-v0.1 | 2.x                  |  [📰 Notebook](https://colab.research.google.com/drive/1mp4MVQEAFZ0Zz2AI9aJ1uOHJ5k73B2fr?usp=sharing) | Building a Hacker News Top Stories TL;DR | [@TuanaCelik](https://github.com/tuanacelik)  | |

## 📚 Resources

- [Mixture of Experts Explained](https://huggingface.co/blog/moe)

  Great and deep blog post by Hugging Face on the MoE architecture, which is the basis of Mistral 8x7B.

- [Zephyr: Direct Distillation of LM Alignment](https://arxiv.org/abs/2310.16944)
  
  Technical report by the Hugging Face H4 team.
  They explain how they trained Zephyr, a strong 7B model fine-tuned from Mistral.
  
  The main topic is: ⚗️ **how to effectively distill the capabilities of GPT-4 into smaller models?**
  The report is insightful and well worth reading. I have summarized it [here](https://www.linkedin.com/posts/stefano-fiorucci_llm-largelanguagemodels-nlp-activity-7129738807934885888-ADEX).

