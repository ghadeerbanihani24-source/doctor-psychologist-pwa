# doctor-psychologist-pwa
تطبيق الدكتور النفسي - PWA
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>الدكتور النفسي</title>
  <meta name="description" content="طبيبك النفسي الخاص - دعم نفسي آمن وسري">
  <link rel="manifest" href="manifest.json">
  <meta name="theme-color" content="#1e3a8a">
</head>
<body style="margin:0;padding:0;height:100vh;overflow:hidden;background:#f8fafc;">

  <div style="position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);color:#1e3a8a;font-size:20px;font-weight:bold;z-index:10;">
    جاري تحميل الدكتور النفسي...
  </div>

  <!-- ⚠️ غير هذا الرابط لاحقاً بعد رفع Streamlit -->
  <iframe src="https://your-streamlit-link.streamlit.app" 
          style="width:100%; height:100%; border:none;" 
          allowfullscreen></iframe>

  <script>
    if ('serviceWorker' in navigator) {
      navigator.serviceWorker.register('sw.js');
    }
  </script>
</body>
</html>
