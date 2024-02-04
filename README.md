## 相关技术

前端:Next.js(React.js 18)  
服务端:Koa2+Sequelize(ORM)  
数据库:MySQL(InnoDB)+Redis

开发语言 TypeScript  
组件库使用 Ant Design  
CSS 方案 Tailwind CSS  
React 状态管理 Recoil

### 环境变量

1. client 文件夹在 env 文件夹中.env.production 文件并按照.env.development 填写完整
2. server 文件夹在 env 文件夹中将 template 重命名为环境变量名(development/production)后补全内容

### 启动

#### 环境

1. Node.js 18.x
2. MySQL 8.x
3. Redis

#### 启动步骤

1. 导入 SQL 文件
2. npm install yarn -g _(如果有 yarn 请忽略)_
3. 点击 install.bat 自动安装依赖 _(完成后关闭 cmd 窗口)_
4. 点击 dev.bat 启动项目

## 生产环境部署

项目同时使用了 pm2 和 socket.io 所以 pm2 要替换为@socket.io/pm2，安装过程见 install.bat。详情见[scoket.io 官网相关内容](https://socket.io/zh-CN/docs/v4/pm2/)
