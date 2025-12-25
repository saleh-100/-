<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مشروع مقرر تصميم الويب</title>

  <!-- Bootstrap -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

  <!-- CSS -->
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<header class="bg-primary text-white p-3 text-center">
  <h1><i class="fa-solid fa-code"></i> مشروع تصميم الويب</h1>
</header>

<nav class="navbar navbar-expand bg-light">
  <div class="container">
    <a class="nav-link" href="#">الرئيسية</a>
    <a class="nav-link" href="#about">عن المشروع</a>
    <a class="nav-link" href="#form">نموذج</a>
  </div>
</nav>

<section class="container mt-4">
  <h2>مرحبًا بك</h2>
  <p>هذا موقع مشروع جامعي لمقرر تصميم الويب.</p>
  <button id="btn" class="btn btn-success">اضغط هنا</button>
</section>

<section id="about" class="container mt-4">
  <h3>عن المشروع</h3>
  <ul>
    <li>HTML + CSS</li>
    <li>JavaScript</li>
    <li>Bootstrap</li>
    <li>jQuery</li>
  </ul>

  <table class="table table-bordered mt-3">
    <tr>
      <th>العنصر</th>
      <th>الوصف</th>
    </tr>
    <tr>
      <td>اللغة</td>
      <td>HTML</td>
    </tr>
    <tr>
      <td>التنسيق</td>
      <td>CSS</td>
    </tr>
  </table>
</section>

<section id="form" class="container mt-4">
  <h3>نموذج تواصل</h3>
  <form>
    <input type="text" class="form-control mb-2" placeholder="الاسم">
    <input type="email" class="form-control mb-2" placeholder="البريد الإلكتروني">
    <textarea class="form-control mb-2" placeholder="رسالتك"></textarea>
    <button class="btn btn-primary">إرسال</button>
  </form>
</section>

<footer class="bg-dark text-white text-center p-3 mt-4">
  © مشروع تصميم الويب
</footer>

<!-- JS -->
<script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
<script src="script.js"></script>
</body>
</html>

