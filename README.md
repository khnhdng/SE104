//Project: [SE104] – SE104 Board:https://trello.com/b/hhUd6Nn4/%C4%91%E1%BB%93-%C3%A1n \
// 21521975 - Lê Bá Khánh Dũng (NT)\
// 21522698 - Phan Huỳnh Thiên Trang\
// 21520602 - Đỗ Gia Bảo\
// 21521840 - Trần Nguyễn Tuấn Anh\
// 21522484 - Đoàn Thị Tuyết Phương\





// Hướng dẫn chạy \
npm init

npm -v

npm install --save body-parser@1.19.0 dotenv@8.2.0 ejs@3.1.5 express@4.17.1  \
npm install --save-dev @babel/core@7.12.10 @babel/preset-env@7.12.10\
npm install --save-dev sequelize-cli@6.2.0\
npm install --save mysql2@2.2.5\
npm install --save sequelize@6.6.2\
npm install --save multer

npm start

npx sequelize-cli db:migrate

//Insert data

node ./src/insert/insertLoaiThe.js

node ./src/insert/insertLoaiChungChi.js

node ./src/insert/insertLoaiCauThu.js

node ./src/insert/insertLoaiBanThang.js

node ./src/insert/insertChungChi.js

node ./src/insert/insertDoiBong.js

node ./src/insert/insertChucVu.js

node ./src/insert/insertCauThu.js

node ./src/insert/insertLichThiDau.js

node ./src/insert/inserHuanLuyenVien.js

node ./src/insert/insert_loaicauthu.js

node ./src/insert/insertDienBien.js
