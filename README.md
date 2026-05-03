<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Robot Life - تقييم المشروع</title>

<style>
body{
margin:0;
font-family:"Segoe UI",sans-serif;
direction:rtl;
background:#0b1f3a;
color:white;
overflow-x:hidden;
}

/* شبكة فضية تقنية */
body::before{
content:"";
position:fixed;
width:100%;
height:100%;
background-image:
linear-gradient(rgba(192,192,192,0.07) 1px, transparent 1px),
linear-gradient(90deg, rgba(192,192,192,0.07) 1px, transparent 1px);
background-size:45px 45px;
z-index:0;
}

/* دائرة إضاءة خفيفة */
body::after{
content:"";
position:fixed;
width:500px;
height:500px;
background:radial-gradient(circle, rgba(30,64,175,0.4), transparent 70%);
top:-100px;
left:-100px;
z-index:0;
}

.container{
position:relative;
z-index:1;
max-width:750px;
margin:60px auto;
background:rgba(10,20,40,0.9);
padding:40px;
border-radius:20px;
border:1px solid silver;
box-shadow:0 0 25px rgba(192,192,192,0.25);
}

h1{
text-align:center;
color:silver;
letter-spacing:1px;
margin-bottom:10px;
}

.subtitle{
text-align:center;
color:#cbd5e1;
margin-bottom:35px;
line-height:1.8;
}

/* روبوت مرسوم بخطوط */
.robot{
width:120px;
margin:0 auto 25px auto;
position:relative;
}

.robot-head{
width:100px;
height:80px;
border:2px solid silver;
border-radius:15px;
margin:0 auto;
position:relative;
}

.eye{
width:12px;
height:12px;
background:silver;
border-radius:50%;
position:absolute;
top:30px;
}

.eye.left{ right:25px; }
.eye.right{ left:25px; }

.robot-body{
width:70px;
height:90px;
border:2px solid silver;
border-radius:15px;
margin:10px auto;
}

.question{
margin-top:25px;
font-weight:bold;
color:#93c5fd;
}

.options{
margin-top:10px;
line-height:2;
color:#e2e8f0;
}

input[type="text"], textarea{
width:100%;
padding:12px;
margin-top:10px;
border-radius:10px;
border:1px solid silver;
background:#0b1f3a;
color:white;
}

button{
margin-top:30px;
width:100%;
padding:14px;
border:none;
border-radius:10px;
background:linear-gradient(90deg,#1e40af,#2563eb);
color:white;
font-weight:bold;
cursor:pointer;
transition:0.3s;
}

button:hover{
box-shadow:0 0 15px silver;
}

.footer{
text-align:center;
margin-top:30px;
font-size:14px;
color:#cbd5e1;
line-height:1.8;
}
</style>
</head>

<body>

<div class="container">

<div class="robot">
<div class="robot-head">
<div class="eye left"></div>
<div class="eye right"></div>
</div>
<div class="robot-body"></div>
</div>

<h1>Robot × Life</h1>

<p class="subtitle">
نعتز بآرائكم حول مشروعنا،
فملاحظاتكم تسهم في تطوير الفكرة وتعزيز الجانب التقني والإنساني معًا.
</p>

<form>

<div class="question">الاسم الكريم:</div>
<input type="text" placeholder="يرجى كتابة الاسم هنا">

<div class="question">ما مدى تميز فكرة المشروع؟</div>
<div class="options">
<label><input type="radio" name="q1"> متميزة ومبتكرة</label><br>
<label><input type="radio" name="q1"> جيدة وواضحة</label><br>
<label><input type="radio" name="q1"> تحتاج تطوير</label>
</div>

<div class="question">مدى وضوح الربط بين التقنية والحياة؟</div>
<div class="options">
<label><input type="radio" name="q2"> واضح باحترافية</label><br>
<label><input type="radio" name="q2"> جيد إلى حد ما</label><br>
<label><input type="radio" name="q2"> يحتاج توضيح أكثر</label>
</div>

<div class="question">تقييمكم العام للمشروع:</div>
<div class="options">
<label><input type="radio" name="q3"> ممتاز</label><br>
<label><input type="radio" name="q3"> جيد جدًا</label><br>
<label><input type="radio" name="q3"> جيد</label>
</div>

<div class="question">ملاحظات أو مقترحات تطوير:</div>
<textarea rows="4"></textarea>

<div class="question">رسالة تودون توجيهها لفريق المشروع:</div>
<textarea rows="4"></textarea>

<button type="submit">إرسال التقييم</button>

</form>

<div class="footer">
شكرًا لوقتكم الثمين ودعمكم المستمر.
</div>

</div>

</body>
</html>
