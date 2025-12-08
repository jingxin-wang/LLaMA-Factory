llamafactory api运行命令：
### Qwen2.5-7B-Instruct
API_PORT=6006 API_MODEL_NAME=Qwen/Qwen2.5-7B-Instruct llamafactory-cli api \
	--model_name_or_path Qwen/Qwen2.5-7B-Instruct \
	--template qwen
### Qwen2.5-VL-7B-Instruct
API_PORT=6007 API_MODEL_NAME=Qwen/Qwen2.5-VL-7B-Instruct llamafactory-cli api \
	--model_name_or_path Qwen/Qwen2.5-VL-7B-Instruct \
	--template qwen2_vl
### Meta-Llama-3.1-8B-Instruct
API_PORT=6008 API_MODEL_NAME=Meta-Llama-3.1-8B-Instruct llamafactory-cli api \
	--model_name_or_path meta-llama/Meta-Llama-3.1-8B-Instruct \
	--template llama3
### DeepSeek-R1-Distill-Qwen-7B
API_PORT=6008 API_MODEL_NAME=deepseek-ai/DeepSeek-R1-Distill-Qwen-7B llamafactory-cli api \
	--model_name_or_path deepseek-ai/DeepSeek-R1-Distill-Qwen-7B \
	--template deepseekr1
### explain_agent_item_feature_800
API_PORT=6006 API_MODEL_NAME=explain_agent_item_feature_800 llamafactory-cli api \
	--model_name_or_path /mnt/d/Users/27827/OneDrive/Desktop/推荐解释代理模型论文/explain_agent/code/module6/LLaMA-Factory/models/explain_agent/item_feature_800 \
	--template llama3
### explain_agent_user_cot
API_PORT=6006 API_MODEL_NAME=explain_agent_user_cot llamafactory-cli api \
	--model_name_or_path /mnt/d/Users/27827/OneDrive/Desktop/推荐解释代理模型论文/explain_agent/code/module6/LLaMA-Factory/models/explain_agent/user_cot \
	--template llama3