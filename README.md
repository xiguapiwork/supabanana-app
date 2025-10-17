# SupaBanana App

一个基于 Next.js 和 Supabase 的现代化全栈应用，包含用户认证、数据可视化、国际化等功能。

## 功能特性

- 🔐 用户认证系统（注册、登录、密码重置）
- 👤 用户资料管理（头像、用户名、密码设置）
- 📊 数据可视化和图表展示
- 🌍 国际化支持（中英文切换）
- 🌙 深色模式支持
- 📱 响应式设计
- 🔒 管理员权限控制
- 💰 积分系统

## 技术栈

- **前端**: Next.js 15, React 18, TypeScript
- **样式**: Tailwind CSS, shadcn/ui
- **后端**: Supabase (数据库 + 认证)
- **状态管理**: React Hooks
- **国际化**: next-intl
- **图表**: Recharts
- **UI组件**: Radix UI

## 项目结构

```
├── app/                    # Next.js App Router
│   ├── auth/              # 认证相关页面
│   ├── protected/         # 受保护的页面
│   └── api/               # API路由
├── components/            # React组件
│   ├── ui/               # UI基础组件
│   └── tutorial/         # 教程组件
├── lib/                  # 工具库
├── hooks/                # 自定义Hooks
├── messages/             # 国际化文件
└── public/               # 静态资源
```

## 开始使用

1. 克隆项目
2. 安装依赖：`npm install`
3. 配置环境变量
4. 运行开发服务器：`npm run dev`

## 环境变量

创建 `.env.local` 文件并配置以下变量：

```env
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
SUPABASE_SERVICE_ROLE_KEY=your_service_role_key
```

## 部署

项目支持部署到 Vercel、Netlify 等平台。

## 许可证

MIT License