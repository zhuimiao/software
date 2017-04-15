#gitbook
## 本小节知识点：
1. gitbook 怎么安装
2. gitbook 配置环境时遇到的坑

---
## 1. gitbook 怎么安装
1. [node.js](https://nodejs.org/en/) 下载并按默认一步步安装
2. 安装 gitbook-cli

```
npm install gitbook-cli -g
```

## gitbook 配置环境时遇到的坑
### 1. npm : command not found

* profile 添加 java 环境， 影响的用不了
```
改回原来的
```

### 2. gitbook : command not found
* 没权限，无法安装
```
sudo npm install gitbook-cli -g
```
