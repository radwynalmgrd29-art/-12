نگاه این کد را دادی به منث<html lang="fa" dir="rtl">

<head>  
<meta charset="utf-8">  
<meta name="viewport" content="width=device-width, initial-scale=1">  
<title>درگاه پرداخت نمایشی</title>  <style>  
body {  
  margin: 0;  
  background: #f3f5f7;  
  font-family: Tahoma;  
  display: flex;  
  justify-content: center;  
  align-items: center;  
  height: 100vh;  
}  
  
.box {  
  width: 350px;  
  background: #ffffff;  
  padding: 25px;  
  border-radius: 15px;  
  box-shadow: 0 10px 30px rgba(0,0,0,0.1);  
}  
  
.title {  
  text-align: center;  
  font-size: 20px;  
  margin-bottom: 5px;  
}  
  
.sub {  
  text-align: center;  
  color: gray;  
  margin-bottom: 20px;  
}  
  
.amount {  
  background: #f8f8f8;  
  padding: 12px;  
  text-align: center;  
  border-radius: 10px;  
  margin-bottom: 20px;  
  font-size: 16px;  
}  
  
label {  
  display: block;  
  margin-bottom: 8px;  
}  
  
input {  
  width: 100%;  
  padding: 12px;  
  border: 1px solid #ccc;  
  border-radius: 10px;  
  font-size: 16px;  
}  
  
button {  
  width: 100%;  
  padding: 12px;  
  margin-top: 15px;  
  border: none;  
  border-radius: 10px;  
  background: #1976d2;  
  color: white;  
  font-size: 16px;  
  cursor: pointer;  
}  
  
.note {  
  font-size: 12px;  
  text-align: center;  
  margin-top: 15px;  
  color: gray;  
}  
</style>  </head>  <body>  <div class="box">  <div class="title">درگاه پرداخت نمایشی</div>  
<div class="sub">پرداخت اینترنتی</div>  <div class="amount">  
مبلغ قابل پرداخت: ۵۰۰٬۰۰۰ تومان  
</div>  <label>شناسه خود را وارد کنید</label>
<input type="text" id="userId" placeholder="مثلاً 12345">

<button onclick="send()">ادامه</button>

<div class="note">  
این صفحه فقط نمایشی است و پرداخت واقعی انجام نمی‌شود  
</div>  </div>  <script>  
function send() {  
  var value = document.getElementById("userId").value;  
  
  if (value === "") {  
    alert("لطفاً شناسه را وارد کنید");  
    return;  
  }  
  
  alert("شناسه ثبت شد: " + value);  
}  
</script>  </body>  
</html>
