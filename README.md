function greetUser(name) {
    let message = "مرحباً بك يا " + name + " في عالم البرمجة!";
    console.log(message);
    return message;
}

// تشغيل الدالة
greetUser("أحمد");
<!DOCTYPE html>
<html>
<head>
    <style>
        .my-button {
            background-color: #4CAF50; /* لون أخضر */
            color: white;
            padding: 15px 32px;
            text-align: center;
            font-size: 16px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: 0.3s;
        }
        .my-button:hover {
            background-color: #45a049; /* تغيير اللون عند مرور الماوس */
        }
    </style>
</head>
<body>

    <button class="my-button">اضغط هنا</button>

</body>
</html>
const http = require('http');

const server = http.createServer((req, res) => {
    res.statusCode = 200;
    res.setHeader('Content-Type', 'text/plain; charset=utf-8');
    res.end('تم تشغيل السيرفر بنجاح وأهلاً بك!');
});

// تشغيل السيرفر على المنفذ 3000
server.listen(3000, () => {
    console.log('السيرفر يعمل الآن على http://localhost:3000');
});
