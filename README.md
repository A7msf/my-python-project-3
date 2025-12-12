<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل الدخول للموظفين</title>

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;600&display=swap');

        body {
            margin: 0;
            font-family: 'Cairo', sans-serif;
            background: #bfbfbf;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
            overflow: hidden;
        }

        /* الخلفية الدائرية */
        .circle {
            position: absolute;
            border: 3px solid #dcdcdc;
            border-radius: 50%;
            opacity: 0.5;
        }

        /* توزيع الدوائر */
        .c1 { width: 150px; height: 150px; top: 20px; right: 20px; }
        .c2 { width: 90px; height: 90px; top: 200px; right: 50px; }
        .c3 { width: 300px; height: 300px; top: -70px; left: 150px; }
        .c4 { width: 120px; height: 120px; bottom: 40px; left: 80px; }
        .c5 { width: 90px; height: 90px; bottom: 120px; right: 200px; }

        .container {
            width: 430px;
            background: white;
            padding: 40px 35px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 0 15px rgba(0,0,0,0.1);
            position: relative;
            z-index: 10;
        }

        h2 {
            margin-top: 0;
            font-size: 26px;
            font-weight: 700;
        }

        .subtitle {
            color: gray;
            margin-bottom: 25px;
            font-size: 15px;
        }

        .input-group {
            text-align: right;
            margin-bottom: 18px;
        }

        .input-group label {
            display: block;
            font-weight: 600;
            margin-bottom: 6px;
        }

        input {
            width: 100%;
            padding: 13px;
            border-radius: 8px;
            border: 1px solid #ddd;
            font-size: 15px;
        }

        .forgot {
            text-align: right;
            font-size: 13px;
            margin-top: -8px;
            margin-bottom: 10px;
            color: red;
            cursor: pointer;
        }

        .remember {
            text-align: right;
            margin-bottom: 25px;
        }

        button {
            width: 100%;
            background: #263238;
            padding: 14px;
            border: none;
            border-radius: 10px;
            font-size: 17px;
            color: white;
            cursor: pointer;
        }

        .support-box {
            margin-top: 25px;
            font-size: 14px;
            color: #666;
        }

        .support {
            margin-top: 10px;
            font-size: 15px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <!-- دوائر الخلفية -->
    <div class="circle c1"></div>
    <div class="circle c2"></div>
    <div class="circle c3"></div>
    <div class="circle c4"></div>
    <div class="circle c5"></div>

    <div class="container">

        <h2>تسجيل الدخول للموظفين</h2>
        <div class="subtitle">اهلا بك مجددًا في المنظومة القومية لبنوك الدم</div>

        <div class="input-group">
            <label>الرقم القومي (اسم المستخدم)</label>
            <input type="text" placeholder="قم بكتابة رقمك القومي المكون من 14 رقم">
        </div>

        <div class="forgot">نسيت كلمة المرور؟</div>

        <div class="input-group">
            <label>كلمة المرور</label>
            <input type="password" placeholder="***************">
        </div>

        <div class="remember">
            <input type="checkbox"> تذكرني على هذا الجهاز
        </div>

        <button>تسجيل الدخول</button>

        <div class="support-box">
            ــــــــــــــــ  مشكلة تقنية ؟  ــــــــــــــــ
            <div class="support">تواصل مع الدعم الفني 🎧</div>
        </div>

    </div>

</body>
</html>
