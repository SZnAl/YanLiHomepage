
## 运行

```
npm install
```

本地服务器运行可全局安装 `live-server`，执行代码：

```
npm install -g live-server  
```

```
live-server
```

## 本地测试

使用 node-sass 编译 sass 到 css，可全局安装或者本地安装 node-sass。

- 全局安装 node-sass，执行以下代码编译 sass： 

  ```
  npm install -g node-sass
  ```

  ```
  node-sass sass/main.scss css/style.css 
  ```

- 本地安装 node-sass，使用 npm script 命令执行编译，执行代码：

  ```
  npm install --save-dev node-sass
  ```

  ```
  npm run start
  ```

