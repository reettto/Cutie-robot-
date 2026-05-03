<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>Robot × Life Survey</title>

<style>
body{
margin:0;
font-family:Segoe UI, sans-serif;
direction:rtl;
background:#061a33;
color:white;
overflow-x:hidden;
}

/* خطوط فضية */
body::before{
content:"";
position:fixed;
inset:0;
background-image:
linear-gradient(rgba(192,192,192,0.07) 1px, transparent 1px),
linear-gradient(90deg, rgba(192,192,192,0.07) 1px, transparent 1px);
background-size:40px 40px;
z-index:0;
}

/* ضوء فضي */
body::after{
content:"";
position:fixed;
width:400px;
height:400px;
background:radial-gradient(circle, rgba(148,163,184,0.2), transparent 70%);
top:-100px;
right:-100px;
z-index:0;
}

.container{
position:relative;
z-index:1;
max-width:800px;
margin:60px auto;
background:rgba(10,20,40,0.95);
padding:40px;
border-radius:18px;
border:1px solid silver;
}

h1{
text-align:center;
color:silver;
}

.subtitle{
text-align:center;
color:#cbd5e1;
margin-bottom:25px;
}

/* روبوت */
.robot{
width:100px;
margin:auto;
}

.head{
width:90px;
height:70px;
border:2px solid silver;
border-radius:12px;
margin:auto;
position:relative;
}

.eye{
width:9px;
height:9px;
background:silver;
border-radius:50%;
position:absolute;
top:28px;
}

.eye.left{ right:22px; }
.eye.right{ left:22px; }

.body{
width:65px;
height:85px;
border:2px solid silver;
border-radius:12px;
margin:8px auto;
}

/* الأسئلة */
.q{
margin-top:18px;
color:#93c5fd;
font-weight:bold;
}

input,textarea{
width:100%;
padding:12px;
margin-top:8px;
border-radius:10px;
border:1px solid silver;
background:#061a33;
color:white;
}

/* زر */
.btn{
text-align:center;
margin-top:30px;
}

.btn a{
display:inline-block;
padding:14px 26px;
background:#1e3a8a;
color:white;
text-decoration:none;
border-radius:12px;
border:1px solid silver;
font-weight:bold;
}

.footer{
text-align:center;
margin-top:25px;
color:#cbd5e1;
font-size:14px;
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
نقدّر مشاركتكن في تقييم المشروع، ونسعد بآرائكن.
</p>

<form>

<div class="q">الاسم:</div>
<input type="text" name="name">

<div class="q">رأيك في المشروع:</div>
<input type="text" name="opinion">

<div class="q">هل استفدتِ من المشروع؟</div>
<input type="text" name="benefit">

<div class="q">الأخطاء أو الملاحظات:</div>
<textarea name="issues"></textarea>

<div class="q">رسالة لفريق المشروع:</div>
<textarea name="team"></textarea>

<div class="q">رسالة لفتيات المشروع:</div>
<textarea name="girls"></textarea>

</form>

<div class="btn">
<a href="https://forms.cloud.microsoft/r/ysMRYwdXts" target="_blank">
الدخول إلى الاستبيان
</a>
</div>

<div class="footer">
شكرًا لكن على وقتكن الثمين.
</div>

</div>

</body>
</html>


