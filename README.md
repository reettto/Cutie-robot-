# Hello  🤖👋

html <!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>استبيان مشروعنا </title>

<style>
body {
  margin: 0;
  font-family: "Segoe UI", sans-serif;
  direction: rtl;
  background: #0b1120;
  color: #e2e8f0;
}

/* خلفية شبكة تقنية */
.background {
  position: fixed;
  width: 100%;
  height: 100%;
  z-index: -1;
  background-image:
    linear-gradient(rgba(59,130,246,0.08) 1px, transparent 1px),
    linear-gradient(90deg, rgba(148,163,184,0.08) 1px, transparent 1px);
  background-size: 60px 60px;
}

.container {
  max-width: 850px;
  margin: 80px auto;
  background: rgba(15,23,42,0.9);
  padding: 45px;
  border-radius: 18px;
  border: 1px solid #334155;
  box-shadow: 0 20px 60px rgba(0,0,0,0.5);
}

h1 {
  text-align: center;
  color: #93c5fd;
  margin-bottom: 15px;
  letter-spacing: 1px;
}

.subtitle {
  text-align: center;
  color: #cbd5e1;
  margin-bottom: 40px;
  font-size: 14px;
}

label {
  display: block;
  margin-top: 30px;
  margin-bottom: 12px;
  font-weight: 600;
}

.options {
  line-height: 2;
  color: #f1f5f9;
}

textarea {
  width: 100%;
  padding: 14px;
  border-radius: 10px;
  border: 1px solid #475569;
  background-color: #0b1120;
  color: #f8fafc;
  font-family: inherit;
}

button {
  margin-top: 40px;
  width: 100%;
  padding: 16px;
  border: none;
  border-radius: 10px;
  background: linear-gradient(90deg, #3b82f6, #94a3b8);
  color: #0b1120;
  font-size: 15px;
  font-weight: bold;
  cursor: pointer;
}

button:hover {
  opacity: 0.9;
}

.footer {
  text-align: center;
  margin-top: 35px;
  font-size: 13px;
  color: #94a3b8;
}
</style>
</head>

<body>

<div class="background"></div>

<div class="container">

<h1>تقييم عرض المشروع</h1>

<p class="subtitle">
نقدر مشاركتكم في تقييم عرض مشروعنا، آراؤكم تساعدنا في التطوير والتحسين 🤍.
</p>

<form> <label>اكتبِ اسمك:</label>
<input type="text" placeholder="اسمك هنا" style="
width:100%;
padding:12px;
border-radius:10px;
border:1px solid #475569;
background:#0f172a;
color:white;
">

<label>كيف تقيمين العرض بشكل عام؟</label>
<div class="options">
<input type="radio" name="overall"> ممتاز<br>
<input type="radio" name="overall"> جيد جداً<br>
<input type="radio" name="overall"> جيد<br>
<input type="radio" name="overall"> يحتاج تطوير
</div>

<label>هل كانت المعلومات واضحة وسهلة الفهم؟</label>
<div class="options">
<input type="radio" name="clarity"> واضحة جداً<br>
<input type="radio" name="clarity"> نوعاً ما<br>
<input type="radio" name="clarity"> غير واضحة
</div>

<label>هل استفدتِ من العرض؟</label>
<div class="options">
<input type="radio" name="benefit"> استفدت كثيراً<br>
<input type="radio" name="benefit"> استفدت قليلاً<br>
<input type="radio" name="benefit"> لم أستفد
</div>

<label>في حال وجود ملاحظات أو نقاط تحتاج تحسين:</label>
<textarea rows="4"></textarea>

<label>رسالة إلى طاقم المشروع:</label>
<textarea rows="4"></textarea> 

<button type="submit">إرسال التقييم</button>

</form>

<div class="footer">
جميع الآراء محل تقدير .. شكرا لوقتكم 🤍
</div>

</div>

</body>
</html>
