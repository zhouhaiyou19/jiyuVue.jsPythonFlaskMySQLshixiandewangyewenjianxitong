# 基于Vue.js + Python Flask + MySQL实现的网页文件系统

## 项目简介

本项目是一个综合性的前后端分离应用示例，通过结合现代前端框架Vue.js、轻量级Web服务器框架Python Flask以及关系型数据库MySQL，实现了一个功能完备的网页文件管理系统。系统旨在模拟传统文件系统的在线操作，包括但不限于文件上传、下载、删除、重命名、目录浏览等核心功能，同时也支持用户权限管理，确保数据的安全访问。

## 技术栈

- **前端**：Vue.js（构建界面）、Vuex（状态管理）、Vue Router（路由管理）
- **后端**：Python Flask（Web服务框架）、Flask-SQLAlchemy（ORM，用于数据库交互）
- **数据库**：MySQL（存储文件元数据、用户信息）
- **其他**：Axios（前端HTTP请求库）、Bootstrap Vue（快速页面样式布局）

## 功能特点

1. **用户认证**：登录/注册系统，保证文件访问的安全性。
2. **文件管理**：
   - 上传文件至云端，支持多文件同时上传。
      - 文件下载，直接从系统下载文件到本地。
         - 实现文件夹创建、删除、重命名等基本操作。
            - 文件搜索，便捷查找目标文件或文件夹。
            3. **权限控制**：不同用户对文件的操作权限可以被设定，确保数据安全。
            4. **响应式设计**：适配多种设备，无论是桌面还是移动设备都能流畅体验。
            5. **日志记录**：后台可记录重要操作日志，便于追踪和审计。

            ## 快速启动

            ### 后端部署步骤：

            1. 安装Python环境。
            2. 使用`pip`安装依赖：在后端项目根目录运行`pip install -r requirements.txt`。
            3. 配置数据库连接，在配置文件中设置正确的MySQL连接参数。
            4. 运行后端服务器：使用命令`flask run`。

            ### 前端开发与部署：

            1. 确保已安装Node.js。
            2. 在前端目录下执行`npm install`安装所需依赖。
            3. 运行前端开发服务器：使用命令`npm run serve`。
            4. 访问`http://localhost:8080`查看并测试应用。

            ## 注意事项

            - 在实际部署前，请确保所有环境变量正确配置，尤其是数据库连接字符串。
            - 考虑安全性，生产环境中应启用HTTPS，并对敏感数据加密处理。
            - 数据库初始化脚本和初始用户配置可能需要根据实际情况进行调整。

            这个项目是学习和理解全栈开发流程的绝佳实践，适合Vue.js和Flask的初学者及进阶开发者进行研究和扩展。希望本项目的分享能够帮助大家在实际开发中有所启发和收获。

            ## 下载链接
            [基于Vue.jsPythonFlaskMySQL实现的网页文件系统](https://pan.quark.cn/s/68f7f0501b93) 

            (备用: [备用下载](https://pan.baidu.com/s/1DEmaWiQtX6DhZL550qkgbQ?pwd=1234))

            ## 说明

            该仓库仅用于学习交流，请勿用于商业用途。
