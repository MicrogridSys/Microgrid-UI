## 如何运行
### 所需环境
```bash
node >= 12(推荐16)
```

### 修改后端ip
```bash
# 修改ruoyi-ui\vue.config.js文件 第38行
# 将localhost修改为对应后台主机10.33.129.184

# 修改后代码
target: `http://10.33.129.184:8080`,
```

### 前端运行
```bash
# 进入项目目录
cd ruoyi-ui

# 安装包依赖
npm install --registry=https://registry.npmmirror.com

# 启动服务
npm run dev
```

浏览器访问 http://localhost:80

### 相关链接

> [强制删除包依赖（node_module）](https://blog.csdn.net/qq_39889855/article/details/125197551)