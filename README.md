# chenguang-agent-platform

## 介绍
《辰光Agent平台》是企业内部整合、管理各种大模型与Agent的基础平台

## 软件架构
软件架构说明


## 安装教程
```sh
# 创建环境
conda create -n chenguang python=3.13
# 激活环境
conda activate chenguang

# 安装依赖
pip install -r requirements.txt
```

## env配置
把 .env.example 复制一份 叫 .env ，修改为自己的信息即可

## 指定端口启动
```
# 后端启动
uvicorn src.main:app --port 8080 --reload

# 前端启动
npm run dev
```



