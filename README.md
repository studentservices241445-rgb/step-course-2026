<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="التسجيل — دورة STEP المكثفة 2026" />
  <meta name="theme-color" content="#f4c400" />
  <title>دورة STEP المكثفة 2026</title>

  <!-- خط عربي -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;800;900&display=swap" rel="stylesheet">

  <!-- favicon will be injected by JS -->
  <link id="favicon" rel="icon" href="">

  <style>
    :root{
      --bg1:#fff2b3;
      --bg2:#ffffff;
      --card:#ffffff;
      --ink:#0b0b0b;
      --muted:#5a5a5a;
      --accent:#f4c400;
      --accent2:#ffd85b;
      --dark:#111;
      --ok:#0a7a2f;
      --warn:#b75a00;
      --danger:#b00020;
      --line:rgba(0,0,0,.12);
      --shadow:0 18px 36px rgba(0,0,0,.12);
      --radius:18px;
    }
    *{box-sizing:border-box}
    html{scroll-behavior:smooth}
    body{
      margin:0;
      font-family:"Tajawal", system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color:var(--ink);
      background:
        radial-gradient(900px 360px at 10% -10%, rgba(244,196,0,.55), transparent 60%),
        radial-gradient(900px 360px at 90% -10%, rgba(17,17,17,.10), transparent 60%),
        linear-gradient(180deg, var(--bg1), var(--bg2) 42%, #fff 100%);
      overflow-x:hidden;
      position:relative;
    }
    /* علامة مائية */
    body::before{
      content: attr(data-watermark);
      position:fixed; inset:0;
      display:grid; place-items:center;
      pointer-events:none;
      opacity:.06;
      font-weight:900;
      font-size:52px;
      transform:rotate(-12deg);
      z-index:0;
      text-align:center;
      letter-spacing:.5px;
      mix-blend-mode:multiply;
    }

    a{color:inherit}
    .wrap{max-width:1120px;margin:0 auto;padding:18px;position:relative;z-index:1}

    /* شريط علوي */
    .urgency{
      position:sticky; top:0;
      z-index:90;
      background: linear-gradient(90deg, var(--dark), #2a2a2a);
      color:#fff;
      border-bottom:1px solid rgba(255,255,255,.12);
    }
    .urgency .in{
      max-width:1120px;margin:0 auto;
      padding:10px 16px;
      display:flex;align-items:center;justify-content:space-between;gap:12px;
    }
    .urgency b{color:var(--accent)}
    .urgency .uBtn{
      background: linear-gradient(180deg, var(--accent), var(--accent2));
      border:0;
      padding:10px 12px;
      border-radius:999px;
      font-weight:900;
      cursor:pointer;
      white-space:nowrap;
    }
    .mini{font-size:12.8px;color:var(--muted);line-height:1.7}
    .miniW{font-size:13px;opacity:.92;line-height:1.7}

    header{
      position:sticky; top:52px; z-index:80;
      backdrop-filter: blur(10px);
      background: rgba(255,255,255,.80);
      border-bottom:1px solid var(--line);
    }
    .topbar{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:14px 18px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:46px;height:46px;border-radius:14px;
      background: radial-gradient(circle at 30% 30%, #fff, #ffe27a 55%, var(--accent) 100%);
      border:1px solid rgba(0,0,0,.12);
      box-shadow: var(--shadow);
      display:grid;place-items:center;
      overflow:hidden;
    }
    .brand h1{font-size:16px;margin:0}
    .brand p{margin:0;font-size:12px;color:var(--muted)}
    nav{display:flex;gap:10px;flex-wrap:wrap;justify-content:flex-end}
    .pill{
      border:1px solid var(--line);
      background:#fff;
      padding:8px 10px;border-radius:999px;
      font-size:13px;text-decoration:none;font-weight:900;
    }
    .pill:hover{border-color:rgba(0,0,0,.25)}
    @media (max-width: 980px){ nav{display:none} }

    .grid{display:grid;grid-template-columns:1.25fr .75fr;gap:16px}
    @media (max-width: 980px){ .grid{grid-template-columns:1fr} }

    .card{
      background:var(--card);
      border:1px solid var(--line);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      padding:16px;
      position:relative;
      overflow:hidden;
    }
    .card::after{
      content:"";
      position:absolute; inset:auto -80px -80px auto;
      width:240px;height:240px;
      background: radial-gradient(circle, rgba(244,196,0,.28), transparent 60%);
      transform:rotate(12deg);
      pointer-events:none;
    }
    .title{display:flex;align-items:center;justify-content:space-between;gap:10px}
    .title h2{margin:0;font-size:18px}
    .badge{
      display:inline-flex;align-items:center;gap:6px;
      background: rgba(244,196,0,.20);
      border:1px solid rgba(244,196,0,.60);
      padding:6px 10px;border-radius:999px;
      font-size:12px;font-weight:900;
      white-space:nowrap;
    }
    .line{height:1px;background:var(--line);margin:14px 0}

    .kpis{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:12px}
    @media (max-width: 620px){ .kpis{grid-template-columns:1fr} }
    .kpi{border:1px dashed rgba(0,0,0,.18);border-radius:14px;padding:10px;background:rgba(255,255,255,.9)}
    .kpi b{display:block;font-size:14px}
    .kpi span{font-size:12px;color:var(--muted);line-height:1.7}

    .ctaRow{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
    .btn{
      border:1px solid var(--line);
      background:#fff;
      padding:10px 12px;border-radius:14px;
      cursor:pointer;
      font-weight:900;
      text-decoration:none;
      display:inline-flex;align-items:center;gap:8px;
    }
    .btn.primary{
      background:linear-gradient(180deg,var(--accent), var(--accent2));
      border-color: rgba(0,0,0,.15);
    }
    .btn.dark{
      background:var(--dark); color:#fff; border-color:rgba(255,255,255,.18);
    }
    .btn:active{transform:translateY(1px)}

    .box{
      border:1px solid rgba(244,196,0,.65);
      background:rgba(244,196,0,.10);
      border-radius:16px;
      padding:12px;
    }
    .row{display:grid;grid-template-columns:1fr auto;gap:10px;align-items:center;margin:8px 0}
    .mono{
      font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace;
      font-size:13px;
      background:rgba(255,255,255,.90);
      border:1px solid var(--line);
      border-radius:12px;
      padding:8px 10px;
      overflow:auto;
      white-space:nowrap;
    }

    .twoCol{display:grid;grid-template-columns:1fr 1fr;gap:14px}
    @media (max-width: 900px){ .twoCol{grid-template-columns:1fr} }

    .ok{color:var(--ok);font-weight:900}
    .warn{color:var(--warn);font-weight:900}
    .danger{color:var(--danger);font-weight:900}

    /* العداد */
    .bigNum{font-size:36px;font-weight:900;letter-spacing:.3px;margin-top:8px}

    /* form */
    form{margin:0}
    .fields{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:10px}
    @media (max-width: 720px){ .fields{grid-template-columns:1fr} }
    label{font-size:13px;font-weight:900}
    input, textarea, select{
      width:100%;
      padding:10px 12px;
      border:1px solid var(--line);
      border-radius:14px;
      font-size:14px;
      outline:none;
      background:#fff;
    }
    textarea{min-height:90px;resize:vertical}
    input:focus, textarea:focus, select:focus{border-color:rgba(0,0,0,.35)}

    .segTitle{margin:10px 0 6px;font-size:13px;font-weight:900}
    .seg{display:flex;gap:8px;flex-wrap:wrap}
    .chip{
      border:1px solid var(--line);
      background:#fff;
      padding:10px 12px;
      border-radius:999px;
      cursor:pointer;
      font-size:13px;
      font-weight:900;
      user-select:none;
      transition:.15s transform ease, .15s background ease;
    }
    .chip:hover{transform:translateY(-1px)}
    .chip.active{background:rgba(244,196,0,.26);border-color:rgba(0,0,0,.25)}
    .hidden{display:none !important}

    .result{
      border:1px solid rgba(0,0,0,.12);
      border-radius:16px;
      background:#fff;
      padding:12px;
      margin-top:12px;
    }
    .result pre{
      margin:0;
      white-space:pre-wrap;
      word-break:break-word;
      font-size:13px;
      line-height:1.75;
    }

    /* Dock سفلي */
    .dock{
      position:fixed;
      left:50%;
      transform:translateX(-50%);
      bottom:12px;
      z-index:95;
      background:rgba(255,255,255,.92);
      border:1px solid var(--line);
      box-shadow:var(--shadow);
      border-radius:999px;
      padding:8px;
      display:flex;
      gap:8px;
      align-items:center;
      max-width: min(800px, calc(100% - 18px));
      overflow:auto;
    }
    .dock a,.dock button{
      border:1px solid var(--line);
      background:#fff;
      padding:10px 12px;
      border-radius:999px;
      font-weight:900;
      cursor:pointer;
      white-space:nowrap;
      text-decoration:none;
    }
    .dock .hot{background:linear-gradient(180deg,var(--accent), var(--accent2));border-color: rgba(0,0,0,.15);}

    .toast{
      position:fixed; inset:auto 16px 84px 16px;
      background:#111; color:#fff;
      padding:10px 12px;
      border-radius:14px;
      max-width:640px;
      box-shadow: var(--shadow);
      display:none;
      z-index:110;
    }
    .toast.show{display:block}

    details{
      border:1px solid var(--line);
      border-radius:14px;
      padding:10px 12px;
      background:#fff;
    }
    details + details{margin-top:10px}
    summary{cursor:pointer;font-weight:900}

    .reveal{opacity:0; transform:translateY(10px); transition:.5s ease}
    .reveal.on{opacity:1; transform:none}

    footer{padding:18px 0 110px}
    .foot{font-size:12px;color:var(--muted);line-height:1.95}

    /* شريط “ثقة” (بدون ادعاء توثيق) */
    .trustStrip{
      display:flex;gap:10px;flex-wrap:wrap;align-items:center;
      padding:10px 12px;border-radius:16px;
      border:1px solid rgba(0,0,0,.10);
      background:rgba(255,255,255,.85);
    }
    .trustItem{
      display:flex;align-items:center;gap:8px;
      padding:8px 10px;border-radius:999px;border:1px solid rgba(0,0,0,.10);
      background:#fff;font-weight:900;font-size:12px;
    }
    .dot{width:10px;height:10px;border-radius:50%;background:var(--accent);border:1px solid rgba(0,0,0,.18)}
  </style>
</head>

<body data-watermark="">
  <div class="urgency">
    <div class="in">
      <div class="miniW" id="urgencyText">—</div>
      <button class="uBtn" type="button" onclick="document.querySelector('#register').scrollIntoView({behavior:'smooth'})">
        سجّل الآن
      </button>
    </div>
  </div>

  <header>
    <div class="topbar wrap">
      <div class="brand">
        <div class="logo" id="logoBox"></div>
        <div>
          <h1 id="siteTitle">—</h1>
          <p>التواصل الرسمي: <b id="coordinatorTag">—</b> — إغلاق التسجيل: <b id="deadlineText">—</b></p>
        </div>
      </div>
      <nav>
        <a class="pill" href="#features">المميزات</a>
        <a class="pill" href="#pay">الدفع</a>
        <a class="pill" href="#register">التسجيل</a>
        <a class="pill" href="#placement">تحديد المستوى</a>
        <a class="pill" href="#share">مشاركة</a>
        <a class="pill" href="#faq">أسئلة</a>
        <a class="pill" href="#privacy">الخصوصية</a>
      </nav>
    </div>
  </header>

  <main class="wrap">
    <section class="grid reveal" style="margin-top:14px">
      <div class="card">
        <div class="title">
          <h2 id="heroTitle">—</h2>
          <span class="badge">باقي: <span id="countdown">—</span></span>
        </div>

        <div class="trustStrip" style="margin-top:12px">
          <div class="trustItem"><span class="dot"></span> تسجيل واضح + رسالة جاهزة للمنسق</div>
          <div class="trustItem"><span class="dot"></span> دفع بنكي أو نجوم تيليجرام</div>
          <div class="trustItem"><span class="dot"></span> تدريب يومي على المتكرر</div>
        </div>

        <div class="kpis">
          <div class="kpi"><b>السعر</b><span>رسوم الدورة: <b id="priceText">—</b></span></div>
          <div class="kpi"><b>مدة الوصول</b><span><b>90 يوم</b> من تاريخ تفعيل اشتراكك</span></div>
          <div class="kpi"><b>إغلاق التسجيل</b><span>ينتهي: <b id="deadlineShort">—</b></span></div>
        </div>

        <div class="ctaRow">
          <a class="btn primary" href="#pay">أبغى أدفع</a>
          <a class="btn dark" href="#register">أبغى أسجل وأرسل الإيصال</a>
          <button class="btn" type="button" id="btnShareTop">مشاركة الإعلان</button>
        </div>

        <p class="mini" style="margin-top:10px">
          **مهم:** الصفحة ما تقدر ترسل ملفات تلقائيًا (قيود المتصفح)، لذلك <span class="warn">ترفق الإيصال يدويًا</span> في الخاص بعد نسخ الرسالة.
        </p>
      </div>

      <aside class="card">
        <div class="title">
          <h2>روابط رسمية</h2>
          <span class="badge">تجنب المصادر المجهولة</span>
        </div>
        <div class="line"></div>
        <div class="ctaRow">
          <a class="btn" id="openCoordinator" href="#" target="_blank" rel="noopener">فتح محادثة المنسق</a>
          <a class="btn" id="openGroup" href="#" target="_blank" rel="noopener">قروب الأكاديمية</a>
          <a class="btn" id="openMainSite" href="#" target="_blank" rel="noopener">موقع الدورة الشاملة</a>
        </div>

        <div class="line"></div>

        <div id="membersCard" class="box">
          <div class="title">
            <h2 style="font-size:16px;margin:0">عدد أعضاء القروب</h2>
            <span class="badge" id="membersUpdated">—</span>
          </div>
          <div class="bigNum" id="membersCount">—</div>
          <div class="mini" id="membersHint">—</div>
        </div>

        <div class="line"></div>
        <p class="mini" id="rotatingTip">—</p>
      </aside>
    </section>

    <section id="features" class="card reveal" style="margin-top:16px">
      <div class="title">
        <h2>مميزات دورة STEP المكثفة 2026</h2>
        <span class="badge">مركزة + عملية</span>
      </div>
      <div class="line"></div>

      <div class="twoCol">
        <div>
          <b>وش تحصل داخل الدورة؟</b>
          <ul style="line-height:1.95;margin:10px 18px">
            <li>مقاطع شرح مسجلة (تفهمها وتطبقها).</li>
            <li>ملفات PDF مرتبة + ملخصات.</li>
            <li>تدريبات يومية على الأسئلة المتكررة.</li>
            <li>ملف إلزامي (واجبات/متابعة) يساعدك ما تتشتت.</li>
            <li>دعم فني للاستفسارات.</li>
          </ul>

          <div class="box">
            <b>مين تناسبه؟</b>
            <div class="mini" style="margin-top:6px">
              - اللي درجاته ثابتة ويبي كسر السقف.<br>
              - اللي اختباره قريب ويبغى خطة مركزة.<br>
              - اللي يبي تدريبات أكثر من الشرح (والشرح موجود وقت الحاجة).
            </div>
          </div>
        </div>

        <div>
          <b>ليش المكثفة “لازم” لبداية 2026؟</b>
          <div class="mini" style="margin-top:8px">
            كثير طلاب يخسرون محاولات وفلوس بسبب التشتت بين دورات وملفات. هنا تمشي “بخطة + تدريب” بدل التجربة.
          </div>

          <div class="line"></div>

          <div class="box">
            <b>تنبيه صريح ضد الاستغلال</b>
            <div class="mini" style="margin-top:6px">
              لا تحول لأي جهة “غير واضحة” أو تطلب منك تحويلات متكررة بدون نظام. اعتمد فقط على قنوات التواصل الموضحة هنا.
            </div>
          </div>

          <div class="line"></div>

          <div class="ctaRow">
            <a class="btn primary" href="#placement">سوّ اختبار تحديد مستوى</a>
            <a class="btn" href="#faq">اقرأ الأسئلة المتكررة</a>
          </div>
        </div>
      </div>
    </section>

    <section id="pay" class="card reveal" style="margin-top:16px">
      <div class="title">
        <h2>الدفع</h2>
        <span class="badge">اختر المناسب لك</span>
      </div>

      <div class="twoCol" style="margin-top:12px">
        <div class="box">
          <h3 style="margin:0 0 8px">**1) تحويل بنكي (مع إرسال إيصال)**</h3>
          <div class="mini">انسخ البيانات بضغطة — ثم بعد التحويل انتقل لنموذج التسجيل.</div>

          <div class="row">
            <div><div class="mini">البنك</div><div class="mono" id="bankName">—</div></div>
            <button class="btn" type="button" onclick="copyText('bankName')">نسخ</button>
          </div>
          <div class="row">
            <div><div class="mini">رقم الحساب</div><div class="mono" id="accNo">—</div></div>
            <button class="btn" type="button" onclick="copyText('accNo')">نسخ</button>
          </div>
          <div class="row">
            <div><div class="mini">الآيبان</div><div class="mono" id="iban">—</div></div>
            <button class="btn" type="button" onclick="copyText('iban')">نسخ</button>
          </div>
          <div class="row">
            <div><div class="mini">اسم المستفيد (عربي)</div><div class="mono" id="benAr">—</div></div>
            <button class="btn" type="button" onclick="copyText('benAr')">نسخ</button>
          </div>
          <div class="row">
            <div>
              <div class="mini">غرض التحويل (انسخه كما هو)</div>
              <div class="mono" id="purpose">—</div>
              <div class="mini">إذا ظهر الاسم مختصر: عادي — الأهم صحة الآيبان.</div>
            </div>
            <button class="btn" type="button" onclick="copyText('purpose')">نسخ</button>
          </div>

          <div class="ctaRow">
            <button class="btn dark" type="button" id="copyAllBank">نسخ كل البيانات</button>
            <a class="btn primary" href="#register">بعد التحويل: نموذج التسجيل</a>
          </div>
        </div>

        <div class="box">
          <h3 style="margin:0 0 8px">**2) نجوم تيليجرام (2000⭐) — تفعيل تلقائي**</h3>
          <div class="mini">
            افتح الرابط → اضغط اشتراك → اختر الدفع بالنجوم → حدّد 2000⭐ → يتفعل تلقائيًا ✅  
            (ما يحتاج ترسل إيصال)
          </div>
          <div class="ctaRow" style="margin-top:10px">
            <a class="btn primary" id="stars1" href="#" target="_blank" rel="noopener">رابط النجوم 1</a>
            <a class="btn primary" id="stars2" href="#" target="_blank" rel="noopener">رابط النجوم 2</a>
            <a class="btn" id="supportBtn" href="#" target="_blank" rel="noopener">احتجت مساعدة؟</a>
          </div>

          <div class="line"></div>
          <div class="mini">
            سؤال يتكرر: **Apple Pay؟**  
            إذا ما تقدر تحوّل بسبب مشكلة بحسابك: استخدم **النجوم** لأنها تتم داخل تيليجرام عبر البطاقة.
          </div>
        </div>
      </div>
    </section>

    <section id="register" class="card reveal" style="margin-top:16px">
      <div class="title">
        <h2>نموذج التسجيل (اختيارات بالأزرار + رسالة جاهزة)</h2>
        <span class="badge">يرسل لك نص مرتب للمنسق</span>
      </div>

      <form id="regForm" novalidate>
        <div class="fields">
          <div>
            <label for="fullName">اسمك الكامل *</label>
            <input id="fullName" required placeholder="مثال: سعود محمد..." />
          </div>
          <div>
            <label for="wa">رقم الواتساب *</label>
            <input id="wa" required inputmode="tel" placeholder="05xxxxxxxx" />
          </div>
          <div>
            <label for="tgUser">يوزر تيليجرام (اختياري)</label>
            <input id="tgUser" placeholder="@username" />
          </div>
          <div>
            <label for="testedBeforeSelect">هل اختبرت STEP قبل؟ *</label>
            <select id="testedBeforeSelect" required>
              <option value="">اختر…</option>
              <option value="نعم">نعم</option>
              <option value="لا">لا</option>
            </select>
          </div>
        </div>

        <div id="prevBox" class="fields hidden">
          <div>
            <label for="lastScore">آخر درجة (تقريبًا)</label>
            <input id="lastScore" inputmode="numeric" placeholder="مثال: 44" />
          </div>
          <div>
            <label for="attempts">عدد المحاولات</label>
            <input id="attempts" inputmode="numeric" placeholder="مثال: 3" />
          </div>
        </div>

        <div class="segTitle">موعد الاختبار *</div>
        <div class="seg" data-seg="examTime">
          <span class="chip" data-val="خلال أسبوع">خلال أسبوع</span>
          <span class="chip" data-val="خلال أسبوعين">خلال أسبوعين</span>
          <span class="chip" data-val="خلال شهر">خلال شهر</span>
          <span class="chip" data-val="خلال شهرين">خلال شهرين</span>
          <span class="chip" data-val="لسا ما حجزت">لسا ما حجزت</span>
        </div>
        <input type="hidden" id="examTime" required />

        <div class="segTitle">الدرجة المستهدفة *</div>
        <div class="seg" data-seg="targetScore">
          <span class="chip" data-val="50+">50+</span>
          <span class="chip" data-val="60+">60+</span>
          <span class="chip" data-val="70+">70+</span>
          <span class="chip" data-val="80+">80+</span>
          <span class="chip" data-val="90+">90+</span>
        </div>
        <input type="hidden" id="targetScore" required />

        <div class="segTitle">طريقة الدفع *</div>
        <div class="seg" data-seg="payMethod">
          <span class="chip" data-val="تحويل بنكي">تحويل بنكي</span>
          <span class="chip" data-val="نجوم تيليجرام (2000⭐)">نجوم تيليجرام (2000⭐)</span>
        </div>
        <input type="hidden" id="payMethod" required />

        <p class="mini" id="bankHint"><span class="warn">للتحويل البنكي:</span> إرفاق الإيصال إلزامي قبل توليد الرسالة.</p>
        <p class="mini hidden" id="starsHint"><span class="ok">للنجوم:</span> التفعيل تلقائي — ما يحتاج إيصال.</p>

        <div class="fields">
          <div>
            <label for="receipt">إرفاق الإيصال (صورة/‏PDF) *</label>
            <input id="receipt" type="file" accept="image/*,application/pdf" />
            <div class="mini">بعد ما تولّد الرسالة: افتح الخاص وأرسل الإيصال يدويًا.</div>
          </div>
          <div>
            <label for="notes">ملاحظات (اختياري)</label>
            <textarea id="notes" placeholder="مثال: مشكلتي بالاستماع / القراءة / القواعد…"></textarea>
          </div>
        </div>

        <div class="fields">
          <div>
            <label style="font-weight:900">إقرارات *</label>
            <div style="display:grid;gap:8px;margin-top:6px">
              <label style="font-weight:800"><input type="checkbox" id="c1" /> أقر بصحة البيانات وسأرسل الإيصال للحساب الرسمي.</label>
              <label style="font-weight:800"><input type="checkbox" id="c2" /> أتعهد بعدم نشر محتوى الدورة أو تداوله.</label>
            </div>
          </div>
          <div class="box">
            <b>بعد التأكيد وش يصير؟</b>
            <div class="mini" style="margin-top:6px">
              يتم تأكيد اشتراكك من الخاص → وتوصلك روابط الدورة + خطة مناسبة حسب موعدك.
            </div>
          </div>
        </div>

        <div class="ctaRow" style="margin-top:12px">
          <button class="btn primary" type="submit">توليد رسالة للمنسق</button>
          <a class="btn" href="#pay">رجوع للدفع</a>
        </div>

        <div id="regResult" class="result hidden">
          <div class="title">
            <h2 style="font-size:16px;margin:0">تم تجهيز الرسالة ✅</h2>
            <span class="badge">الخطوة التالية: إرسال الإيصال</span>
          </div>
          <div class="line"></div>
          <pre id="msgOut"></pre>
          <div class="ctaRow">
            <button class="btn dark" type="button" id="copyMsg">نسخ الرسالة</button>
            <a class="btn primary" id="openChat" href="#" target="_blank" rel="noopener">فتح محادثة المنسق</a>
          </div>
          <p class="mini">
            افتح المحادثة → الصق الرسالة → <b>أرفق الإيصال</b> وأرسله → انتظر التأكيد.
          </p>
        </div>
      </form>
    </section>

    <section id="placement" class="card reveal" style="margin-top:16px">
      <div class="title">
        <h2>اختبار تحديد مستوى (سريع) — توصية خطة</h2>
        <span class="badge">5 أسئلة</span>
      </div>
      <div class="line"></div>

      <div class="mini">
        هذا تقييم سريع يساعدك نحدد لك مسار مناسب (مو بديل لاختبار قياس). اختَر الإجابة الأقرب لك.
      </div>

      <div id="quiz" style="margin-top:12px"></div>

      <div class="ctaRow">
        <button class="btn primary" type="button" id="quizCalc">طلّع نتيجتي</button>
        <button class="btn" type="button" id="quizReset">إعادة</button>
      </div>

      <div id="quizResult" class="result hidden">
        <div class="title">
          <h2 style="font-size:16px;margin:0">نتيجتك</h2>
          <span class="badge" id="quizBadge">—</span>
        </div>
        <div class="line"></div>
        <div class="mini" id="quizText">—</div>
        <div class="ctaRow" style="margin-top:10px">
          <a class="btn dark" href="#register">سجّل الآن</a>
          <a class="btn" href="#pay">روح للدفع</a>
        </div>
      </div>
    </section>

    <section id="share" class="card reveal" style="margin-top:16px">
      <div class="title">
        <h2>مشاركة إعلان جاهز</h2>
        <span class="badge">زر واحد</span>
      </div>
      <div class="line"></div>

      <div class="twoCol">
        <div>
          <b>اختر قالب الإعلان:</b>
          <div class="seg" data-seg="sharePack" style="margin-top:10px">
            <span class="chip active" data-val="short">قصير</span>
            <span class="chip" data-val="mid">متوسط</span>
            <span class="chip" data-val="student">صيغة طالب ينصح</span>
          </div>
          <input type="hidden" id="sharePack" value="short" />
          <p class="mini">إذا جهازك يدعم المشاركة: يفتح لك واتساب/سناب/تيليجرام… مباشرة.</p>
        </div>

        <div class="box">
          <b>مشاركة + نسخ:</b>
          <div class="ctaRow" style="margin-top:10px">
            <button class="btn dark" type="button" id="btnShare">مشاركة الآن</button>
            <button class="btn" type="button" id="btnCopyShare">نسخ نص الإعلان</button>
          </div>
          <div class="result" style="margin-top:10px">
            <pre id="sharePreview"></pre>
          </div>
        </div>
      </div>
    </section>

    <section id="faq" class="card reveal" style="margin-top:16px">
      <div class="title">
        <h2>أسئلة متكررة</h2>
        <span class="badge">واضحة</span>
      </div>
      <div class="line"></div>

      <details>
        <summary>أنا أبي تدريبات أكثر من الشرح… تنفع؟</summary>
        <div class="mini" style="margin-top:8px">نعم — التدريبات اليومية موجودة، والشرح وقت الحاجة.</div>
      </details>

      <details>
        <summary>اختباري قريب… ينفع أدخل؟</summary>
        <div class="mini" style="margin-top:8px">نعم — اختر موعدك في النموذج ونرسل لك مسار مكثف.</div>
      </details>

      <details>
        <summary>كيف أرسل الإيصال؟</summary>
        <div class="mini" style="margin-top:8px">بعد توليد الرسالة: افتح محادثة المنسق → الصق الرسالة → أرفق الإيصال وأرسله.</div>
      </details>

      <details>
        <summary>فيه بلاغات احتيال/أرقام كثيرة؟</summary>
        <div class="mini" style="margin-top:8px">إذا وصلك رقم/حساب ثاني يطلب تحويل مختلف: لا تحول له، وارسل بلاغ من قسم “بلاغ احتيال” تحت.</div>
      </details>
    </section>

    <section id="privacy" class="card reveal" style="margin-top:16px">
      <div class="title">
        <h2>سياسة الخصوصية (مختصرة وواضحة)</h2>
        <span class="badge">شفافية</span>
      </div>
      <div class="line"></div>
      <div class="mini">
        - نجمع بيانات التسجيل (الاسم/وسيلة التواصل/موعد الاختبار) فقط لغرض: **تأكيد الاشتراك + تجهيز الخطة + الدعم**.<br>
        - لا نطلب كلمات مرور ولا رموز تحقق.<br>
        - ملفات الإيصال تُرسل في الخاص للمنسق فقط لتأكيد الدفع.<br>
        - يحق لك طلب حذف بياناتك عبر التواصل مع الحساب الرسمي الموضح في الصفحة.
      </div>

      <div class="line"></div>

      <div class="title">
        <h2 style="font-size:16px;margin:0">بلاغ احتيال / شكوى</h2>
        <span class="badge">يرسل رسالة جاهزة</span>
      </div>
      <div class="mini" style="margin-top:10px">
        إذا تعرضت لمحاولة نصب/حسابات مزيفة: اضغط الزر وارسِل التفاصيل.
      </div>
      <div class="ctaRow" style="margin-top:10px">
        <button class="btn dark" type="button" id="reportFraud">إرسال بلاغ للمنسق</button>
      </div>
    </section>

    <footer class="reveal">
      <div class="line"></div>
      <div class="foot">
        <b>© <span id="yearNow">2026</span> — جميع الحقوق محفوظة.</b><br>
        قروب الأكاديمية: <span id="groupFooter">—</span> — التواصل: <span id="coordFooter">—</span>
      </div>
    </footer>
  </main>

  <div class="dock" aria-label="أزرار سريعة">
    <a class="hot" href="#register">التسجيل</a>
    <a href="#pay">الدفع</a>
    <a href="#placement">تحديد المستوى</a>
    <button type="button" id="dockShare">مشاركة</button>
    <a id="dockSupport" href="#" target="_blank" rel="noopener">الدعم</a>
  </div>

  <div class="toast" id="toast"></div>

  <script>
    // =========================
    // CONFIG (عدّل هنا فقط)
    // =========================
    const CONFIG = {
      brandName: "أكاديمية عايد",
      courseName: "دورة STEP المكثفة 2026",
      watermark: "STEP 2026 — المكثفة",
      coordinatorUser: "Ayed_Academy_2026", // بدون @
      groupLink: "https://t.me/Academy_Ayed_2026",
      mainSiteLink: "https://studentservices241445-rgb.github.io/Hilm-STEP-Academy/",

      priceSAR: "299 ريال",
      deadlineISO: "2026-01-13T23:59:59+03:00",  // نهاية التسجيل

      // عداد الأعضاء:
      // mode: "manual" => رقم ثابت تكتبه
      // mode: "endpoint" => رقم حقيقي من API عبر Worker
      // mode: "hidden" => إخفاء
      members: { mode: "manual", manualValue: 35000, endpointUrl: "" },

      bank: {
        name: "بنك الإنماء",
        acc: "68206067557000",
        iban: "SA4905000068206067557000",
        beneficiaryAr: "مؤسسة كريتيفا جلوبال لتقنية المعلومات",
        purpose: "مشتريات دورة STEP المكثفة منصة عايد الرسمية"
      },

      starsLinks: [
        "https://t.me/+0XBrGJ0i_exiZDVk",
        "https://t.me/+E6HNb3JznoI1MmI0"
      ]
    };

    // =========================
    // شعار/أيقونة (SVG) — مميز وخفيف + يستخدم كـ favicon
    // =========================
    const LOGO_SVG = `
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 128 128">
        <defs>
          <linearGradient id="g" x1="0" x2="1">
            <stop offset="0" stop-color="#f4c400"/>
            <stop offset="1" stop-color="#ffd85b"/>
          </linearGradient>
        </defs>
        <rect x="10" y="10" width="108" height="108" rx="28" fill="url(#g)" stroke="rgba(0,0,0,.18)" stroke-width="3"/>
        <path d="M42 45c0-8 6-14 14-14h17c8 0 14 6 14 14v16c0 8-6 14-14 14H65l-10 9c-1 1-3 0-3-2v-7c-6-2-10-7-10-14V45z"
              fill="#fff" stroke="rgba(0,0,0,.12)" stroke-width="3" />
        <path d="M60 45l18 11-18 11V45z" fill="#111" opacity=".9"/>
        <circle cx="46" cy="89" r="7" fill="#111" opacity=".12"/>
        <circle cx="82" cy="89" r="7" fill="#111" opacity=".12"/>
      </svg>
    `;

    const setFaviconFromSvg = (svg) => {
      const svgUrl = "data:image/svg+xml;charset=utf-8," + encodeURIComponent(svg.trim());
      document.getElementById("favicon").setAttribute("href", svgUrl);
      // عرض الشعار داخل الهيدر
      document.getElementById("logoBox").innerHTML = svg;
    };
    setFaviconFromSvg(LOGO_SVG);

    // =========================
    // Helpers
    // =========================
    const toast = (msg) => {
      const el = document.getElementById("toast");
      el.textContent = msg;
      el.classList.add("show");
      clearTimeout(window.__t);
      window.__t = setTimeout(()=>el.classList.remove("show"), 2200);
    };

    const copyText = async (id) => {
      const val = document.getElementById(id).textContent.trim();
      try{ await navigator.clipboard.writeText(val); toast("تم النسخ ✅"); }
      catch{ toast("ما قدرت أنسخ—انسخ يدويًا."); }
    };
    window.copyText = copyText;

    const tgLink = (text) => `https://t.me/${CONFIG.coordinatorUser}?text=${encodeURIComponent(text)}`;

    // =========================
    // Apply CONFIG to UI
    // =========================
    document.body.setAttribute("data-watermark", CONFIG.watermark);

    document.getElementById("siteTitle").textContent = `${CONFIG.brandName} — ${CONFIG.courseName}`;
    document.getElementById("heroTitle").textContent = `${CONFIG.courseName} — تسجيل سريع وخطة مذاكرة حسب وقتك`;
    document.getElementById("coordinatorTag").textContent = `@${CONFIG.coordinatorUser}`;
    document.getElementById("priceText").textContent = CONFIG.priceSAR;

    const deadlineDate = new Date(CONFIG.deadlineISO);
    document.getElementById("deadlineText").textContent = deadlineDate.toLocaleDateString("ar-SA");
    document.getElementById("deadlineShort").textContent = deadlineDate.toLocaleDateString("ar-SA");

    document.getElementById("openCoordinator").href = `https://t.me/${CONFIG.coordinatorUser}`;
    document.getElementById("supportBtn").href = `https://t.me/${CONFIG.coordinatorUser}`;
    document.getElementById("dockSupport").href = `https://t.me/${CONFIG.coordinatorUser}`;
    document.getElementById("openGroup").href = CONFIG.groupLink;
    document.getElementById("openMainSite").href = CONFIG.mainSiteLink;

    document.getElementById("stars1").href = CONFIG.starsLinks[0];
    document.getElementById("stars2").href = CONFIG.starsLinks[1];

    document.getElementById("bankName").textContent = CONFIG.bank.name;
    document.getElementById("accNo").textContent = CONFIG.bank.acc;
    document.getElementById("iban").textContent = CONFIG.bank.iban;
    document.getElementById("benAr").textContent = CONFIG.bank.beneficiaryAr;
    document.getElementById("purpose").textContent = CONFIG.bank.purpose;

    document.getElementById("yearNow").textContent = new Date().getFullYear();
    document.getElementById("groupFooter").textContent = CONFIG.groupLink;
    document.getElementById("coordFooter").textContent = `@${CONFIG.coordinatorUser}`;

    // شريط علوي نص
    document.getElementById("urgencyText").innerHTML =
      `**تنبيه:** التسجيل يقفل <b>${deadlineDate.toLocaleDateString("ar-SA")}</b> — إذا ناوي تبدأ 2026 بخطة صح لا تأجل.`;

    // =========================
    // Countdown
    // =========================
    const pad = (n) => String(n).padStart(2,"0");
    const updateCountdown = () => {
      const now = new Date();
      const end = new Date(CONFIG.deadlineISO);
      const diff = end - now;
      const el = document.getElementById("countdown");
      if (diff <= 0){ el.textContent = "انتهى"; return; }
      const d = Math.floor(diff / (1000*60*60*24));
      const h = Math.floor((diff / (1000*60*60)) % 24);
      const m = Math.floor((diff / (1000*60)) % 60);
      el.textContent = `${d} يوم ${pad(h)}:${pad(m)}`;
    };
    updateCountdown();
    setInterval(updateCountdown, 30_000);

    // =========================
    // Rotating tips (بدون أسماء مزيفة)
    // =========================
    const tips = [
      "نصيحة: لا تضيع محاولاتك بالتجربة… خل مذاكرتك بخطة + تدريب يومي.",
      "إذا ما تقدر تحوّل بنكي: الدفع بالنجوم داخل تيليجرام حل سريع.",
      "اختبارك قريب؟ اختر موعدك في النموذج عشان نوجهك على اللي يرفع درجتك.",
      "أي تحويل خارج بيانات الصفحة لا تعتمد عليه — وإذا شفت حسابات مزيفة بلغنا.",
      "بعد إرسال الإيصال: انتظر التأكيد ثم توصلك الروابط والخطة."
    ];
    let ti = 0;
    const rotatingTip = document.getElementById("rotatingTip");
    const rotate = () => { rotatingTip.textContent = tips[ti % tips.length]; ti++; };
    rotate();
    setInterval(rotate, 9000);

    // =========================
    // Members count (manual/endpoint/hidden)
    // =========================
    const membersCard = document.getElementById("membersCard");
    const membersCount = document.getElementById("membersCount");
    const membersUpdated = document.getElementById("membersUpdated");
    const membersHint = document.getElementById("membersHint");

    const setManualMembers = () => {
      membersCount.textContent = new Intl.NumberFormat("ar-SA").format(CONFIG.members.manualValue);
      membersUpdated.textContent = "تحديث يدوي";
      membersHint.textContent = "لجعل العدد حقيقي ويتحدث تلقائيًا: استخدم وضع endpoint.";
    };

    const fetchMembers = async () => {
      try{
        const res = await fetch(CONFIG.members.endpointUrl, {cache:"no-store"});
        const data = await res.json();
        const n = Number(data.count);
        if(!Number.isFinite(n)) throw new Error("invalid");
        membersCount.textContent = new Intl.NumberFormat("ar-SA").format(n);
        const stamp = data.updated ? new Date(data.updated) : new Date();
        membersUpdated.textContent = "آخر تحديث: " + stamp.toLocaleTimeString("ar-SA",{hour:"2-digit",minute:"2-digit"});
        membersHint.textContent = "العدد يُسحب من مصدر تيليجرام ويتحدث تلقائيًا.";
      }catch(_){
        membersUpdated.textContent = "تعذر التحديث";
        membersHint.textContent = "تحقق من رابط الـ endpoint أو استخدم اليدوي.";
      }
    };

    const initMembers = () => {
      if(CONFIG.members.mode === "hidden"){ membersCard.classList.add("hidden"); return; }
      if(CONFIG.members.mode === "endpoint" && CONFIG.members.endpointUrl){
        fetchMembers();
        setInterval(fetchMembers, 120000);
        return;
      }
      setManualMembers();
    };
    initMembers();

    // =========================
    // Segmented buttons + share pack
    // =========================
    document.querySelectorAll(".seg").forEach(seg => {
      seg.addEventListener("click", (e) => {
        const chip = e.target.closest(".chip");
        if(!chip) return;

        seg.querySelectorAll(".chip").forEach(c=>c.classList.remove("active"));
        chip.classList.add("active");

        const key = seg.dataset.seg;
        const hidden = document.getElementById(key);
        if(hidden) hidden.value = chip.dataset.val;

        if(key === "payMethod"){
          const isStars = chip.dataset.val.includes("نجوم");
          document.getElementById("starsHint").classList.toggle("hidden", !isStars);
          document.getElementById("bankHint").classList.toggle("hidden", isStars);
          document.getElementById("receipt").required = !isStars;
        }
        if(key === "sharePack"){ updateSharePreview(); }
      });
    });

    // =========================
    // tested before select
    // =========================
    const testedSel = document.getElementById("testedBeforeSelect");
    testedSel.addEventListener("change", ()=>{
      document.getElementById("prevBox").classList.toggle("hidden", testedSel.value !== "نعم");
    });

    // =========================
    // Copy all bank
    // =========================
    document.getElementById("copyAllBank").addEventListener("click", async ()=>{
      const all =
`بيانات التحويل — ${CONFIG.courseName}
البنك: ${CONFIG.bank.name}
رقم الحساب: ${CONFIG.bank.acc}
الآيبان: ${CONFIG.bank.iban}
اسم المستفيد: ${CONFIG.bank.beneficiaryAr}
غرض التحويل: ${CONFIG.bank.purpose}
المبلغ: ${CONFIG.priceSAR}
التواصل: @${CONFIG.coordinatorUser}`;
      try{ await navigator.clipboard.writeText(all); toast("تم نسخ كل البيانات ✅"); }
      catch{ toast("ما قدرت أنسخ—انسخ يدويًا."); }
    });

    // =========================
    // Registration form -> generate message
    // =========================
    const regForm = document.getElementById("regForm");
    const regResult = document.getElementById("regResult");
    const msgOut = document.getElementById("msgOut");
    const openChat = document.getElementById("openChat");
    const copyMsgBtn = document.getElementById("copyMsg");
    let lastMsg = "";

    const clean = (s) => (s || "").toString().trim();

    regForm.addEventListener("submit", (e)=>{
      e.preventDefault();
      try{
        const name = clean(document.getElementById("fullName").value);
        const wa = clean(document.getElementById("wa").value);
        const tg = clean(document.getElementById("tgUser").value);
        const testedBefore = testedSel.value;

        const examTime = clean(document.getElementById("examTime").value);
        const targetScore = clean(document.getElementById("targetScore").value);
        const payMethod = clean(document.getElementById("payMethod").value);

        const notes = clean(document.getElementById("notes").value);

        if(!name) throw new Error("اكتب اسمك");
        if(!wa) throw new Error("اكتب رقم الواتساب");
        if(!testedBefore) throw new Error("حدد هل اختبرت قبل");
        if(!examTime) throw new Error("اختر موعد الاختبار");
        if(!targetScore) throw new Error("اختر الدرجة المستهدفة");
        if(!payMethod) throw new Error("اختر طريقة الدفع");

        if(!document.getElementById("c1").checked || !document.getElementById("c2").checked){
          throw new Error("فعّل الإقرارات");
        }

        const isStars = payMethod.includes("نجوم");
        const receipt = document.getElementById("receipt");
        const fileName = receipt.files && receipt.files[0] ? receipt.files[0].name : "";
        if(!isStars && !fileName) throw new Error("ارفق الإيصال قبل الإرسال");

        const lastScore = clean(document.getElementById("lastScore").value);
        const attempts = clean(document.getElementById("attempts").value);

        const lines = [];
        lines.push("السلام عليكم،");
        lines.push(`أبغى تأكيد تسجيلي في **${CONFIG.courseName}** قبل إغلاق التسجيل.`);
        lines.push("");
        lines.push("**بيانات الطالب:**");
        lines.push(`• الاسم: ${name}`);
        lines.push(`• واتساب: ${wa}`);
        lines.push(`• يوزر تيليجرام: ${tg || "—"}`);
        lines.push(`• موعد الاختبار: ${examTime}`);
        lines.push(`• الدرجة المستهدفة: ${targetScore}`);
        lines.push(`• هل اختبرت قبل؟ ${testedBefore}`);
        if(testedBefore === "نعم"){
          lines.push(`• آخر درجة: ${lastScore || "—"}`);
          lines.push(`• عدد المحاولات: ${attempts || "—"}`);
        }
        if(notes) lines.push(`• ملاحظات: ${notes}`);

        lines.push("");
        lines.push("**بيانات الدفع:**");
        lines.push(`• المبلغ: ${CONFIG.priceSAR}`);
        lines.push(`• طريقة الدفع: ${payMethod}`);

        if(isStars){
          lines.push("• تم الاشتراك عبر نجوم تيليجرام (تفعيل تلقائي) ✅");
          lines.push("• أرسل بياناتي للتنسيق والخطة المناسبة.");
        }else{
          lines.push("• تم التحويل البنكي الآن، وسأرسل الإيصال في نفس المحادثة.");
          lines.push(`• البنك: ${CONFIG.bank.name}`);
          lines.push(`• رقم الحساب: ${CONFIG.bank.acc}`);
          lines.push(`• الآيبان: ${CONFIG.bank.iban}`);
          lines.push(`• اسم المستفيد: ${CONFIG.bank.beneficiaryAr}`);
          lines.push(`• غرض التحويل: ${CONFIG.bank.purpose}`);
          lines.push(`• اسم ملف الإيصال: ${fileName}`);
        }

        lines.push("");
        lines.push("**الطلب:**");
        lines.push("فضلاً تأكيد التسجيل وإرسال روابط الدورة + خطة مذاكرة مناسبة حسب وقت اختباري.");

        lastMsg = lines.join("\n");
        msgOut.textContent = lastMsg;
        openChat.href = tgLink(lastMsg);

        regResult.classList.remove("hidden");
        regResult.scrollIntoView({behavior:"smooth", block:"start"});
        toast("تم تجهيز الرسالة ✅");
      }catch(err){
        toast(err.message || "تأكد من الحقول");
      }
    });

    copyMsgBtn.addEventListener("click", async ()=>{
      if(!lastMsg) return toast("ما فيه رسالة للنسخ");
      try{ await navigator.clipboard.writeText(lastMsg); toast("تم النسخ ✅"); }
      catch{ toast("ما قدرت أنسخ—انسخ يدويًا."); }
    });

    // =========================
    // Share templates
    // =========================
    const shareTemplates = {
      short: () =>
`🔥 ${CONFIG.courseName}
السعر: ${CONFIG.priceSAR}
شرح مسجّل + PDF + تدريبات يومية + دعم
التسجيل يقفل: ${new Date(CONFIG.deadlineISO).toLocaleDateString("ar-SA")}
للتسجيل: @${CONFIG.coordinatorUser}
قروب الأكاديمية: ${CONFIG.groupLink}`,

      mid: () =>
`اللي يبي يدخل 2026 بخطة صح لـ STEP 👇
${CONFIG.courseName}
✅ شرح مسجّل
✅ PDF + تدريبات يومية على المتكرر
✅ خطة حسب موعد اختبارك + دعم
💳 السعر: ${CONFIG.priceSAR}
⏳ التسجيل يقفل: ${new Date(CONFIG.deadlineISO).toLocaleDateString("ar-SA")}
التواصل: @${CONFIG.coordinatorUser}
قروب الأكاديمية: ${CONFIG.groupLink}`,

      student: () =>
`كنت متشتت بين ملفات ودورات… لين دخلت ${CONFIG.courseName}.
الفرق؟ خطة + تدريب يومي بدل “جرّب وخسر محاولات”.
السعر: ${CONFIG.priceSAR}
التسجيل يقفل: ${new Date(CONFIG.deadlineISO).toLocaleDateString("ar-SA")}
@${CONFIG.coordinatorUser}
${CONFIG.groupLink}`
    };

    const sharePreview = document.getElementById("sharePreview");
    const getSharePack = () => (document.getElementById("sharePack")?.value || "short");

    const updateSharePreview = () => {
      const pack = getSharePack();
      sharePreview.textContent = shareTemplates[pack]();
    };
    updateSharePreview();

    const doShare = async () => {
      const text = shareTemplates[getSharePack()]();
      if(navigator.share){
        try{ await navigator.share({ title: CONFIG.courseName, text }); }catch(_){}
        return;
      }
      try{ await navigator.clipboard.writeText(text); toast("تم نسخ الإعلان ✅"); }
      catch{ toast("انسخ الإعلان يدويًا من المعاينة."); }
    };

    document.getElementById("btnShare").addEventListener("click", doShare);
    document.getElementById("btnShareTop").addEventListener("click", doShare);
    document.getElementById("dockShare").addEventListener("click", doShare);

    document.getElementById("btnCopyShare").addEventListener("click", async ()=>{
      const text = shareTemplates[getSharePack()]();
      try{ await navigator.clipboard.writeText(text); toast("تم نسخ الإعلان ✅"); }
      catch{ toast("انسخ يدويًا من المعاينة."); }
    });

    // =========================
    // Fraud report button
    // =========================
    document.getElementById("reportFraud").addEventListener("click", ()=>{
      const msg =
`بلاغ (محاولة احتيال/حساب مزيف):
- وش صار؟ …
- اسم/يوزر الحساب: …
- رقم/رابط: …
- وش طلبوا؟ (تحويل/رسوم/روابط) …
أرجو التحقق واتخاذ الإجراء.`;
      window.open(tgLink(msg), "_blank", "noopener");
    });

    // =========================
    // Quiz (5 Q)
    // =========================
    const quizData = [
      {q:"كم درجتك غالبًا؟", a:[
        {t:"أقل من 45", s:1},
        {t:"45–60", s:2},
        {t:"60–75", s:3},
        {t:"75+", s:4},
      ]},
      {q:"أضعف قسم عندك؟", a:[
        {t:"Grammar", s:1},
        {t:"Reading", s:1},
        {t:"Listening", s:1},
        {t:"كلها شوي", s:2},
      ]},
      {q:"موعد اختبارك؟", a:[
        {t:"خلال أسبوع", s:4},
        {t:"خلال أسبوعين", s:3},
        {t:"خلال شهر", s:2},
        {t:"لسا ما حجزت", s:1},
      ]},
      {q:"تذاكر كم ساعة باليوم؟", a:[
        {t:"أقل من ساعة", s:1},
        {t:"1–2 ساعة", s:2},
        {t:"2–3 ساعات", s:3},
        {t:"3+ ساعات", s:4},
      ]},
      {q:"مشكلتك الأساسية؟", a:[
        {t:"تشتت + ما عندي خطة", s:4},
        {t:"أحتاج تدريبات", s:3},
        {t:"أحتاج مراجعة سريعة", s:2},
        {t:"أبي أرفع درجة محددة", s:3},
      ]},
    ];

    const quizBox = document.getElementById("quiz");
    quizBox.innerHTML = quizData.map((item, i)=>`
      <div class="box" style="margin-bottom:10px">
        <b>${i+1}) ${item.q}</b>
        <div class="seg" data-quiz="${i}" style="margin-top:10px">
          ${item.a.map((x, j)=>`<span class="chip" data-score="${x.s}" data-val="${x.t}">${x.t}</span>`).join("")}
        </div>
        <input type="hidden" id="q_${i}" value="">
      </div>
    `).join("");

    // handle quiz chip clicks
    document.querySelectorAll("[data-quiz]").forEach(seg=>{
      seg.addEventListener("click",(e)=>{
        const chip = e.target.closest(".chip");
        if(!chip) return;
        seg.querySelectorAll(".chip").forEach(c=>c.classList.remove("active"));
        chip.classList.add("active");
        const idx = seg.getAttribute("data-quiz");
        document.getElementById(`q_${idx}`).value = chip.getAttribute("data-score");
      });
    });

    document.getElementById("quizCalc").addEventListener("click", ()=>{
      let total = 0;
      for(let i=0;i<quizData.length;i++){
        const v = Number(document.getElementById(`q_${i}`).value);
        if(!v) return toast("جاوب كل الأسئلة أول");
        total += v;
      }
      const badge = document.getElementById("quizBadge");
      const text = document.getElementById("quizText");
      const res = document.getElementById("quizResult");

      if(total <= 7){
        badge.textContent = "توصية: تأسيس + تدريب تدريجي";
        text.textContent = "ابدأ بمسار هادي: يوميًا (60–90 دقيقة) تدريب متكرر + مراجعة أساسيات. لا تدخل تجربة بلا خطة.";
      }else if(total <= 12){
        badge.textContent = "توصية: مسار متوسط + تدريب يومي";
        text.textContent = "أنت تحتاج: تدريب يومي + خطة حسب موعد الاختبار. ركّز على المتكرر ولا تتشتت بين مصادر كثيرة.";
      }else{
        badge.textContent = "توصية: مسار مكثف (اختبار قريب)";
        text.textContent = "اختبارك قريب/وقت مذاكرتك قوي: امشِ بمسار مكثف + واجبات يومية + مراجعة مركزة على نقاط ضعفك.";
      }

      res.classList.remove("hidden");
      res.scrollIntoView({behavior:"smooth", block:"start"});
    });

    document.getElementById("quizReset").addEventListener("click", ()=>{
      document.querySelectorAll("[data-quiz] .chip").forEach(c=>c.classList.remove("active"));
      for(let i=0;i<quizData.length;i++) document.getElementById(`q_${i}`).value = "";
      document.getElementById("quizResult").classList.add("hidden");
      toast("تمت الإعادة");
    });

    // =========================
    // Reveal on scroll
    // =========================
    const io = new IntersectionObserver((entries)=>{
      entries.forEach(en=>{ if(en.isIntersecting) en.target.classList.add("on"); });
    }, {threshold: .12});
    document.querySelectorAll(".reveal").forEach(el=>io.observe(el));
  </script>
</body>
</html>
