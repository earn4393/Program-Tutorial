การสร้างโปรเจค React 
1 เตรียมเครื่องมือที่ต้องใช้ประกอบด้วย
  1.1 node.js : install Node.js ลงบน Desktop
  1.2 React : 'npm install -g creat-react-app' ลงในโฟลเดอร์โปรเจค
2 สร้างโปรเจค
  2.1 fontend : 
      npx create-react-app PROJECT NAME 
      npm install axios 
  2.2 backend : 
      npm init -- yes
      npm install express body-parser 
3 การรันโปรเจค
    3.1 fontend : npm start
    3.2 backend : node app.js
4 การ deploy locall
  4.1 fontend :
    npm run build ->   เข้าไฟล์ build -> npx serve -l PORT -s
    npm i -g serve
  4.2 backend : รัน node app.js  ไว้พร้อมกับรัน build
5 การ deploy ใน backend 
  5.1 backend : pm2 start {app.js} -- name {my-api}
  5.2 fontend : pm2 serve build PORT -- name {my-api} --spa
    
