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
background: linear-gradient(135deg,#cfe9ff,#e6f2ff);
}

.container{
max-width:800px;
margin:60px auto;
background:#f8fbff;
padding:40px;
border-radius:20px;
box-shadow:0 10px 30px rgba(0,0,0,0.1);
border:1px solid #dbeafe;
}

h1{
text-align:center;
color:#1e3a8a;
margin-bottom:10px;
}

.subtitle{
text-align:center;
color:#475569;
margin-bottom:30px;
line-height:1.8;
}

label{
display:block;
margin-top:25px;
margin-bottom:10px;
color:#1e3a8a;
font-weight:600;
}

.options{
line-height:2;
color:#334155;
}

textarea, input[type="text"]{
width:100%;
padding:12px;
border-radius:12px;
border:1px solid #cbd5e1;
background:#ffffff;
font-family:"Segoe UI", sans-serif;
}

button{
margin-top:30px;
width:100%;
padding:14px;
border:none;
border-radius:12px;
background:linear-gradient(90deg,#60a5fa,#93c5fd);
color:white;
font-size:15px;
font-weight:bold;
cursor:pointer;
}

.footer{
text-align:center;
margin-top:25px;
font-size:14px;
color:#64748b;
line-height:1.8;
}
</style>
</head>

<body>

<div class="container">

<h1>استبيان تقييم مشروعنا</h1>

<p class="subtitle">
يسعدنا ويشرفنا تقييمكم الكريم لمشروعنا،  
فرأيكم محل تقدير ويساهم في تطويرنا وتحسين أعمالنا القادمة.
</p>

<form>

<label>الاسم الكريم:</label>
<input type="text" placeholder="تفضلي بكتابة اسمك هنا">

<label>كيف تقيمين مستوى العرض بشكل عام؟</label>
<div class="options">
<input type="radio" name="q1"> ممتاز<br>
<input type="radio" name="q1"> جيد جداً<br>
<input type="radio" name="q1"> جيد<br>
<input type="radio" name="q1"> يحتاج إلى تطوير
</div>

<label>ما رأيك بمحتوى المشروع وفكرته؟</label>
<div class="options">
<input type="radio" name="q2"> متميزة وواضحة<br>
<input type="radio" name="q2"> جيدة ومفهومة<br>
<input type="radio" name="q2"> تحتاج إلى مزيد من الإيضاح
</div>

<label>إلى أي مدى ترين أن المشروع كان منظمًا ومترابطًا؟</label>
<div class="options">
<input type="radio" name="q3"> منظم جدًا<br>
<input type="radio" name="q3"> منظم إلى حد ما<br>
<input type="radio" name="q3"> يحتاج تنظيم أكثر
</div>

<label>في حال وجود ملاحظات تطوير، تفضلي بذكرها:</label>
<textarea rows="4"></textarea>

<label>رسالة توجهينها لطاقم المشروع:</label>
<textarea rows="4"></textarea>

<button type="submit">إرسال التقييم</button>

</form>

<div class="footer">
نشكر لك وقتك الثمين واهتمامك الكريم،  
ونسعد دائمًا بتوجيهاتك وملاحظاتك القيّمة.
</div>

</div>

</body>
</html>
