TXL-1214/                   # 项目根目录
│
├── frontend/               # 前端代码 (UniApp + Vue2)
│   ├── pages/              # 页面目录
│   │   ├── login.vue       # 登录页面
│   │   ├── home.vue        # 主页面
│   │   └── upload.vue      # 数据上传页面
│   │
│   ├── utils/              # 工具类
│   │   └── request.js      # 网络请求封装
│   │
│   ├── App.vue             # 入口文件
│   └── main.js             # Vue 入口配置
│
├── backend/                # 后端代码 (Node.js + Express)
│   ├── routes/             # 路由目录
│   │   ├── auth.js         # 登录路由
│   │   ├── upload.js       # 数据上传路由
│   │   └── devices.js      # 设备管理路由
│   │
│   ├── models/             # 数据模型
│   │   └── deviceModel.js  # 设备数据模型
│   │
│   ├── server.js           # 主服务文件
│   └── package.json        # 后端依赖配置
│
├── Dockerfile              # Docker 部署配置文件
├── README.md               # 项目说明文档
└── deploy_docs/            # 部署文档
    ├── baota_deploy.md     # 宝塔面板部署文档
    └── docker_deploy.md    # Docker 部署指南


![image](https://github.com/user-attachments/assets/7e55cd8b-0636-45f6-a3cc-e8ac9227b57f)
