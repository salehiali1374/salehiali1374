# Ali Salehi

**Applied AI / LLM Engineer** with a research background in reinforcement learning, fuzzy control and evolutionary optimization.

I build AI systems in Python, with a current focus on LLM applications: retrieval-augmented generation (RAG), retrieval quality and evaluation, and tool-calling agents, served with FastAPI and packaged with Docker. My research background shapes how I work on these systems: controlled experiments, honest baselines and measured results.

- M.S. in Artificial Intelligence, [Ferdowsi University of Mashhad](https://en.um.ac.ir/)
- CTO at [AHD Soft](https://ahdsoft.ir/) (previously Data Team Lead and Senior Data Scientist): led Yarabot, a Persian generative-AI platform with 80K+ users, SaaS RAG agents and private on-GPU LLM deployments for enterprise customers
- Languages: English, Persian

## Selected work

| Repository | What it shows |
| --- | --- |
| [hybrid-rag-eval](https://github.com/salehiali1374/hybrid-rag-eval) | Hybrid retrieval (BM25 + dense), cross-encoder reranking and evaluation for Persian RAG, served with FastAPI and Docker. On PersianQA (651 test questions), recall@1 rises from 0.909 (BM25) to 0.962 (tuned hybrid) and 0.986 (with bge-reranker-v2-m3); CI runs tests and a retrieval quality gate |
| [Interval-Type-2-Fuzzy-Control…COVID-19](https://github.com/salehiali1374/Interval-Type-2-Fuzzy-Control-and-Stochastic-Modeling-of-COVID-19-Spread) | Official code for a journal paper (Computer Methods and Programs in Biomedicine, 2023): GA-optimized type-2 fuzzy control of a stochastic epidemic model, compared against PD, PID and type-1 fuzzy baselines |
| [VIETFC](https://github.com/salehiali1374/VIETFC) | Code for a follow-up study on evolutionary type-2 fuzzy control under vaccination and isolation constraints |
| [Persian-Sentiment-Classification](https://github.com/salehiali1374/Persian-Sentiment-Classification) | Fine-tuning ParsBERT (Hugging Face Transformers, PyTorch) for Persian text classification |
| [Q-learning UAV path planning](https://github.com/salehiali1374/Q-learning-based-unmanned-aerial-vehicle-path-planning-with-dynamic-obstacle-avoidance) | Python reproduction and benchmark of A\*, Dijkstra, SARSA and Q-learning variants for UAV path planning |
| [Introduction-to-NLP-Workshop](https://github.com/salehiali1374/Introduction-to-NLP-Workshop) | Teaching material from an NLP workshop at the ICDS.ai Summer Bootcamp |

## Publications

- H. Rafiei, **A. Salehi**, F. Baghbani, P. Parsa, M.-R. Akbarzadeh-T. *Interval type-2 fuzzy control and stochastic modeling of COVID-19 spread based on vaccination and social distancing rates.* Computer Methods and Programs in Biomedicine, 232, 107443, 2023. [doi:10.1016/j.cmpb.2023.107443](https://doi.org/10.1016/j.cmpb.2023.107443)
- *Control of P53 gene regulatory network based on deep reinforcement learning and its application in cancer.* 9th Iranian Joint Congress on Fuzzy and Intelligent Systems (CFIS 2022). **Best Paper "AI for Good" Award.**
- *Improving the overestimation in off-policy deep reinforcement learning using Deep Selective Update Network (DSUN).* 27th International Computer Conference, Computer Society of Iran, 2022.

## Tools

Python · PyTorch · Hugging Face Transformers · scikit-learn · Keras · FastAPI · Elasticsearch · MongoDB · Redis · Docker · GitHub Actions · MATLAB · Git / Linux
