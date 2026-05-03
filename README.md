<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<title>استبيان طموحات وظيفية</title>

<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    direction: rtl;
    background: linear-gradient(135deg, #0f172a, #1e293b);
    color: white;
  }

  .container {
    max-width: 700px;
    margin: 60px auto;
    background: rgba(255,255,255,0.08);
    padding: 30px;
    border-radius: 20px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.3);
    backdrop-filter: blur(10px);
  }

  h1 {
    text-align: center;
    color: #22c55e;
  }

  .subtitle {
    text-align: center;
    margin-bottom: 20px;
    color: #cbd5e1;
  }

  label {
    display: block;
    margin-top: 15px;
    margin-bottom: 5px;
  }

  input, textarea {
    width: 100%;
    padding: 10px;
    border-radius: 10px;
    border: none;
    outline: none;
  }

  .options {
    margin-top: 10px;
  }

  button {
    margin-top: 20px;
    width: 100%;
    padding: 12px;
    border: none;
    border-radius: 10px;
    background: #22c55e;
    color: white;
    font-size: 16px;
    cursor: pointer;
  }

  button:hover {
    background: #16a34a;
  }

  .footer {
    text-align: center;
    margin-top: 20px;
    font-size: 12px;
    color: #94a3b8;
  }
</style>

</head>

<body>

<div class="container">

  <h1>استبيان الطموحات الوظيفية</h1>

  <p class="subtitle">
    ضمن رؤية المملكة 2030، نهدف لفهم طموحات الشباب المهنية وتوجهاتهم المستقبلية 🤍
  </p>

  <form> <label>اكتب اسمك:</label>
<input type="text" placeholder="اسمك هنا" style="
width:100%;
padding:12px;
border-radius:10px;
border:1px solid #475569;
background:#0f172a;
color:white;">

    <label>ما هو المجال الذي تطمحين له مستقبلاً؟</label>
    <input type="text" placeholder="مثال: طب، تقنية، تصميم...">

    <label>هل تفضلين العمل الحكومي أو الخاص؟</label>
    <div class="options">
      <input type="radio" name="job"> حكومي<br>
      <input type="radio" name="job"> خاص<br>
      <input type="radio" name="job"> لا أعلم
    </div>

    <label>ما أهم شيء تبحثين عنه في الوظيفة؟</label>
    <textarea rows="4" placeholder="راتب، راحة، تطوير، شغف..."></textarea>

    <button type="submit">إرسال</button>

  </form>

  <div class="footer">
    مشروع طلابي مرتبط برؤية 2030 - شكراً لمشاركتك ✨
  </div>

</div>

</body>
</html>
