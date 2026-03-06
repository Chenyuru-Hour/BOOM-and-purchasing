# BOOM-and-purchasing
用于将BOOM整合成采购表/入库表
```bash
BOOM-and-purchasing
├──purchase_list_web/
│  ├── app.py                 # Flask主应用
│  ├── processor.py           # 核心处理逻辑（提取、合并、生成）
│  ├── templates/
│  │   └── index.html         # 上传页面
│  ├── uploads/                # 临时存放上传的文件
│  ├── outputs/                # 存放生成的采购清单文件
│  ├── requirements.txt       # 依赖列表
│  └── rules.md               #项目需求
├── README.md
└── .gitignore
```
