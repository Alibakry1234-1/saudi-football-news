<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>أخبار فريقك</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            text-align: center;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 { color: #007BFF; }
        input, select, button {
            padding: 10px;
            margin: 5px;
        }
        .news, .matches {
            text-align: right;
            margin-top: 20px;
        }
        .news-item, .match-item {
            background: #FFF;
            padding: 10px;
            margin: 5px 0;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        .hidden { display: none; }
    </style>
</head>
<body>

    <div class="container">
        <h1>مرحبًا بك في صفحة أخبار فريقك</h1>
        <div id="userInfo" class="hidden">
            <p>مرحبًا <span id="userName"></span>، أنت تشجع فريق <span id="teamName"></span>.</p>
            <button onclick="resetUser()">تغيير الفريق</button>
        </div>

        <div id="userForm">
            <h2>اختر فريقك</h2>
            <input type="text" id="fullName" placeholder="أدخل اسمك الثلاثي">
            <select id="teamSelect">
                <option value="الهلال">الهلال</option>
                <option value="النصر">النصر</option>
                <option value="الاتحاد">الاتحاد</option>
                <option value="الأهلي">الأهلي</option>
                <option value="الشباب">الشباب</option>
            </select>
            <button onclick="saveUser()">حفظ</button>
        </div>

        <div id="content" class="hidden">
            <h2>أخبار فريقك</h2>
            <div id="news" class="news"></div>

            <h2>المباريات القادمة</h2>
            <div id="matches" class="matches"></div>
        </div>
    </div>

    <script>
        function saveUser() {
            let name = document.getElementById("fullName").value.trim();
            let team = document.getElementById("teamSelect").value;
            
            if (!name.includes(" ") || name.split(" ").length < 3) {
                alert("يرجى إدخال الاسم الثلاثي.");
                return;
            }

            localStorage.setItem("userName", name);
            localStorage.setItem("teamName", team);
            showContent();
        }

        function resetUser() {
            localStorage.removeItem("userName");
            localStorage.removeItem("teamName");
            location.reload();
        }

        function showContent() {
            let userName = localStorage.getItem("userName");
            let teamName = localStorage.getItem("teamName");

            if (userName && teamName) {
                document.getElementById("userForm").classList.add("hidden");
                document.getElementById("userInfo").classList.remove("hidden");
                document.getElementById("content").classList.remove("hidden");
                document.getElementById("userName").textContent = userName;
                document.getElementById("teamName").textContent = teamName;

                fetchNews(teamName);
                fetchMatches(teamName);
            }
        }

        function fetchNews(team) {
            let url = `https://www.google.com/search?q=أخبار+${team}+السعودي&hl=ar`;
            document.getElementById("news").innerHTML = `<p>جلب الأخبار من: <a href="${url}" target="_blank">Google</a></p>`;
        }

        function fetchMatches(team) {
            let url = `https://www.google.com/search?q=مباريات+${team}+القادمة&hl=ar`;
            document.getElementById("matches").innerHTML = `<p>جدول المباريات من: <a href="${url}" target="_blank">Google</a></p>`;
        }

        showContent();
    </script>

</body>
</html>
