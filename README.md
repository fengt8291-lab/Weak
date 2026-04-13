# 测测你的人性弱点 (Weak)

基于卡内基《人性的弱点》的人际弱点测试网站。

## 产品概述

通过25道场景化选择题，诊断你在人际交往中的6大弱点维度：
- 🔍 批评型 - 习惯性挑剔，总看到别人缺点
- ❄️ 冷漠型 - 只在乎自己，忽视对方感受
- 🪞 自恋型 - 聊天只说自己，不问对方
- 🧠 记不住型 - 经常忘记别人名字和信息
- 🛡️ 防御型 - 遇到分歧必须赢，无法接受不同意见
- 🤲 索取型 - 只关注自己想从对方那里得到什么

## 技术栈

- Flask (Python)
- SQLite 数据库
- 原生 HTML/CSS/JS
- 智谱 AI (GLM-4-Flash) 个性化报告

## 快速开始

```bash
# 安装依赖
pip install flask

# 设置环境变量
export WEEK_CODE="your-week-code"
export ADMIN_PASSWORD="your-admin-password"

# 运行
python app.py
```

## 访问地址

- 本地：http://localhost:5002
- 演示模式：任意通行码均可进入

## 部署

使用 Gunicorn + Nginx 部署到服务器。

## 相关项目

- AISoul: https://github.com/fengt8291-lab/aisoul

## 许可证

MIT
