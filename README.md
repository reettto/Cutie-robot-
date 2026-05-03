<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>استبيان تقييم المشروع</title>

<style>
body{
margin:0;
font-family:"Segoe UI", sans-serif;
direction:rtl;
background: linear-gradient(135deg,#dbeafe,#eaf4ff);
}

.container{
max-width:750px;
margin:70px auto;
background:#ffffff;
padding:40px;
border-radius:18px;
box-shadow:0 12px 30px rgba(0,0,0,0.08);
border:1px solid #cbd5e1;
}

h1{
text-align:center;
color:#1e3a8a;
margin-bottom:15px;
}

.intro{
text-align:center;
color:#475569;
margin-bottom:35px;
line-height:1.8;
}

.question{
margin-top:25px;
margin-bottom:10px;
color:#1e3a8a;
font-weight:600;
}

.options{
margin-bottom:20px;
line-height:2;
color:#334155;
}

textarea, input[type="text"]{
width:100%;
padding:12px;
border-radius:10px;
border:1px solid #cbd5e1;
margin-top:8px;
font-family:"Segoe UI", sans-serif;
}

button{
margin-top:30px;
width:100%;
padding:14px;
border:none;
border-radius:10px;
background:linear-gradient(90deg,#93c5fd,#60a5fa);
color:white;
font-size:15px;
font-weight:bold;
cursor:pointer;
}

.footer{
text-align:center;
margin-top:30px;
font-size:14px;
color:#64748b;
line-height:1.8;
}
</style>
</head>

<body>

<div class="container">

<h1>استبيان تقييم المشروع</h1>

<p class="intro">
يسرّنا تقييمكم الكريم لمشروعنا،
ونسعد بملاحظاتكم التي تسهم في تطوير أعمالنا المستقبلية.
</p>

<form>

<div class="question">الاسم الكريم:</div>
<input type="text" placeholder="يرجى كتابة الاسم هنا">

<div class="question">كيف تقيمين مستوى العرض بشكل عام؟</div>
<div class="options">
<label><input type="radio" name="q1"> ممتاز</label><br>
<label><input type="radio" name="q1"> جيد جدًا</label><br>
<label><input type="radio" name="q1"> جيد</label><br>
<label><input type="radio" name="q1"> يحتاج إلى تطوير</label>
</div>

<div class="question">ما رأيك بمحتوى المشروع وفكرته؟</div>
<div class="options">
<label><input type="radio" name="q2"> واضحة ومتميزة</label><br>
<label><input type="radio" name="q2"> جيدة ومفهومة</label><br>
<label><input type="radio" name="q2"> تحتاج إلى مزيد من الإيضاح</label>
</div>

<div class="question">إلى أي مدى كان المشروع منظمًا ومترابطًا؟</div>
<div class="options">
<label><input type="radio" name="q3"> منظم جدًا</label><br>
<label><input type="radio" name="q3"> منظم إلى حد ما</label><br>
<label><input type="radio" name="q3"> يحتاج تنظيم أكثر</label>
</div>

<div class="question">ملاحظات أو اقتراحات تطوير:</div>
<textarea rows="4"></textarea>

<div class="question">رسالة تودين توجيهها لفريق المشروع:</div>
<textarea rows="4"></textarea>

<button type="submit">إرسال التقييم</button>

</form>

<div class="footer">
نشكر لكم وقتكم الثمين واهتمامكم الكريم،
ونسعد دائمًا بتوجيهاتكم القيّمة.
</div>

</div>

</body>
</html>
