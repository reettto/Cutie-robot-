<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title> استبيان </title>

<style>
body {
  margin: 0;
  font-family: "Segoe UI", sans-serif;
  direction: rtl;
  background: linear-gradient(135deg, #0f172a, #1e3a8a);
  color: #e5e7eb;
}

.container {
  max-width: 800px;
  margin: 70px auto;
  background: rgba(15,23,42,0.9);
  padding: 40px;
  border-radius: 15px;
  border: 1px solid #334155;
}

h1 {
  text-align: center;
  color: #93c5fd;
}

.subtitle {
  text-align: center;
  color: #cbd5e1;
  margin-bottom: 30px;
}

label {
  display: block;
  margin-top: 25px;
  margin-bottom: 10px;
}

.options {
  line-height: 2;
}

textarea {
  width: 100%;
  padding: 12px;
  border-radius: 10px;
  border: 1px solid #475569;
  background: #0f172a;
  color: white;
}

button {
  margin-top: 30px;
  width: 100%;
  padding: 14px;
  border: none;
  border-radius: 10px;
  background: #3b82f6;
  color: white;
  font-size: 15px;
  font-weight: bold;
  cursor: pointer;
}

.footer {
  text-align: center;
  margin-top: 25px;
  font-size: 13px;
  color: #94a3b8;
}
</style>

</head>

<body>

<div class="container">

<h1> تقييم مشروعنا <h1/>

<p class="subtitle">
نقدر رأيكم عن مشروع تخرجنا ، لاتستحين وقيمي بكل أريحية في سبيل إتقاننا التام للمشاريع في المستقبل !🤍
</p>

<form> <label>اكتب اسمك:</label>
<input type="text" placeholder="اسمك هنا" style="
width:100%;
padding:12px;
border-radius:10px;
border:1px solid #475569;
background:#0f172a;
color:white;">

<label>كيف توصفين العرض؟</label>
<div class="options">
<input type="radio" name="q1"> ممتاز<br>
<input type="radio" name="q1"> جيد جداً<br>
<input type="radio" name="q1"> جيد<br>
<input type="radio" name="q1"> يحتاج تطوير
</div>

<label>هل كانت المعلومات واضحة؟</label>
<div class="options">
<input type="radio" name="q2"> نعم<br>
<input type="radio" name="q2"> نوعاً ما<br>
<input type="radio" name="q2"> لا
</div>

<label>هل استفدتِ من العرض؟</label>
<div class="options">
<input type="radio" name="q3"> نعم كثيراً<br>
<input type="radio" name="q3"> قليلاً<br>
<input type="radio" name="q3"> لا
</div>

<label>الملاحظات:</label>
<textarea rows="4"></textarea>

<label>رسالة لطاقم المشروع:</label>
<textarea rows="4"></textarea>

<button type="submit">إرسال</button>

</form>

<div class="footer">
جميع الآراء محل تقدير ، شكرًا لوقتكم 🤍
</div>

</div>

</body>
</html>
