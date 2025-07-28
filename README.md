e

## 简单可运行的后端模板

下面是一个使用 Node.js 和 Express 框架的简单后端模板示例：

```bash
# 初始化项目
npm init -y

# 安装 Express
npm install express
```

创建 `index.js` 文件：

```js
const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => {
    res.send('Hello, backend template!');
});

app.listen(port, () => {
    console.log(`Server running at http://localhost:${port}`);
});
```

启动服务：

```bash
node index.js
```

访问 [http://localhost:3000](http://localhost:3000) 即可看到输出。