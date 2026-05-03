<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>Robot Project Survey</title>

<style>
body{
margin:0;
font-family:"Segoe UI",sans-serif;
direction:rtl;
background:#071a33;
color:white;
overflow-x:hidden;
}

/* خطوط فضية عشوائية */
body::before{
content:"";
position:fixed;
width:100%;
height:100%;
background-image:
linear-gradient(rgba(192,192,192,0.06) 1px, transparent 1px),
linear-gradient(90deg, rgba(192,192,192,0.06) 1px, transparent 1px);
background-size:35px 35px;
z-index:0;
}

/* إضاءة فضية */
body::after{
content:"";
position:fixed;
width:500px;
height:500px;
background:radial-gradient(circle, rgba(148,163,184,0.25), transparent 70%);
top:-120px;
right:-120px;
z-index:0;
}

.container{
position:relative;
z-index:1;
max-width:800px;
margin:60px auto;
background:rgba(10,20,40,0.92);
padding:40px;
border-radius:20px;
border:1px solid silver;
box-shadow:0 0 30px rgba(192,192,192,0.2);
}

/* روبوت */
.robot{
width:120px;
margin:0 auto 20px auto;
}

.head{
width:100px;
height:80px;
border:2px solid silver;
border-radius:15px;
margin:auto;
position:relative;
}

.eye{
width:10px;
height:10px;
background:silver;
border-radius:50%;
position:absolute;
top:30px;
}

.eye.left{ right:25px; }
.eye.right{ left:25px; }

.body{
width:70px;
height:90px;
border:2px solid silver;
border-radius:15px;
margin:10px auto;
}

h1{
text-align:center;
color:silver;
}

.subtitle{
text-align:center;
color:#cbd5e1;
margin-bottom:30px;
}

.q{
margin-top:20px;
color:#93c5fd;
font-weight:bold;
}

textarea,input{
width:100%;
padding:12px;
margin-top:8px;
border-radius:10px;
border:1px solid silver;
background:#071a33;
color:white;
}

.btn{
text-align:center;
margin-top:30px;
}

.btn a{
display:inline-block;
padding:14px 25px;
background:#1e3a8a;
color:white;
text-decoration:none;
border-radius:12px;
border:1px solid silver;
font-weight:bold;
}

.footer{
text-align:center;
margin-top:30px;
color:#cbd5e1;
line-height:1.8;
}
</style>
</head>

<body>

<div class="container">

<div class="robot">
<div class="head">
<div class="eye left"></div>
<div class="eye right"></div>
</div>
<div class="body"></div>
</div>

<h1>Robot × Life</h1>

<p class="subtitle">
نقدّر مشاركتكم لنا في هذا التقييم،
ونرحب بآرائكم التي تساعدنا في تطوير المشروع.
</p>

<form>

<div class="q">الاسم:</div>
<input type="text" name="name">

<div class="q">رأيك في المشروع:</div>
<input type="text" name="rating">

<div class="q">هل استفدت من المشروع؟</div>
<input type="text" name="benefit">

<div class="q">الأخطاء أو الملاحظات التي لاحظتها:</div>
<textarea name="issues" rows="3"></textarea>

<div class="q">رسالة لفريق المشروع:</div>
<textarea name="teammsg" rows="3"></textarea>

<div class="q">رسالة لفتيات المشروع:</div>
<textarea name="girlsmsg" rows="3"></textarea>

</form>

<div class="btn">
<a href="https://forms.cloud.microsoft/r/ysMRYwdXts" target="_blank">
فتح الاستبيان وإرسال الإجابات
</a>
</div>

<div class="footer">
شكرًا لوقتك الثمين ودعمك المستمر.
</div>

</div>

</body>
</html>
