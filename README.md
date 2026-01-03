<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="صفحة التسجيل الرسمية — دورة STEP المكثفة 2026" />
  <title>أكاديمية عايد — دورة STEP المكثفة 2026</title>

  <style>
    :root{
      --bg:#fff7d1;
      --card:#ffffff;
      --ink:#141414;
      --muted:#666;
      --accent:#f4c400;
      --accent2:#111;
      --ok:#0a7a2f;
      --warn:#b75a00;
      --danger:#b00020;
      --line:rgba(0,0,0,.12);
      --shadow:0 10px 25px rgba(0,0,0,.08);
      --radius:18px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, "Noto Kufi Arabic", "Noto Sans Arabic", Arial, sans-serif;
      background: radial-gradient(1200px 500px at 50% -100px, rgba(244,196,0,.45), transparent 60%),
                  linear-gradient(180deg, var(--bg), #fff 35%, #fff 100%);
      color:var(--ink);
    }
    a{color:inherit}
    .wrap{max-width:1080px;margin:0 auto;padding:18px}
    header{
      position:sticky; top:0; z-index:10;
      backdrop-filter: blur(10px);
      background: rgba(255,255,255,.7);
      border-bottom:1px solid var(--line);
    }
    .topbar{display:flex;align-items:center;justify-content:space-between;gap:12px;padding:14px 18px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{
      width:44px;height:44px;border-radius:12px;
      background: linear-gradient(135deg, var(--accent), #ffe27a);
      border:1px solid rgba(0,0,0,.12);
      box-shadow: var(--shadow);
      display:grid;place-items:center;
      font-weight:900;
    }
    .brand h1{font-size:16px;margin:0}
    .brand p{margin:0;font-size:12px;color:var(--muted)}
    nav{display:flex;gap:10px;flex-wrap:wrap;justify-content:flex-end}
    .pill{
      border:1px solid var(--line);
      background:#fff;
      padding:8px 10px;border-radius:999px;
      font-size:13px;text-decoration:none;
    }
    .pill:hover{border-color:rgba(0,0,0,.25)}
    .hero{padding:22px 0 6px}
    .grid{display:grid;grid-template-columns:1.25fr .75fr;gap:16px}
    @media (max-width: 980px){ .grid{grid-template-columns:1fr} nav{justify-content:flex-start} }
    .card{
      background:var(--card);
      border:1px solid var(--line);
      border-radius:var(--radius);
      box-shadow:var(--shadow);
      padding:16px;
    }
    .title{display:flex;align-items:center;justify-content:space-between;gap:10px}
    .title h2{margin:0;font-size:18px}
    .badge{
      display:inline-flex;align-items:center;gap:6px;
      background: rgba(244,196,0,.22);
      border:1px solid rgba(244,196,0,.55);
      padding:6px 10px;border-radius:999px;
      font-size:12px;font-weight:700;
    }
    .kpis{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-top:12px}
    @media (max-width: 620px){ .kpis{grid-template-columns:1fr} }
    .kpi{border:1px dashed rgba(0,0,0,.18);border-radius:14px;padding:10px}
    .kpi b{display:block;font-size:14px}
    .kpi span{font-size:12px;color:var(--muted)}
    .ctaRow{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
    .btn{
      border:1px solid var(--line);
      background:#fff;
      padding:10px 12px;border-radius:14px;
      cursor:pointer;
      font-weight:800;
      text-decoration:none;
      display:inline-flex;align-items:center;gap:8px;
    }
    .btn.primary{
      background:linear-gradient(180deg,var(--accent), #ffd85b);
      border-color: rgba(0,0,0,.15);
    }
    .btn.dark{
      background:var(--accent2); color:#fff; border-color:rgba(255,255,255,.15);
    }
    .btn:active{transform:translateY(1px)}
    .note{font-size:12.5px;color:var(--muted);line-height:1.7;margin:10px 0 0}
    .line{height:1px;background:var(--line);margin:14px 0}

    .box{
      border:1px solid rgba(244,196,0,.6);
      background:rgba(244,196,0,.10);
      border-radius:16px;
      padding:12px;
    }
    .box h3{margin:0 0 8px;font-size:15px}
    .row{display:grid;grid-template-columns:1fr auto;gap:10px;align-items:center;margin:8px 0}
    .mono{
      font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, "Liberation Mono", monospace;
      font-size:13px;
      background:rgba(255,255,255,.8);
      border:1px solid var(--line);
      border-radius:12px;
      padding:8px 10px;
      overflow:auto;
      white-space:nowrap;
    }
    .mini{font-size:12px;color:var(--muted)}
    .stepper{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
    .step{
      border:1px solid var(--line);
      border-radius:999px;
      padding:6px 10px;
      font-size:12px;
      background:#fff;
    }
    .step strong{font-weight:900}
    .step.ok{border-color:rgba(10,122,47,.35); background:rgba(10,122,47,.08)}
    .step.wait{border-color:rgba(183,90,0,.35); background:rgba(183,90,0,.08)}

    form{margin:0}
    .fields{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:10px}
    @media (max-width: 720px){ .fields{grid-template-columns:1fr} }
    label{font-size:13px;font-weight:800}
    input, textarea{
      width:100%;
      padding:10px 12px;
      border:1px solid var(--line);
      border-radius:14px;
      font-size:14px;
      outline:none;
      background:#fff;
    }
    textarea{min-height:90px;resize:vertical}
    input:focus, textarea:focus{border-color:rgba(0,0,0,.35)}
    .segTitle{margin:10px 0 6px;font-size:13px;font-weight:900}
    .seg{
      display:flex;gap:8px;flex-wrap:wrap;
    }
    .chip{
      border:1px solid var(--line);
      background:#fff;
      padding:10px 12px;
      border-radius:999px;
      cursor:pointer;
      font-size:13px;
      font-weight:800;
      user-select:none;
    }
    .chip.active{
      background:rgba(244,196,0,.25);
      border-color:rgba(0,0,0,.25);
    }
    .hint{font-size:12px;color:var(--muted);margin-top:6px;line-height:1.7}
    .danger{color:var(--danger);font-weight:900}
    .ok{color:var(--ok);font-weight:900}
    .warn{color:var(--warn);font-weight:900}
    .hidden{display:none !important}

    .result{
      border:1px solid rgba(0,0,0,.12);
      border-radius:16px;
      background: #fff;
      padding:12px;
      margin-top:12px;
    }
    .result pre{
      margin:0;
      white-space:pre-wrap;
      word-break:break-word;
      font-size:13px;
      line-height:1.65;
    }

    footer{padding:24px 0 40px}
    .foot{font-size:12px;color:var(--muted);line-height:1.8}
    .toast{
      position:fixed; inset:auto 16px 16px 16px;
      background:#111; color:#fff;
      padding:10px 12px;
      border-radius:14px;
      max-width:560px;
      box-shadow: var(--shadow);
      display:none;
      z-index:50;
    }
    .toast.show{display:block}
    .modal{
      position:fixed; inset:0;
      background:rgba(0,0,0,.55);
      display:none; align-items:center; justify-content:center;
      padding:16px; z-index:60;
    }
    .modal.show{display:flex}
    .modal .card{max-width:760px;width:100%}
  </style>
</head>

<body>
<header>
  <div class="topbar wrap">
    <div class="brand">
      <div class="logo" aria-label="Ayed">A</div>
      <div>
        <h1>أكاديمية عايد — دورة STEP المكثفة 2026</h1>
        <p>صفحة تسجيل وتأكيد دفع — التواصل الرسمي: <b>@Ayed_Academy_2026</b></p>
      </div>
    </div>
    <nav>
      <a class="pill" href="#pay">الدفع</a>
      <a class="pill" href="#register">نموذج التسجيل</a>
      <a class="pill" href="#stars">الدفع بالنجوم</a>
      <a class="pill" href="#reviews">آراء المشتركين</a>
      <a class="pill" href="#reports">بلاغات/شكاوى</a>
    </nav>
  </div>
</header>

<main class="wrap">
  <section class="hero grid">
    <div class="card">
      <div class="title">
        <h2>تم فتح التسجيل ✅</h2>
        <span class="badge">ينتهي التسجيل بعد <span id="countdown">—</span></span>
      </div>

      <div class="kpis">
        <div class="kpi">
          <b>محتوى مكثف ومباشر</b>
          <span>مقاطع شرح مسجّلة + ملفات + تدريبات يومية على المتكرر.</span>
        </div>
        <div class="kpi">
          <b>مناسبة للي وقته ضيق</b>
          <span>خطة مذاكرة حسب وقتك (أسبوع / أسبوعين / شهر).</span>
        </div>
        <div class="kpi">
          <b>صلاحية 90 يوم</b>
          <span>الدورة تبقى معك 90 يوم من تاريخ تفعيل اشتراكك.</span>
        </div>
      </div>

      <div class="ctaRow">
        <a class="btn primary" href="#pay">أبغى أدفع الآن</a>
        <a class="btn dark" href="#register">أرسّل بياناتي للمنسق</a>
        <a class="btn" href="https://studentservices241445-rgb.github.io/Hilm-STEP-Academy/" target="_blank" rel="noopener">
          رابط الدورة الشاملة الحديثة
        </a>
      </div>

      <p class="note">
        **تنبيه مهم:** إذا بتلحق على العرض/المقاعد، التفعيل ما يصير إلا بعد إرسال الإيصال والتأكيد من الحساب الرسمي.
        ولو دفعت بالنجوم (اشتراك القنوات المدفوعة) التفعيل يكون تلقائي.
      </p>

      <div class="line"></div>

      <div class="stepper" aria-label="حالة الطلب">
        <div class="step ok"><strong>1</strong> ادفع</div>
        <div class="step wait"><strong>2</strong> أرسل الإيصال</div>
        <div class="step wait"><strong>3</strong> تأكيد + روابط الدورة</div>
      </div>
    </div>

    <aside class="card">
      <div class="title">
        <h2>سؤال سريع قبل ما تبدأ؟</h2>
        <span class="badge">ردود مختصرة</span>
      </div>
      <div class="line"></div>
      <p class="note"><b>• هل فيه Apple Pay؟</b><br>إذا Apple Pay صعب عندك: استخدم <b>الدفع بنجوم تيليجرام</b> (تفعيل تلقائي) أو جرّب التحويل البنكي من أي بنك.</p>
      <p class="note"><b>• ليه تسألون عن موعد الاختبار؟</b><br>عشان نعطيك خطة تناسب وقتك وتخليك تستفيد من التدريب الصح.</p>
      <p class="note"><b>• وش يوصلني بعد التفعيل؟</b><br>روابط القنوات + ملف خطة مذاكرة + تدريبات يومية على الأسئلة المتكررة.</p>
      <p class="note"><b>• هل تكفي بدل التشتت؟</b><br>إيه. هدفنا تقلل التجارب والخسائر وتدخل بخطة واضحة بدل “ملف هنا وملف هناك”.</p>

      <div class="line"></div>
      <a class="btn" href="https://t.me/Ayed_Academy_2026" target="_blank" rel="noopener">فتح محادثة المنسق</a>
      <button class="btn" type="button" id="openPrivacy">سياسة الخصوصية</button>
    </aside>
  </section>

  <!-- الدفع البنكي -->
  <section id="pay" class="card" style="margin-top:16px">
    <div class="title">
      <h2>بيانات التحويل البنكي (انسخها بضغطة)</h2>
      <span class="badge">قبل النموذج</span>
    </div>

    <div class="box" style="margin-top:12px">
      <h3>**تحويل بنكي — دورة STEP المكثفة 2026**</h3>

      <div class="row">
        <div>
          <div class="mini">البنك</div>
          <div class="mono" id="bankName">بنك الإنماء</div>
        </div>
        <button class="btn" type="button" onclick="copyText('bankName')">نسخ</button>
      </div>

      <div class="row">
        <div>
          <div class="mini">رقم الحساب</div>
          <div class="mono" id="accNo">68206067557000</div>
        </div>
        <button class="btn" type="button" onclick="copyText('accNo')">نسخ</button>
      </div>

      <div class="row">
        <div>
          <div class="mini">الآيبان</div>
          <div class="mono" id="iban">SA4905000068206067557000</div>
        </div>
        <button class="btn" type="button" onclick="copyText('iban')">نسخ</button>
      </div>

      <div class="row">
        <div>
          <div class="mini">اسم المستفيد (عربي)</div>
          <div class="mono" id="benAr">مؤسسة كريتيفا جلوبال لتقنية المعلومات</div>
        </div>
        <button class="btn" type="button" onclick="copyText('benAr')">نسخ</button>
      </div>

      <div class="row">
        <div>
          <div class="mini">Beneficiary Name (English)</div>
          <div class="mono" id="benEn">Creativa Global for Information Technology Est.</div>
        </div>
        <button class="btn" type="button" onclick="copyText('benEn')">Copy</button>
      </div>

      <div class="row">
        <div>
          <div class="mini">غرض التحويل (انسخه كما هو)</div>
          <div class="mono" id="purpose">مشتريات دورة STEP المكثفة منصة عايد الرسمية</div>
          <div class="mini">*لو ظهر اسم المستفيد مختصر في التطبيق: عادي، المهم رقم الآيبان صحيح.*</div>
        </div>
        <button class="btn" type="button" onclick="copyText('purpose')">نسخ</button>
      </div>

      <p class="note">
        بعد التحويل: **انتقل للنموذج تحت** وارفِق الإيصال (صورة/‏PDF) — بعدها بتطلع لك رسالة جاهزة ترسلها للمنسق:
        <b>@Ayed_Academy_2026</b>
      </p>
    </div>
  </section>

  <!-- التسجيل -->
  <section id="register" class="card" style="margin-top:16px">
    <div class="title">
      <h2>نموذج التسجيل (بأزرار اختيار)</h2>
      <span class="badge">إرفاق الإيصال إلزامي للتحويل البنكي</span>
    </div>

    <form id="regForm" novalidate>
      <div class="fields">
        <div>
          <label for="fullName">اسمك الكامل *</label>
          <input id="fullName" name="fullName" placeholder="مثال: سعود محمد..." required />
        </div>
        <div>
          <label for="tgUser">يوزر تيليجرام (اختياري)</label>
          <input id="tgUser" name="tgUser" placeholder="@username" />
        </div>
        <div>
          <label for="wa">رقم الواتساب *</label>
          <input id="wa" name="wa" placeholder="05xxxxxxxx" inputmode="tel" required />
          <div class="hint">للضرورة فقط (تواصل سريع لو صار نقص بالبيانات).</div>
        </div>
        <div>
          <label for="notes">ملاحظات (اختياري)</label>
          <input id="notes" name="notes" placeholder="مثال: اختباري لأول مرة / عندي مشكلة في الاستماع..." />
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

      <div class="segTitle">هل اختبرت STEP قبل؟ *</div>
      <div class="seg" data-seg="testedBefore">
        <span class="chip" data-val="نعم">نعم</span>
        <span class="chip" data-val="لا">لا</span>
      </div>
      <input type="hidden" id="testedBefore" required />

      <div id="prevBox" class="fields hidden" style="margin-top:10px">
        <div>
          <label for="lastScore">آخر درجة (تقريبًا)</label>
          <input id="lastScore" name="lastScore" placeholder="مثال: 44" inputmode="numeric" />
        </div>
        <div>
          <label for="attempts">عدد المحاولات</label>
          <input id="attempts" name="attempts" placeholder="مثال: 3" inputmode="numeric" />
        </div>
      </div>

      <div class="segTitle">طريقة الدفع *</div>
      <div class="seg" data-seg="payMethod">
        <span class="chip" data-val="تحويل بنكي">تحويل بنكي</span>
        <span class="chip" data-val="نجوم تيليجرام (2000⭐)">نجوم تيليجرام (2000⭐)</span>
      </div>
      <input type="hidden" id="payMethod" required />

      <div id="bankHint" class="hint">
        <span class="warn">للتحويل البنكي:</span> لازم ترفق الإيصال قبل الإرسال للمنسق.
      </div>

      <div id="starsHint" class="hint hidden">
        <span class="ok">للنجوم:</span> التفعيل تلقائي بعد الاشتراك، وما يحتاج ترسل إيصال — لكن نفضل ترسل بياناتك للترتيب (اختياري).
      </div>

      <div class="fields" style="margin-top:10px">
        <div>
          <label for="receipt">إرفاق الإيصال (صورة/‏PDF) *</label>
          <input id="receipt" name="receipt" type="file" accept="image/*,application/pdf" />
          <div class="hint">ملاحظة: الملف ما ينرسل من الموقع، لكنه “إلزامي” عشان نضمن أنك جاهز ترسله بالخاص.</div>
        </div>
        <div>
          <label for="consent">إقرار *</label>
          <div style="display:grid;gap:8px;margin-top:6px">
            <label style="font-weight:700">
              <input type="checkbox" id="c1" />
              أقر بصحة البيانات وأتعهد بإرسال الإيصال للحساب الرسمي.
            </label>
            <label style="font-weight:700">
              <input type="checkbox" id="c2" />
              أتعهد بعدم نشر محتوى الدورة أو تداوله.
            </label>
          </div>
        </div>
      </div>

      <div class="ctaRow" style="margin-top:12px">
        <button class="btn primary" type="submit">توليد رسالة للمنسق</button>
        <button class="btn" type="button" onclick="scrollToEl('pay')">ارجع لبيانات التحويل</button>
      </div>

      <div id="regResult" class="result hidden" aria-live="polite">
        <div class="title">
          <h2 style="font-size:16px;margin:0">تم تجهيز رسالتك ✅</h2>
          <span class="badge" id="statusBadge">الحالة: بانتظار التأكيد</span>
        </div>
        <div class="line"></div>
        <pre id="msgOut"></pre>
        <div class="ctaRow">
          <button class="btn dark" type="button" onclick="copyMessage()">نسخ الرسالة</button>
          <a class="btn primary" id="openChat" href="#" target="_blank" rel="noopener">فتح محادثة المنسق</a>
        </div>
        <p class="note">
          بعد ما تفتح المحادثة: **الصق الرسالة** ثم **ارفِق الإيصال** وأرسله.  
          بعدها انتظر التأكيد—وبإذن الله توصلك روابط الدورة.
        </p>
      </div>
    </form>
  </section>

  <!-- الدفع بالنجوم -->
  <section id="stars" class="card" style="margin-top:16px">
    <div class="title">
      <h2>بديل سريع: الدفع بنجوم تيليجرام (2000⭐)</h2>
      <span class="badge">تفعيل تلقائي ✅</span>
    </div>

    <div class="box" style="margin-top:12px">
      <h3>**الطريقة المختصرة**</h3>
      <ol style="margin:8px 18px;line-height:1.9">
        <li>افتح رابط القناة الخاصة المدفوعة</li>
        <li>اضغط <b>اشتراك</b></li>
        <li>اختر <b>الدفع بالنجوم</b> وحدد <b>2000⭐</b></li>
        <li>بعد الدفع يتفعل الاشتراك تلقائيًا ✅</li>
      </ol>

      <div class="ctaRow">
        <a class="btn primary" href="https://t.me/+0XBrGJ0i_exiZDVk" target="_blank" rel="noopener">رابط النجوم 1</a>
        <a class="btn primary" href="https://t.me/+E6HNb3JznoI1MmI0" target="_blank" rel="noopener">رابط النجوم 2</a>
        <a class="btn" href="https://t.me/Ayed_Academy_2026" target="_blank" rel="noopener">لو احتجت مساعدة</a>
      </div>

      <p class="note">
        *مهم:* إذا دفعت بالنجوم **ما تحتاج ترسل إيصال**.  
        وإذا ودك ترسل بياناتك للتنسيق (اختياري): افتح نموذج التسجيل فوق وولّد رسالة.
      </p>
    </div>
  </section>

  <!-- آراء -->
  <section id="reviews" class="card" style="margin-top:16px">
    <div class="title">
      <h2>آراء المشتركين (إرسال رأيك)</h2>
      <span class="badge">يتم استلامها بالحساب الرسمي</span>
    </div>

    <p class="note">
      عشان ما يصير عبث أو كلام غير لائق داخل الموقع (لأنه بدون لوحة تحكم)، تقييمك ينرسل للمنسق كرسالة،
      وهو ينشر المناسب بالقنوات.
    </p>

    <form id="revForm">
      <div class="fields">
        <div>
          <label for="revName">اسمك (اختياري)</label>
          <input id="revName" placeholder="مثال: نورة" />
        </div>
        <div>
          <label for="revRate">تقييمك (1 إلى 5) *</label>
          <input id="revRate" placeholder="مثال: 5" inputmode="numeric" required />
        </div>
      </div>
      <div style="margin-top:10px">
        <label for="revText">رأيك باختصار *</label>
        <textarea id="revText" placeholder="وش أكثر شي فرق معك؟ خطة؟ كويزات؟ شروحات؟" required></textarea>
      </div>
      <div class="ctaRow" style="margin-top:12px">
        <button class="btn primary" type="submit">تجهيز رسالة الرأي للمنسق</button>
      </div>
      <div id="revResult" class="result hidden">
        <pre id="revOut"></pre>
        <div class="ctaRow">
          <button class="btn dark" type="button" onclick="copyTextRaw('revOut')">نسخ الرأي</button>
          <a class="btn primary" id="revChat" href="#" target="_blank" rel="noopener">إرسال للمنسق</a>
        </div>
      </div>
    </form>
  </section>

  <!-- بلاغات/شكاوى -->
  <section id="reports" class="card" style="margin-top:16px">
    <div class="title">
      <h2>بلاغات نصب/مشكلة دفع (نساعدك بلُطف)</h2>
      <span class="badge">وعي + حماية للطلاب</span>
    </div>

    <p class="note">
      إذا أحد طلب منك تحويل لحساب مختلف أو قال “أنا المنسق” وهو مو الحساب الرسمي—بلغنا هنا.
      هدفنا نحميكم من الاستغلال والتشتت.
    </p>

    <form id="repForm">
      <div class="fields">
        <div>
          <label for="repType">نوع البلاغ *</label>
          <input id="repType" placeholder="مثال: رقم يدّعي أنه رسمي / رابط مشبوه / مشكلة تحويل" required />
        </div>
        <div>
          <label for="repLink">يوزر/رابط الطرف الآخر (إن وجد)</label>
          <input id="repLink" placeholder="@username أو رابط" />
        </div>
      </div>
      <div style="margin-top:10px">
        <label for="repDesc">تفاصيل البلاغ *</label>
        <textarea id="repDesc" placeholder="اكتب وش صار باختصار، ولو عندك سكرين/إيصال جهزه ترسله بالخاص." required></textarea>
      </div>
      <div class="ctaRow" style="margin-top:12px">
        <button class="btn primary" type="submit">تجهيز رسالة البلاغ للمنسق</button>
      </div>
      <div id="repResult" class="result hidden">
        <pre id="repOut"></pre>
        <div class="ctaRow">
          <button class="btn dark" type="button" onclick="copyTextRaw('repOut')">نسخ البلاغ</button>
          <a class="btn primary" id="repChat" href="#" target="_blank" rel="noopener">إرسال للمنسق</a>
        </div>
      </div>
    </form>
  </section>

  <footer>
    <div class="foot">
      <div class="line"></div>
      <b>التواصل الرسمي:</b> @Ayed_Academy_2026<br>
      <span>ملاحظة تنظيمية: استخدم الاسم/الشعار فقط إذا كان مصرح لك رسميًا.</span>
    </div>
  </footer>
</main>

<div class="toast" id="toast"></div>

<div class="modal" id="privacyModal" role="dialog" aria-modal="true" aria-label="سياسة الخصوصية">
  <div class="card">
    <div class="title">
      <h2 style="margin:0;font-size:18px">سياسة الخصوصية (مختصرة وواضحة)</h2>
      <button class="btn" type="button" id="closePrivacy">إغلاق</button>
    </div>
    <div class="line"></div>
    <p class="note">
      **وش نجمع؟** الاسم + رقم واتساب + معلومات الاختبار + طريقة الدفع (وعند التحويل البنكي: إيصال الدفع).<br>
      **ليش؟** لتأكيد الاشتراك، ترتيب خطة مناسبة، وتقديم الدعم الفني.<br>
      **من يشوفها؟** الحساب الرسمي فقط: @Ayed_Academy_2026.<br>
      **نشاركها؟** لا. ما يتم بيع البيانات أو مشاركتها مع أي طرف.<br>
      **حذف بياناتك؟** تقدر تطلب حذف بياناتك برسالة مباشرة للحساب الرسمي.
    </p>
  </div>
</div>

<script>
  // ===== إعدادات عامة =====
  const COORDINATOR = "Ayed_Academy_2026";
  const DEADLINE = "2026-01-13T23:59:59+03:00";

  const toast = (msg) => {
    const el = document.getElementById("toast");
    el.textContent = msg;
    el.classList.add("show");
    clearTimeout(window.__t);
    window.__t = setTimeout(()=>el.classList.remove("show"), 2200);
  };

  const scrollToEl = (id) => {
    document.getElementById(id).scrollIntoView({behavior:"smooth", block:"start"});
  };

  const copyText = async (id) => {
    const val = document.getElementById(id).textContent.trim();
    try{ await navigator.clipboard.writeText(val); toast("تم النسخ ✅"); }
    catch{ toast("ما قدرت أنسخ—انسخ يدويًا."); }
  };

  const copyTextRaw = async (id) => {
    const val = document.getElementById(id).innerText.trim();
    try{ await navigator.clipboard.writeText(val); toast("تم النسخ ✅"); }
    catch{ toast("ما قدرت أنسخ—انسخ يدويًا."); }
  };

  // ===== عدّاد =====
  const pad = (n) => String(n).padStart(2,"0");
  const updateCountdown = () => {
    const now = new Date();
    const end = new Date(DEADLINE);
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

  // ===== Segmented buttons =====
  const initSeg = () => {
    document.querySelectorAll(".seg").forEach(seg => {
      seg.addEventListener("click", (e) => {
        const chip = e.target.closest(".chip");
        if(!chip) return;

        // toggle active within this seg
        seg.querySelectorAll(".chip").forEach(c=>c.classList.remove("active"));
        chip.classList.add("active");

        const key = seg.dataset.seg;
        const hidden = document.getElementById(key);
        hidden.value = chip.dataset.val;

        // conditional UI
        if(key === "testedBefore"){
          const prev = document.getElementById("prevBox");
          prev.classList.toggle("hidden", hidden.value !== "نعم");
        }
        if(key === "payMethod"){
          const isStars = hidden.value.includes("نجوم");
          document.getElementById("starsHint").classList.toggle("hidden", !isStars);
          document.getElementById("bankHint").classList.toggle("hidden", isStars);

          // receipt requirement changes
          const receipt = document.getElementById("receipt");
          receipt.required = !isStars; // bank transfer => required
        }
      });
    });
  };
  initSeg();

  // ===== Privacy modal =====
  const modal = document.getElementById("privacyModal");
  document.getElementById("openPrivacy").onclick = ()=> modal.classList.add("show");
  document.getElementById("closePrivacy").onclick = ()=> modal.classList.remove("show");
  modal.addEventListener("click", (e)=>{ if(e.target === modal) modal.classList.remove("show"); });

  // ===== Telegram deeplink with prefilled text =====
  const tgLink = (text) => {
    const enc = encodeURIComponent(text);
    return `https://t.me/${COORDINATOR}?text=${enc}`;
  };

  // ===== Registration submit =====
  const regForm = document.getElementById("regForm");
  const regResult = document.getElementById("regResult");
  const msgOut = document.getElementById("msgOut");
  const openChat = document.getElementById("openChat");

  const clean = (s) => (s || "").toString().trim();
  const must = (v, msg) => { if(!clean(v)) throw new Error(msg); };

  let lastMsg = "";

  regForm.addEventListener("submit", (e) => {
    e.preventDefault();
    try{
      const name = clean(document.getElementById("fullName").value);
      const wa = clean(document.getElementById("wa").value);
      const tg = clean(document.getElementById("tgUser").value);
      const notes = clean(document.getElementById("notes").value);

      const examTime = clean(document.getElementById("examTime").value);
      const targetScore = clean(document.getElementById("targetScore").value);
      const testedBefore = clean(document.getElementById("testedBefore").value);
      const payMethod = clean(document.getElementById("payMethod").value);

      must(name, "اكتب اسمك");
      must(wa, "اكتب رقم الواتساب");
      must(examTime, "اختر موعد الاختبار");
      must(targetScore, "اختر الدرجة المستهدفة");
      must(testedBefore, "حدد هل اختبرت قبل");
      must(payMethod, "اختر طريقة الدفع");

      const c1 = document.getElementById("c1").checked;
      const c2 = document.getElementById("c2").checked;
      if(!c1 || !c2) throw new Error("فعّل الإقرارات");

      const isStars = payMethod.includes("نجوم");
      const receipt = document.getElementById("receipt");
      const fileName = receipt.files && receipt.files[0] ? receipt.files[0].name : "";

      if(!isStars){
        if(!fileName) throw new Error("ارفق الإيصال (صورة أو PDF) قبل الإرسال");
      }

      const lastScore = clean(document.getElementById("lastScore").value);
      const attempts = clean(document.getElementById("attempts").value);

      const lines = [];
      lines.push("السلام عليكم،");
      lines.push("أبغى تأكيد اشتراكي في **دورة STEP المكثفة 2026**.");
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
      lines.push(`• طريقة الدفع: ${payMethod}`);

      if(isStars){
        lines.push("• ملاحظة: تم الاشتراك عبر نجوم تيليجرام (تفعيل تلقائي) ✅");
        lines.push("• أرسلت بياناتي للترتيب وتوجيه الخطة.");
      }else{
        lines.push("• تم التحويل البنكي الآن، وأرفقت الإيصال في نفس المحادثة.");
        lines.push("• غرض التحويل: مشتريات دورة STEP المكثفة منصة عايد الرسمية");
        lines.push(`• اسم الملف المرفق: ${fileName}`);
      }

      lines.push("");
      lines.push("**الطلب:**");
      lines.push("فضلاً تأكيد الاشتراك وإرسال روابط الدورة + الخطة المناسبة حسب وقت اختباري.");
      lines.push("");
      lines.push("شاكر لكم 🌟");

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

  const copyMessage = async () => {
    if(!lastMsg) return toast("ما فيه رسالة للنسخ");
    try{ await navigator.clipboard.writeText(lastMsg); toast("تم النسخ ✅"); }
    catch{ toast("ما قدرت أنسخ—انسخ يدويًا."); }
  };

  // ===== Reviews submit =====
  const revForm = document.getElementById("revForm");
  const revResult = document.getElementById("revResult");
  const revOut = document.getElementById("revOut");
  const revChat = document.getElementById("revChat");

  revForm.addEventListener("submit", (e)=>{
    e.preventDefault();
    try{
      const n = clean(document.getElementById("revName").value);
      const r = clean(document.getElementById("revRate").value);
      const t = clean(document.getElementById("revText").value);
      if(!r || isNaN(Number(r)) || Number(r) < 1 || Number(r) > 5) throw new Error("اكتب التقييم من 1 إلى 5");
      if(!t) throw new Error("اكتب رأيك");

      const msg =
`**[رأي مشترك]**
• الاسم: ${n || "—"}
• التقييم: ${r}/5
• الرأي:
${t}

(للنشر إذا مناسب)`;

      revOut.textContent = msg;
      revChat.href = tgLink(msg);
      revResult.classList.remove("hidden");
      revResult.scrollIntoView({behavior:"smooth"});
      toast("تم تجهيز رسالة الرأي ✅");
    }catch(err){
      toast(err.message || "تأكد من الحقول");
    }
  });

  // ===== Reports submit =====
  const repForm = document.getElementById("repForm");
  const repResult = document.getElementById("repResult");
  const repOut = document.getElementById("repOut");
  const repChat = document.getElementById("repChat");

  repForm.addEventListener("submit", (e)=>{
    e.preventDefault();
    try{
      const type = clean(document.getElementById("repType").value);
      const link = clean(document.getElementById("repLink").value);
      const desc = clean(document.getElementById("repDesc").value);
      if(!type) throw new Error("حدد نوع البلاغ");
      if(!desc) throw new Error("اكتب تفاصيل البلاغ");

      const msg =
`**[بلاغ/شكوى]**
• النوع: ${type}
• الطرف/الرابط: ${link || "—"}
• التفاصيل:
${desc}

ملاحظة: عندي سكرينات/إثباتات وبأرسلها بالمرفقات إن لزم.`;

      repOut.textContent = msg;
      repChat.href = tgLink(msg);
      repResult.classList.remove("hidden");
      repResult.scrollIntoView({behavior:"smooth"});
      toast("تم تجهيز رسالة البلاغ ✅");
    }catch(err){
      toast(err.message || "تأكد من الحقول");
    }
  });
</script>
</body>
</html>
