# finadvisor-llm-mvp
finadvisor-llm-mvp/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── architecture.md
│   ├── deployment.md
│   └── api_reference.md
├── src/
│   ├── app.py
│   ├── model/
│   │   ├── finetune.py
│   │   └── lora_config.py
│   ├── data/
│   │   ├── dataset_loader.py
│   │   └── preprocessing.py
│   └── utils/
│       ├── rag_retrieval.py
│       └── postprocess.py
├── examples/
│   ├── notebook/
│   │   └── demo_finadvisor.ipynb
│   └── screenshots/
│       └── sample_output.png
├── demo/
│   └── streamlit_app.py
├── tests/
│   ├── test_model.py
│   └── test_api.py
├── LICENSE
├── README.md
└── requirements.txt
.github/：CI、Issue/PR 模板，提升协作体验 
Reddit

docs/：系统架构、部署和 API 文档，降低上手门槛 
cw Richard Kim

examples/：交互 Notebook 与截图，展示核心功能与效果 
cw Richard Kim

tests/：单元与集成测试，保证项目稳定性 
Reddit
