# bot：一款人性化，具备情感的定制化AI Agent

[![python](https://img.shields.io/badge/python-3776AB.svg?logo=python&logoColor=white)](https://python.org/)
[![fastapi](https://img.shields.io/badge/fastapi-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=OpenAI&logoColor=white)](https://openai.com/)
[![langchain](https://img.shields.io/badge/langchain-1C3C3C?logo=langchain&logoColor=white)](https://python.langchain.com)
[![Ollama](https://img.shields.io/badge/Ollama-000000?logo=Ollama&logoColor=61DAFB)](https://ollama.ai/)
[![telegram](https://img.shields.io/badge/telegram-26A5E4?logo=telegram&logoColor=white)](https://telegram.org/)
[![chatbot](https://img.shields.io/badge/chatbot-0066FF?logo=chatbot&logoColor=white)](https://example.com/chatbot) 
[![redis](https://img.shields.io/badge/redis-FF4438?logo=redis&logoColor=white)](https://redis.io/)
[![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=Docker&logo=docker&logoColor=white)](https://www.docker.com/)

- 自然语言交互：文本、语音
- 具备知识学习能力
- 具备实时感知能力
- 具备记忆能力
- API可嵌入IM中
- 具备可扩展性
- 具备鲜明个性

### 服务器端：接口 -> langchain-> openai\ollama。。
### 客户端：电报机器人、微信机器人、website。
### 接口：http,https,websocket

### 服务器：
1. 接口访问，python选型fastapi
2. /chat的接口，post请求
3. /add_urls 从url中学习知识
4. /add_pdfs 从pdf里学习知识
5. /add_texts 从txt文本里学习

##人性化
1. 用户输入-> AI判断一下当前问题的情绪倾向？-> 判断-> 反馈 -> agent判断

2. 工具调用: 用户发起请求 -> agent判断使用哪个工具 -> 带着相关的参数去请求工具 -> 得到观察结果

### 截止目前：
1. api
2. agent框架
3. tools:搜索、查询信息、专业知识库
4. 记忆，长时记忆
5. 学习能力

## 从url来学习，实现增强
1. 输入URL
2. 地址的HTML变成文本
3. 向量化
4. 检索-》相关文本块
5. LLM回答

















要在Mac上安装Redis，您可以按照以下步骤进行操作：

1. 使用Homebrew安装Redis：
   - 打开终端应用程序。
   - 输入以下命令以安装Homebrew（如果您尚未安装）：
     ```
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
     ```
   - 安装完Homebrew后，运行以下命令以安装Redis：
     ```
     brew install redis
     ```

2. 启动Redis服务器：
   - 在终端中运行以下命令以启动Redis服务器：
     ```
     redis-server
     ```

3. 验证Redis是否正在运行：
   - 在终端中运行以下命令以连接到Redis服务器：
     ```
     redis-cli
     ```
   - 输入 `ping` 命令，如果返回 `PONG`，则表示Redis已成功安装并正在运行。

通过上述步骤，您应该能够在Mac上成功安装和运行Redis。