# Website
Tạo 1 dự án React (Front End)
npx create-react-app cilent
cd frontend
npm install
Tạo Backend
mkdir server && cd server
npm init -y
npm install express

Xóa tiến trình
netstat -ano | findstr :3000
TCP    127.0.0.1:3000    0.0.0.0:0    LISTENING    9876
taskkill /PID 9876 /F
