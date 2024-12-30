- 👋 Hi, I’m @Ryan433-web
- 👀 I’m interested in .../* style.css */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

section {
    padding: 20px;
    margin: 10px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #333;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form {
    display: grid;
    gap: 10px;
}

form input, form textarea {
    padding: 10px;
    width: 100%;
    border-radius: 5px;
    border: 1px solid #ccc;
}

form button {
    padding: 10px;
    background-color: #333;
    color: white;
    border: none;
    border-radius: 5px;
}
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Ryan433-web/Ryan433-web is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
متاسفانه در حال حاضر قادر به ساخت وب‌سایت به صورت مستقیم و در دسترس قرار دادن لینک آن نیستم، اما می‌توانم به شما کمک کنم تا کدهای HTML و CSS برای طراحی یک وب‌سایت ساده برای رایان آماده کنید. در ادامه، یک طرح اولیه برای وب‌سایت رایان به عنوان بازیگر، خواننده، مدل و رپر ارائه می‌کنم:

1. ساختار HTML:

<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رایان - بازیگر، خواننده، مدل، رپر</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>رایان</h1>
            <p>بازیگر | خواننده | مدل | رپر</p>
        </div>
        <nav>
            <ul>
                <li><a href="#bio">بیوگرافی</a></li>
                <li><a href="#music">آلبوم موسیقی</a></li>
                <li><a href="#acting">پروژه‌های بازیگری</a></li>
                <li><a href="#contact">تماس</a></li>
            </ul>
        </nav>
    </header>

    <section id="bio">
        <h2>بیوگرافی</h2>
        <p>رایان یک نوجوان ۱۲ ساله با استعداد در زمینه‌های بازیگری، خوانندگی، مدلینگ و رپ است. او تاکنون در پروژه‌های مختلف هنری فعالیت داشته و اجراهای زیادی در مقابل تماشاگران داشته است.</p>
    </section>

    <section id="music">
        <h2>آلبوم موسیقی</h2>
        <p>در اینجا می‌توانید به آهنگ‌ها و رپ‌های رایان گوش دهید.</p>
        <ul>
            <li><a href="#">آهنگ ۱</a></li>
            <li><a href="#">آهنگ ۲</a></li>
            <li><a href="#">آهنگ ۳</a></li>
        </ul>
    </section>

    <section id="acting">
        <h2>پروژه‌های بازیگری</h2>
        <p>رایان در پروژه‌های مختلف بازیگری مانند فیلم‌ها و سریال‌ها حضور داشته است.</p>
        <ul>
            <li>فیلم ۱</li>
            <li>فیلم ۲</li>
            <li>فیلم ۳</li>
        </ul>
    </section>

    <section id="contact">
        <h2>تماس با رایان</h2>
        <p>برای همکاری یا مشاوره، لطفاً از طریق فرم زیر با رایان تماس بگیرید:</p>
        <form action="#" method="post">
            <label for="name">نام:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">ایمیل:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">پیام:</label>
            <textarea id="message" name="message" rows="4" required></textarea>
            <button type="submit">ارسال</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 رایان</p>
    </footer>
</body>
</html>

2. استایل (CSS):

/* style.css */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

section {
    padding: 20px;
    margin: 10px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h2 {
    color: #333;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

form {
    display: grid;
    gap: 10px;
}

form input, form textarea {
    padding: 10px;
    width: 100%;
    border-radius: 5px;
    border: 1px solid #ccc;
}

form button {
    padding: 10px;
    background-color: #333;
    color: white;
    border: none;
    border-radius: 5px;
}

3. نحوه استفاده:

1. ایجاد فایل‌ها:

یک پوشه جدید بسازید و دو فایل به نام‌های index.html و style.css ایجاد کنید.

کدهای HTML را در فایل index.html و کدهای CSS را در فایل style.css قرار دهید.



2. انتشار سایت:

شما می‌توانید این کدها را در یک سرویس میزبانی وب (مثل GitHub Pages، Netlify یا هر سرویس دیگری) آپلود کنید تا وبسایت خود را آنلاین کنید.




اگر به کمک بیشتری نیاز دارید یا می‌خواهید ویژگی‌های بیشتری به سایت اضافه کنید، خوشحال می‌شوم که راهنمایی کنم.

