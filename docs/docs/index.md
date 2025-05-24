
# **使用 DashScope 的 LangGraph**  
[![GitHub Stars](https://img.shields.io/github/stars/611de/DashGraph?style=social)](https://github.com/611de/DashGraph) [![License](https://img.shields.io/github/license/611de/DashGraph)](LICENSE)


## **简介**  
本仓库旨在通过 **阿里云大模型开发平台 DashScope** 复现 [LangGraph](https://github.com/langgraph/langgraph) 官方教程，探索大模型应用开发的全流程实践。LangGraph 是面向大语言模型的应用开发框架，结合 DashScope 的 API 能力，可快速实现对话系统、文本生成、工具调用等场景。  

**目标**：  
- 多写几个教程的实现
- 可运行的官方教程代码示例（含注释与优化）；  
- 展示 DashScope 与 LangGraph 的集成；  
- 使用 GitHub Page 自动展示实现的笔记本


<!-- ## **目录结构**  
```plaintext
├── examples/                  # 官方教程复现案例
│   ├── basic_chain/           # 基础链示例（如检索-回答链）
│   ├── agent_with_tools/      # 工具调用代理示例
│   └── custom_component/      # 自定义组件开发示例
├── docs/                      # 文档与资源
│   ├── images/                # 示意图与截图
│   ├── dashscope_api_ref.md   # DashScope API 快速参考
│   └── langgraph_guide.md     # 框架核心概念图解
├── scripts/                   # 辅助脚本（如环境配置、数据预处理）
├── tests/                     # 单元测试
├── .env.example               # 环境变量示例文件
├── requirements.txt           # 依赖清单
└── README.md                  # 项目说明
``` -->


## **快速开始**  
### **1. 环境准备**  
```bash
# 克隆仓库
git clone https://github.com/611de/DashGraph.git
cd DashGraph

# 创建虚拟环境（推荐）
python -m venv venv
source venv/bin/activate  # Linux/macOS
.\venv\Scripts\activate   # Windows

# 安装依赖
pip install -r requirements.txt
```  

### **2. 配置 API 密钥**  
- 前往 [阿里云 DashScope 控制台](https://dashscope.aliyun.com/) 获取 API Key；  
- 将密钥添加到项目根目录的 `.env` 文件中：  
```bash
DASHSCOPE_API_KEY=your_api_key_here
```  

<!-- ### **3. 运行示例**  
```bash
# 运行基础链示例（如文档问答）
python examples/basic_chain/document_qa.py
```   -->


## **核心特性**  
| 特性                | 说明                                                                 |  
|---------------------|----------------------------------------------------------------------|  
| **官方教程复现**     | 完整复现 LangGraph 文档中的示例，包含代码注释与优化建议。            |  
| **DashScope 集成**   | 封装 DashScope API 工具（如 `DashScopeLLM` 组件），简化模型调用流程。 |  
| **可视化支持**       | 包含流程图（如链结构、代理执行路径），可通过 `langgraph plot` 命令生成。 |  
<!-- | **最佳实践指南**     | 在 `docs/best_practices.md` 中提供性能优化、成本控制与调试技巧。     |   -->


<!-- ## **贡献指南**  
我们欢迎社区贡献！如需参与开发：  
1.  Fork 本仓库并创建个人分支：  
   ```bash
   git checkout -b feature/new-example
   ```  
2.  编写代码并添加单元测试（位于 `tests/` 目录）；  
3.  提交 Pull Request（PR）并说明变更内容，需通过代码格式检查（`black`/`isort`）。   -->
<!-- 
**贡献类型**：  
- 复现更多官方教程（如多轮对话、函数调用）；  
- 优化现有示例的代码可读性或性能；  
- 补充文档或示意图；  
- 修复 BUG 或提出改进建议。   -->
<!-- ## **许可证**  
本项目采用 **MIT 许可证**，详见 [LICENSE](LICENSE) 文件。允许商业使用、修改和再发布，但需保留原作者声明。  
 -->

## **引用**  
- [LangGraph](https://github.com/langgraph/langgraph)
- [DashScope](https://dashscope.aliyun.com/)  
- [豆包](https://www.doubao.com/product)