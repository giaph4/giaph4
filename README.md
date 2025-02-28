# Dự Án Đa Nền Tảng: Vue 3 + Vite, Java & PHP 🚀

![Vue Logo](https://vuejs.org/images/logo.png)  
![Java Logo](https://www.java.com//en/img/java-logo-vert-blk.png)  
![PHP Logo](https://www.php.net/images/logos/new-php-logo.svg)  

Mẫu khởi tạo này giúp bạn phát triển ứng dụng kết hợp **Vue 3 + Vite** cho giao diện, **Java** cho backend, và **PHP** cho các dịch vụ bổ trợ.

---

## Giới thiệu ✨  
Dự án này tích hợp:  
- **Vue 3 + Vite**: Frontend nhanh nhẹn, hiện đại với `<script setup>` SFCs ([tài liệu](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup)).  
- **Java**: Backend mạnh mẽ với hiệu suất cao.  
- **PHP**: Xử lý logic phía сервер linh hoạt và đơn giản.  

---

## Cài đặt IDE khuyến nghị 🛠️  

### Cho Vue 3 + Vite  
- **[VS Code](https://code.visualstudio.com/)**  
  + **[Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar)** (tắt Vetur).  
  + **[TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin)**.  

### Cho Java  
- **[IntelliJ IDEA](https://www.jetbrains.com/idea/)** hoặc **[Eclipse](https://www.eclipse.org/)**.  

### Cho PHP  
- **[PHPStorm](https://www.jetbrains.com/phpstorm/)** hoặc VS Code với **[PHP Intelephense](https://marketplace.visualstudio.com/items?itemName=bmewburn.vscode-intelephense-client)**.  

---

## Hướng dẫn cài đặt ⚙️  

### 1. Frontend (Vue 3 + Vite)  
```bash  
git clone https://github.com/username/repository.git  
cd frontend  
npm install  
npm run dev

cd backend/java  
mvn clean install  
java -jar target/app.jar

cd services/php  
composer install  
php -S localhost:8000  
