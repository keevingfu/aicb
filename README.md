# 内容大脑应用平台

一个基于 React 和 Vite 构建的现代化内容管理和营销平台。

## 项目结构

```
content-brain-platform/
├── src/
│   ├── components/         # 共享组件
│   ├── pages/             # 页面组件
│   │   ├── portals/       # 门户页面
│   │   ├── workspaces/    # 工作空间页面
│   │   └── panels/        # 功能面板页面
│   ├── layouts/           # 布局组件
│   ├── hooks/             # 自定义 Hooks
│   ├── utils/             # 工具函数
│   ├── styles/            # 样式文件
│   ├── types/             # TypeScript 类型定义
│   ├── services/          # API 服务
│   └── main.jsx          # 应用入口
├── public/                # 静态资源
├── vite.config.ts        # Vite 配置
├── package.json          # 项目依赖
└── README.md             # 项目文档
```

## 功能模块

1. **门户系统**
   - 内容创作者门户
   - 客服人员门户
   - 营销部署门户

2. **工作空间**
   - 内容创作工作台
   - 创意策划工作台
   - 营销策划工作台
   - 数据分析工作台
   - 运营工作台
   - 培训支持工作台
   - 客服代表工作台
   - 投放执行工作台

3. **功能面板**
   - 内容分析面板
   - 内容标签分析面板
   - 内容创作中心面板
   - 营销部署中心面板
   - 系统监控中心面板
   - 任务管理中心面板
   - 用户洞察面板

## 技术栈

- React 18
- Vite
- React Router v6
- TailwindCSS
- TypeScript
- Radix UI
- Lucide Icons

## 开始使用

1. 安装依赖
```bash
npm install
```

2. 启动开发服务器
```bash
npm run dev
```

3. 构建生产版本
```bash
npm run build
```

4. 预览生产版本
```bash
npm run preview
```

## 开发指南

### 路由结构

- `/login` - 登录页面
- `/portal` - 内容大脑门户
  - `/portal/content-creators` - 内容创作者门户
  - `/portal/customer-service` - 客服人员门户
  - `/portal/marketing` - 营销部署门户
- `/workspace` - 工作空间
  - `/workspace/content-creator` - 内容创作工作台
  - `/workspace/creative-planner` - 创意策划工作台
  - `/workspace/marketing-planner` - 营销策划工作台
  - `/workspace/data-analyst` - 数据分析工作台
  - `/workspace/operations` - 运营工作台
  - `/workspace/training-support` - 培训支持工作台
  - `/workspace/customer-service` - 客服代表工作台
  - `/workspace/delivery-executor` - 投放执行工作台
- `/panel` - 功能面板
  - `/panel/content-analysis` - 内容分析面板
  - `/panel/content-tag-analysis` - 内容标签分析面板
  - `/panel/content-creation` - 内容创作中心面板
  - `/panel/marketing-deployment` - 营销部署中心面板
  - `/panel/system-monitoring` - 系统监控中心面板
  - `/panel/task-management` - 任务管理中心面板
  - `/panel/user-insights` - 用户洞察面板
  - `/panel/main-control` - 主控制面板

### 开发规范

1. **代码风格**
   - 使用 TypeScript 进行类型检查
   - 遵循 ESLint 规则
   - 使用 Prettier 进行代码格式化

2. **组件开发**
   - 使用函数组件和 Hooks
   - 遵循组件复用原则
   - 保持组件职责单一

3. **状态管理**
   - 使用 React Context 进行全局状态管理
   - 合理使用 localStorage 存储持久化数据
   - 遵循状态最小化原则

4. **样式开发**
   - 使用 TailwindCSS 进行样式开发
   - 遵循响应式设计原则
   - 保持样式的一致性

## 部署说明

1. **环境要求**
   - Node.js >= 16.0.0
   - npm >= 7.0.0

2. **部署步骤**
   ```bash
   # 安装依赖
   npm install

   # 构建生产版本
   npm run build

   # 部署 dist 目录到服务器
   ```

3. **环境变量配置**
   - 创建 `.env` 文件配置环境变量
   - 根据不同环境创建对应的环境变量文件

## 贡献指南

1. Fork 项目
2. 创建特性分支
3. 提交变更
4. 推送到分支
5. 创建 Pull Request

## 许可证

MIT License 
