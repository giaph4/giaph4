# Dự Án Full-Stack: Java Backend & Vue 3 (Phụ Trợ)


## Giới Thiệu

Dự án này là hệ thống full-stack tập trung vào **Java Backend**, sử dụng **Spring Boot** và **Hibernate** để xử lý logic, API, và truy vấn cơ sở dữ liệu. **Vue 3 + Vite** chỉ được dùng như một công cụ giao diện phụ trợ, trong khi **PHP** được tích hợp để hỗ trợ các API bổ sung hoặc xử lý nhanh.

## Kiến Trúc Hệ Thống

- **Backend (Chính)**: Java, Spring Boot, Hibernate, RESTful API.
- **Frontend (Phụ Trợ)**: Vue 3, Vite, JavaScript, HTML, CSS.
- **Dịch Vụ Phụ Trợ**: PHP để tích hợp API bổ sung.
- **Cơ Sở Dữ Liệu**: MySQL (production), H2 (testing).

## Thống Kê Ngôn Ngữ Sử Dụng

![Thống kê ngôn ngữ sử dụng](https://quickchart.io/chart?c={type:'pie',data:{labels:['Java','Spring Boot','Vue 3','PHP'],datasets:[{data:[50,40,5,5]}]}})

| Ngôn ngữ/Công nghệ | Tỷ lệ sử dụng | Mức độ thành thạo |
| ------------------ | ------------- | ----------------- |
| **Java**           | 50%           | Tốt               |
| **Spring Boot**    | 40%           | Tốt               |
| **Vue 3**          | 5%            | Cơ bản            |
| **PHP**            | 5%            | Cơ bản            |

## Công Nghệ & Công Cụ

| Danh Mục        | Công Nghệ/ Công Cụ           | Mục Đích Sử Dụng           |
| --------------- | ---------------------------- | -------------------------- |
| **Backend**     | Java, Spring Boot, Hibernate | Xử lý logic, API, database |
| **Frontend**    | Vue 3, Vite, HTML, CSS, JS   | Giao diện (phụ trợ)        |
| **Database**    | MySQL, H2                    | Lưu trữ dữ liệu            |
| **Services**    | PHP                          | API bổ sung                |
| **Build Tools** | Maven, npm, Composer         | Quản lý dependencies       |
| **IDE**         | IntelliJ IDEA, VS Code       | Phát triển mã nguồn        |

## Cài Đặt Môi Trường

### 1. Backend (Java - Spring Boot)

**Yêu cầu**: JDK 17+, Maven, MySQL.

```bash
git clone https://github.com/giaph4/firstprojectspring.git 
mvn clean install  
java -jar target/backend-1.0.0.jar  
```

### 2. Database (MySQL)

```sql
CREATE DATABASE project_db;  
```

## Liên Hệ

- **GitHub**: [github.com/username](https://github.com/giaph4)
- **Email**: [user@example.com](phohuynh1503@gmail.com)

