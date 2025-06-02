# llm_practice
This project aims to systematically implement and explore key technologies in large language models (LLMs), including but not limited to model architecture, training methods, optimization techniques, and application development. The complete implementation process will be documented for technical exchange and learning purposes.


## 目录
```
├── peft/                  # PEFT, 高效微调方法
│   ├── clm/               # CLM (Causal LM), 因果大语言模型
│       └── qwen2.5        # 对应的模型
            └── lora.ipynb     # 微调代码
            └── output         # 训练后得到的结果
├── dataset/               # 用于训练的代码
│   ├── huanhuan-100.json  # 嬛嬛指令数据集
│   ├── huanhuan.json/     # 嬛嬛指令数据集
└── README.md                 # 项目说明
```