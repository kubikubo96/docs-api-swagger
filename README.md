# Sử dụng Swagger 3.0
###Tài khoản đăng nhập:
**`username: colearn, password: 123`**

**Các bước sử dụng:**
1. copy file từ example.json. ví dụ rate.json
2. xem cấu trúc của file json example.json và viết theo
3. sửa url để đổi docs api ở trang chủ hoặc trong file index.php.

![alt text](./assets/change_json_file.png)

```
window.onload = () => {
        window.ui = SwaggerUIBundle({
            url: 'data/example.json?t='+Math.random(),
            ...
        });
    };
```
4. Viết docs mới thì nhớ note lại ở README mục 4.

#Các tài liệu API đã viết.
- example.json => các ví dụ về viết api trong swagger
- rate.json => tất cả các api về rate