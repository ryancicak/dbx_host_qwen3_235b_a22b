# Databricks - Host Qwen3 235B A22B model with two notebooks
Host the Qwen3 235B A22B model in Databricks. Two notebooks, one for hosting the model (on all-purpose compute), the other for sending requests. 

Notebook "all-purpose vllm qwen3 235b a22b - host"<br>
The goal of this notebook is to model serve via vLLM the Large MoE model Qwen3 235B A22B within Databricks (as an all purpose cluster). 
- The original author of this notebook is [Srinivas Billa](https://github.com/nivibilla).
- Requires an instance type of g6e.48xlarge or larger to run.
- Tested on DBR ML 16.4 LTS.
- Future goal: To get serverless involved in serving large MoE models such as Qwen3 (not only PaaS)

Notebook "all-purpose vllm - request"<br>
The goal of this notebook is send requests to the all-purpose vllm qwen3 235b a22b - host notebook.
- The original author of this notebook is [Srinivas Billa](https://github.com/nivibilla).
- Connect this notebook to the same all-purpose cluster as the notebook "all-purpose vllm qwen3 235b a22b - host".
