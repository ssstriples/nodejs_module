# nodejs_module

## NODE JS

0. 환경설정
```
1. node version 확인
node -v

2. node 다운로드
https://nodejs.org/en/

3. npm package만들기
npm init

4. express js 다운로드
npm install express --save
```
```
5. 노드 App 시작
- package.json 스크립트 작성
  "scripts": {
    "start" : "node index.js"
  },

- npm run start
http://localhost:5000/
```
```
const express = require('express')
const app = express()
const port = 5000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`)
})
```

1. boiler-plate
