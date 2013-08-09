## 課程規劃

課程對象：

1. 本課程設定的對象是完全沒有接觸過 NodeJS 的學員
2. 必須有基本的 JavaScript 程式設計能力

本課程分為三大部份：

1. 準備開發環境
2. 工具介紹
3. 開始寫 NodeJS 程式

### 準備開發環境

* 1.1 NodeJS 安裝教學: Mac

```
brew install nodejs
```

* 1.2 NodeJS 安裝教學: Ubuntu 

```
sudo apt-get update
sudo apt-get install python-software-properties python g++ make
sudo add-apt-repository ppa:chris-lea/node.js
sudo apt-get update
sudo apt-get install nodejs
```

* 1.3 NodeJS 安裝教學: Windows


### 工具介紹

* 1.4 認識 NPM 套件管理工具, https://npmjs.org/
* 1.5 認識 NVM 多版本 Node 管理工具, https://github.com/creationix/nvm

```
curl https://raw.github.com/creationix/nvm/master/install.sh | sh
nvm install 0.10
nvm use 0.10
nvm run 0.10
nvm ls
nvm deactivate
```

* 1.6 認識 REPL 命令列工具

### 開始寫 NodeJS 程式

* 1.7 我的第一個 NodeJS 程式 (Run first NodeJS application) - hello.js
* 1.9 撰寫 HTTP Server 程式 (Build a simple Web server with http module) - server.js
* 1.11 學習 URL Routing (Route url requests with url module) - server-route.js
* 1.13 如何解析 Query String (Handle URL parameters with query string module)  - server-qs.js
* 1.15 處理靜態檔案的請求 (Serve static file on web server with File System module) - server-fs.js

