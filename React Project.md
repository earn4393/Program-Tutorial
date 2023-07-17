# การสร้างโปรเจค React 
## 1 เตรียมเครื่องมือที่ต้องใช้ประกอบด้วย
1. node.js : install Node.js ลงบน Desktop
1. React : 'npm install -g creat-react-app' ลงในโฟลเดอร์โปรเจค
## 2 สร้างโปรเจค
1. fontend : 
    npx create-react-app PROJECT NAME 
    npm install axios 
1. backend : 
    npm init -- yes
    npm install express body-parser 
## 3 การรันโปรเจค
1. fontend : npm start
1. backend : node app.js
## 4 การ deploy locall
1. fontend :
    npm run build ->   เข้าไฟล์ build -> npx serve -l PORT -s
    npm i -g serve
1. backend : รัน node app.js  ไว้พร้อมกับรัน build
## 5 การ deploy ใน backend 
1. backend : pm2 start {app.js} -- name {my-api}
1. fontend : pm2 serve build PORT -- name {my-api} --spa
    


## more
1. sweetalert2 : https://sweetalert2.github.io/v9.html
2. flash icons : https://www.flaticon.com/
