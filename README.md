# LaoShihJi
- Lao(老)Shih(司)Ji(機)
- LSJ-CLI

# 初始安裝
```bash=
npm ci
```

# CLI 名稱修改
打開 package.json 檔案
```
"bin": {
    "lsj": "./index.js"
  },
```
修改 lsj 成為你想要的名稱

# 原始程式碼連結安裝
```
npm link
```
這個指令將會幫助你把這個資料夾放進你的全域node module 中，
這樣你就不用部署到 npm 上就能直接使用。

# 原始程式碼連結解安裝
lsj-cli 是 package.json 檔案 name 的欄位內容
```
npm unlink lsj-cli
```

# CLI 範例測試
lsj 是 package.json 檔案 bin 的欄位內容
```
lsj -d 1234
```

# 讀取 Excel 檔案 GameList.xlsx 轉換為 GameList.csv 檔案
```
lsj -e
```

# 猜星座
```
lsj -a
```
使用 https://github.com/cronvel/terminal-kit 套件來取得輸入
```
npm install terminal-kit
```

# abstract syntax tree
```
lsj -a 1
```
```
npm install @babel/parser
```

