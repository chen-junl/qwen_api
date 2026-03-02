# qwen_api

## 安装ollama
curl -fsSL https://ollama.com/install.sh | sh

## 启动ollama
ollama serve > ollama.log 2>&1 &

## 下载并运行 Qwen 模型
ollama run qwen:7b