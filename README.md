# WebRTC

> https://www.youtube.com/watch?v=DvlyzDZDEq4&t=145s

```
npm init -y

# express: 서버
# ejs: 템플릿 언어
# socket.io: 실제 서버와 통신
npm i express ejs socket.io

# uuid: 모든 방에 대해 동적 고유 uuid를 가지기 때문에

# 특정 방에서 채팅하기 위함
npm i uuid

# 자동 새로고침
npm i --save-dev nodemon
```

### package.json

```json
"scripts": {
    "devStart": "nodemon server.js"
    ...
```

### cli

```
npm run devStart
```

- write server.js
- write views/room.ejs
- wirte public/script.js

### install peer js

```
npm i -g peer
```

# run peerjs

```
peerjs --port 3001
```

peer 서버: 사용자에 대한 모든 WebRTC 정보를 취하고, 사용하기 쉬운 ID로 변환시킴
