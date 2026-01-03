# step-course-2026
صفحة التسجيل الرسمية لدورة STEP المكثفة 2026: شرح مسجّل + ملفات وتدريبات + خطة مذاكرة + دعم فني. التسجيل متاح حتى 13/01/2026.
<!doctype html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <meta name="description" content="صفحة تسجيل دورة STEP المكثفة 2026 مع عدّاد نهاية التسجيل ونموذج يولّد رسالة جاهزة للمنسق." />
  <title>دورة STEP المكثفة 2026 | التسجيل</title>

  <style>
    :root{
      --bg:#ffd83b;           /* أصفر */
      --card:#ffffff;
      --text:#111;
      --muted:#4b5563;
      --border:rgba(17,17,17,.12);
      --shadow:0 12px 30px rgba(0,0,0,.12);
      --radius:18px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: system-ui, -apple-system, "Segoe UI", Tahoma, Arial, "Noto Kufi Arabic", sans-serif;
      color:var(--text);
      background:
        radial-gradient(1200px 600px at 20% -10%, rgba(255,255,255,.55), transparent 60%),
        radial-gradient(900px 500px at 90% 0%, rgba(255,255,255,.35), transparent 55%),
        var(--bg);
    }
    a{color:inherit}
    .wrap{max-width:1080px;margin:0 auto;padding:22px}
    .topbar{
      display:flex;gap:12px;align-items:center;justify-content:space-between;
      padding:14px 16px;border:1px solid var(--border);
      border-radius:var(--radius); background:rgba(255,255,255,.45); backdrop-filter: blur(6px);
    }
    .brand{display:flex;gap:10px;align-items:center}
    .logo{
      width:44px;height:44px;border-radius:14px;
      background:rgba(17,17,17,.10);
      border:1px solid rgba(17,17,17,.14);
      display:grid;place-items:center;font-weight:900;
    }
    .brand h1{margin:0;font-size:16px;line-height:1.2}
    .brand p{margin:0;color:var(--muted);font-size:12px}

    .actions{display:flex;gap:10px;flex-wrap:wrap}
    .btn{
      border:1px solid rgba(17,17,17,.18);
      background:rgba(255,255,255,.75);
      padding:10px 12px;border-radius:14px;
      cursor:pointer; text-decoration:none; display:inline-flex; gap:8px; align-items:center;
      font-weight:800; font-size:13px;
      transition:.15s transform ease, .15s background ease;
    }
    .btn:hover{transform:translateY(-1px);background:#fff}
    .btn.primary{background:#111;color:#fff;border-color:#111}
    .btn.primary:hover{background:#000}

    .grid{
      display:grid; gap:14px; margin-top:14px;
      grid-template-columns: 1.05fr .95fr;
    }
    @media (max-width: 980px){ .grid{grid-template-columns:1fr} }

    .card{
      background:rgba(255,255,255,.92);
      border:1px solid rgba(17,17,17,.14);
      border-radius:var(--radius);
      box-shadow: var(--shadow);
      padding:16px;
    }
    .title{margin:0 0 6px 0;font-size:18px}
    .sub{margin:0;color:var(--muted);font-size:13px;line-height:1.6}

    .pillrow{display:flex;gap:10px;flex-wrap:wrap;margin-top:12px}
    .pill{
      font-size:12px;font-weight:900;
      padding:8px 10px;border-radius:999px;
      background:rgba(17,17,17,.06); border:1px solid rgba(17,17,17,.10)
    }

    .countbox{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-top:12px}
    .kpi{
      background:rgba(17,17,17,.06); border:1px solid rgba(17,17,17,.12);
      border-radius:16px; padding:10px; text-align:center;
    }
    .kpi b{display:block;font-size:18px}
    .kpi span{color:var(--muted);font-size:12px;font-weight:800}

    .hr{height:1px;background:rgba(17,17,17,.12);margin:14px 0}

    .list{margin:10px 0 0 0;padding:0 18px 0 0}
    .list li{margin:8px 0;line-height:1.7}
    .tag{
      display:inline-block;margin-inline-start:8px;
      font-size:11px;font-weight:900;color:#111;
      background:rgba(255,216,59,.8);
      border:1px solid rgba(17,17,17,.14);
      padding:4px 8px;border-radius:999px;
    }

    label{display:block;font-weight:900;font-size:12px;margin:10px 0 6px}
    input, select, textarea{
      width:100%; padding:11px 12px;
      border-radius:14px; border:1px solid rgba(17,17,17,.18);
      outline:none; background:#fff;
      font-size:14px;
    }
    textarea{min-height:120px;resize:vertical}
    .row{display:grid;grid-template-columns:1fr 1fr;gap:10px}
    @media (max-width: 560px){ .row{grid-template-columns:1fr} }

    .hint{
      margin:8px 0 0 0;
      font-size:12px;color:var(--muted);line-height:1.6
    }

    .copyline{
      display:flex;gap:10px;flex-wrap:wrap;align-items:center;
      padding:12px;border-radius:16px;
      background:rgba(17,17,17,.05);border:1px dashed rgba(17,17,17,.18);
    }
    .mono{
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", monospace;
      font-size:12px; white-space:pre-wrap; line-height:1.6;
      flex:1; min-width:240px;
    }
    .toast{
      position:fixed; left:18px; bottom:18px;
      padding:10px 12px; border-radius:14px;
      background:#111; color:#fff; font-weight:900; font-size:12px;
      opacity:0; transform:translateY(6px);
      transition:.18s ease;
      pointer-events:none;
    }
    .toast.show{opacity:1; transform:translateY(0)}
    .floating{
      position:fixed; right:16px; bottom:16px; z-index:50;
      display:flex; gap:10px; flex-wrap:wrap; justify-content:flex-end;
    }
    .badge{
      font-size:11px;font-weight:900;color:#111;
      background:rgba(255,255,255,.75);
      border:1px solid rgba(17,17,17,.16);
      padding:7px 10px;border-radius:999px;
      backdrop-filter: blur(6px);
    }
    .small{font-size:12px;color:var(--muted);line-height:1.7;margin:0}
    details{
      border:1px solid rgba(17,17,17,.14);
      border-radius:16px; padding:10px 12px;
      background:rgba(255,255,255,.85);
      margin-top:10px;
    }
    summary{cursor:pointer;font-weight:900}
  </style>
</head>

<body>
  <div class="wrap">

    <!-- شريط علوي -->
    <div class="topbar">
      <div class="brand">
        <div class="logo">STEP</div>
        <div>
          <h1 id="brandName">دورة STEP المكثفة 2026</h1>
          <p id="brandLine">تسجيل سريع + خطة واضحة + تدريب يومي على المتكرر</p>
        </div>
      </div>

      <div class="actions">
        <a class="btn primary" href="#register" id="ctaTop">سجّل الآن</a>
        <a class="btn" id="btnCoordinatorTop" target="_blank" rel="noreferrer">تواصل المنسق</a>
        <a class="btn" id="btnFullCourse" target="_blank" rel="noreferrer">موقع الدورة الشاملة</a>
      </div>
    </div>

    <div class="grid">

      <!-- يسار: تعريف + عدّاد + مميزات -->
      <section class="card">
        <h2 class="title">التسجيل مفتوح الآن — وينتهي <span class="tag" id="deadlineTag">13/01/2026</span></h2>
        <p class="sub">
          الفكرة بسيطة: بدل ما تضيّع محاولاتك وفلوسك وأعصابك بين ملفات متفرقة…
          خذ خطة واحدة واضحة وتمشي عليها لين تجيب الدرجة اللي تبيها.
        </p>

        <div class="pillrow">
          <div class="pill">مقاطع شرح مسجلة</div>
          <div class="pill">ملفات + تدريبات</div>
          <div class="pill">تدريب يومي على المتكرر</div>
          <div class="pill">دعم فني داخل تلجرام</div>
          <div class="pill">مدة الوصول: 90 يوم</div>
        </div>

        <div class="countbox" aria-label="عداد نهاية التسجيل">
          <div class="kpi"><b id="d">--</b><span>يوم</span></div>
          <div class="kpi"><b id="h">--</b><span>ساعة</span></div>
          <div class="kpi"><b id="m">--</b><span>دقيقة</span></div>
          <div class="kpi"><b id="s">--</b><span>ثانية</span></div>
        </div>

        <p class="hint" id="deadlineHint"></p>

        <div class="hr"></div>

        <h3 class="title" style="font-size:16px;margin-bottom:4px">وش بيجيك بعد تأكيد الدفع؟</h3>
        <ul class="list">
          <li>رابط/روابط الدخول للمحتوى <b>(90 يوم من تاريخ اشتراكك)</b>.</li>
          <li>ملف خاص بالدورة + جدول مذاكرة حسب وقتك.</li>
          <li>تدريبات يومية على الأسئلة المتكررة + واجبات “لازم تنحل”.</li>
          <li>قناة للكويزات + متابعة واستفسارات.</li>
        </ul>

        <details>
          <summary>أسئلة كثيرة تجينا (مختصر ومفيد)</summary>
          <p class="small">
            <b>هل تنفع لو باقي على اختبارك أيام؟</b> نعم — نعطيك خطة مكثفة وتدريب على المتكرر.<br/>
            <b>أنا تأسيسي قوي وأبي تدريبات بس؟</b> ممتاز — ركّز على الاختبارات والكويزات، والشرح موجود وقت الحاجة.<br/>
            <b>هل فيه Apple Pay؟</b> اللي متوفر عندنا: تحويل بنكي، أو دفع نجوم تيليجرام (بالفيزا/ماستر داخل تيليجرام).
          </p>
        </details>

        <div class="hr"></div>

        <h3 class="title" style="font-size:16px;margin-bottom:4px">تذكير سريع</h3>
        <p class="sub">
          لا تثبّت العرض/التسجيل بالكلام… التثبيت يكون بعد الدفع وتأكيده فقط.
          لو ناوي من جد، لا تخلّي الوقت يسرقك.
        </p>
      </section>

      <!-- يمين: التسجيل + توليد رسالة -->
      <section class="card" id="register">
        <h2 class="title">نموذج التسجيل (يولّد رسالة جاهزة للمنسق)</h2>
        <p class="sub">املأ البيانات واضغط “إنشاء الرسالة” — بعدها إمّا تنسخها أو ترسلها مباشرة للمنسق.</p>

        <div class="row">
          <div>
            <label>اسمك</label>
            <input id="name" placeholder="مثال: سعود" />
          </div>
          <div>
            <label>يوزر تلجرام (اختياري)</label>
            <input id="tg" placeholder="مثال: @yourusername" />
          </div>
        </div>

        <div class="row">
          <div>
            <label>موعد اختبار STEP</label>
            <input id="examDate" placeholder="مثال: خلال شهر / 2026-02-10 / لسا ما حجزت" />
          </div>
          <div>
            <label>طريقة الدفع</label>
            <select id="payMethod">
              <option value="bank">تحويل بنكي (أرسل إيصال)</option>
              <option value="stars">نجوم تيليجرام (تفعيل تلقائي)</option>
            </select>
          </div>
        </div>

        <label>ملاحظة (اختياري)</label>
        <input id="note" placeholder="مثال: أستهدف +80 / عندي محاولات كثيرة" />

        <div class="row" style="margin-top:10px">
          <button class="btn primary" id="build">إنشاء الرسالة</button>
          <button class="btn" id="copyMsg">نسخ الرسالة</button>
        </div>

        <div class="row" style="margin-top:10px">
          <a class="btn primary" id="sendToCoordinator" target="_blank" rel="noreferrer">إرسال للمنسق في تلجرام</a>
          <a class="btn" id="openCoordinator" target="_blank" rel="noreferrer">فتح حساب المنسق</a>
        </div>

        <label>الرسالة الجاهزة</label>
        <textarea id="msg" readonly></textarea>

        <div class="hr"></div>

        <h3 class="title" style="font-size:16px;margin-bottom:4px">التحويل البنكي (انسخ البيانات بزر واحد)</h3>
        <p class="sub">إذا اخترت التحويل البنكي: حول ثم أرسل الإيصال للمنسق بالخاص لتأكيد الاشتراك.</p>

        <div class="copyline">
          <div class="mono" id="bankBox"></div>
          <button class="btn" id="copyBank">نسخ بيانات التحويل</button>
        </div>

        <p class="hint">
          <b>غرض التحويل (اكتبه في البنك):</b> <span id="transferPurpose"></span>
        </p>

        <div class="hr"></div>

        <h3 class="title" style="font-size:16px;margin-bottom:4px">بديل سريع: الدفع بنجوم تيليجرام (2000⭐)</h3>
        <p class="sub">إذا دفعت بالنجوم: يتفعل تلقائيًا ✅ وما يحتاج ترسل إيصال.</p>

        <div class="copyline" style="align-items:flex-start">
          <div class="mono" id="starsBox"></div>
          <div style="display:flex;gap:10px;flex-wrap:wrap">
            <a class="btn primary" id="starsLink1" target="_blank" rel="noreferrer">رابط النجوم 1</a>
            <a class="btn primary" id="starsLink2" target="_blank" rel="noreferrer">رابط النجوم 2</a>
          </div>
        </div>

        <details>
          <summary>شرح سريع جدًا للنجوم</summary>
          <p class="small" id="starsHow"></p>
        </details>

        <div class="hr"></div>

        <details>
          <summary>سياسة الخصوصية (مختصرة وواضحة)</summary>
          <p class="small" id="privacyText"></p>
        </details>
      </section>

    </div>

    <div class="card" style="margin-top:14px">
      <h2 class="title">قناة/قروب التنبيهات</h2>
      <p class="sub">
        تحديثات المحتوى + عروض + خطط مذاكرة + تنبيهات مهمة.
      </p>
      <div class="actions">
        <a class="btn primary" id="academyGroup" target="_blank" rel="noreferrer">فتح قروب الأكاديمية</a>
        <span class="badge" id="yearGreeting">كل عام وأنتم بخير — 2026</span>
      </div>
    </div>

  </div>

  <!-- أزرار عائمة (زر واضح في كل وقت) -->
  <div class="floating">
    <a class="btn primary" href="#register">سجّل الآن</a>
    <a class="btn" id="btnCoordinatorFloat" target="_blank" rel="noreferrer">المنسق</a>
  </div>

  <div class="toast" id="toast">تم النسخ ✅</div>

  <script>
    /***********************
     * الإعدادات (عدّلها إذا احتجت)
     ***********************/
    const CONFIG = {
      // العنوان والهوية
      brandName: "دورة STEP المكثفة 2026",
      brandLine: "شرح مسجّل + تدريبات يومية + خطة واضحة (90 يوم وصول)",

      // نهاية التسجيل (بتوقيت السعودية/اليمن +03:00)
      deadlineISO: "2026-01-13T23:59:59+03:00",
      deadlineLabel: "13/01/2026",
      deadlineText: "ينتهي التسجيل يوم الثلاثاء 13/01/2026 الساعة 11:59 مساءً (بتوقيت السعودية).",

      // المنسق (استقبال الإيصالات والاستفسارات)
      coordinatorUsername: "Hilm_STEP1",   // بدون @
      coordinatorDisplay: "@Hilm_STEP1",

      // رابط موقع الدورة الشاملة الحديثة
      fullCourseWebsite: "https://studentservices241445-rgb.github.io/Hilm-STEP-Academy/",

      // قروب/قناة الأكاديمية
      academyGroup: "https://t.me/Academy_Ayed_2026",

      // بيانات التحويل البنكي (المطلوبة منك)
      bank: {
        bankName: "بنك الإنماء",
        account: "68206067557000",
        iban: "SA4905000068206067557000",
        beneficiaryAr: "مؤسسة كريتيفا جلوبال لتقنية المعلومات",
        beneficiaryEn: "Creativa Global for Information Technology Est."
      },

      // الغرض من التحويل (كما طلبت)
      transferPurpose: "مشتريات دورة STEP المكثفة منصة عايد الرسمية",

      // نجوم تيليجرام
      stars: {
        amount: 2000,
        link1: "https://t.me/+0XBrGJ0i_exiZDVk",
        link2: "https://t.me/+E6HNb3JznoI1MmI0",
        how: [
          "افتح رابط القناة الخاصة المدفوعة.",
          "اضغط زر (اشتراك).",
          "اختر (الدفع بنجوم تيليجرام).",
          "حدّد 2000⭐ وأكمل الدفع ببطاقتك داخل تيليجرام.",
          "بعد الدفع يتحول حسابك (مشترك) إلى (عضو) تلقائيًا ✅ بدون إرسال إيصال."
        ]
      },

      // نص سياسة الخصوصية
      privacy: [
        "نحن لا نخزّن بياناتك في هذا الموقع.",
        "كل المعلومات التي تدخلها تُستخدم فقط لتوليد رسالة جاهزة على جهازك.",
        "إرسال الرسالة يتم عبر تلجرام عند ضغط زر الإرسال، وبموافقتك أنت.",
        "لا تشارك إيصال التحويل إلا عبر الخاص للمنسق فقط."
      ]
    };

    /***********************
     * أدوات مساعدة
     ***********************/
    const $ = (id)=>document.getElementById(id);

    function toast(msg="تم النسخ ✅"){
      const t = $("toast");
      t.textContent = msg;
      t.classList.add("show");
      setTimeout(()=>t.classList.remove("show"), 1200);
    }

    async function copyText(text){
      try{
        await navigator.clipboard.writeText(text);
        toast("تم النسخ ✅");
      }catch(e){
        // fallback
        const ta = document.createElement("textarea");
        ta.value = text;
        document.body.appendChild(ta);
        ta.select();
        document.execCommand("copy");
        ta.remove();
        toast("تم النسخ ✅");
      }
    }

    function encodeTg(text){
      return encodeURIComponent(text);
    }

    /***********************
     * تعبئة الواجهة من الإعدادات
     ***********************/
    function fillUI(){
      $("brandName").textContent = CONFIG.brandName;
      $("brandLine").textContent = CONFIG.brandLine;
      $("deadlineTag").textContent = CONFIG.deadlineLabel;
      $("deadlineHint").textContent = CONFIG.deadlineText;

      const coordUrl = `https://t.me/${CONFIG.coordinatorUsername}`;
      $("btnCoordinatorTop").href = coordUrl;
      $("btnCoordinatorFloat").href = coordUrl;
      $("openCoordinator").href = coordUrl;

      $("btnFullCourse").href = CONFIG.fullCourseWebsite;
      $("academyGroup").href = CONFIG.academyGroup;

      $("transferPurpose").textContent = CONFIG.transferPurpose;

      // صندوق البنك
      $("bankBox").textContent =
`**بيانات التحويل البنكي**
• البنك: ${CONFIG.bank.bankName}
• رقم الحساب: ${CONFIG.bank.account}
• الآيبان: ${CONFIG.bank.iban}
• اسم المستفيد (عربي): ${CONFIG.bank.beneficiaryAr}
• Beneficiary (EN): ${CONFIG.bank.beneficiaryEn}`;

      // النجوم
      $("starsBox").textContent =
`**الدفع بنجوم تيليجرام (${CONFIG.stars.amount}⭐)**
بدون إيصال — التفعيل تلقائي ✅
افتح الرابط > اضغط (اشتراك) > اختر (الدفع بالنجوم) > حدّد ${CONFIG.stars.amount}⭐`;

      $("starsLink1").href = CONFIG.stars.link1;
      $("starsLink2").href = CONFIG.stars.link2;

      // شرح النجوم
      $("starsHow").innerHTML = CONFIG.stars.how.map(x=>`• ${x}`).join("<br/>");

      // الخصوصية
      $("privacyText").innerHTML = CONFIG.privacy.map(x=>`• ${x}`).join("<br/>");
    }

    /***********************
     * العدّاد
     ***********************/
    function startCountdown(){
      const target = new Date(CONFIG.deadlineISO).getTime();
      const tick = ()=>{
        const now = Date.now();
        let diff = target - now;

        if(diff <= 0){
          $("d").textContent = "0";
          $("h").textContent = "0";
          $("m").textContent = "0";
          $("s").textContent = "0";
          $("deadlineHint").textContent = "انتهى وقت التسجيل حسب العدّاد. إذا تحتاج استثناء/حل سريع تواصل مع المنسق.";
          return;
        }

        const d = Math.floor(diff / (1000*60*60*24)); diff -= d*(1000*60*60*24);
        const h = Math.floor(diff / (1000*60*60)); diff -= h*(1000*60*60);
        const m = Math.floor(diff / (1000*60)); diff -= m*(1000*60);
        const s = Math.floor(diff / 1000);

        $("d").textContent = String(d);
        $("h").textContent = String(h).padStart(2,"0");
        $("m").textContent = String(m).padStart(2,"0");
        $("s").textContent = String(s).padStart(2,"0");

        requestAnimationFrame(()=>{});
      };

      tick();
      setInterval(tick, 1000);
    }

    /***********************
     * توليد رسالة المنسق
     ***********************/
    function buildMessage(){
      const name = $("name").value.trim() || "—";
      const tg = $("tg").value.trim() || "—";
      const exam = $("examDate").value.trim() || "لسا ما حجزت";
      const pay = $("payMethod").value === "stars" ? "نجوم تيليجرام (تفعيل تلقائي)" : "تحويل بنكي (إرسال إيصال)";
      const note = $("note").value.trim() || "—";

      const bankBlock =
`البنك: ${CONFIG.bank.bankName}
رقم الحساب: ${CONFIG.bank.account}
الآيبان: ${CONFIG.bank.iban}
اسم المستفيد: ${CONFIG.bank.beneficiaryAr}
Beneficiary (EN): ${CONFIG.bank.beneficiaryEn}
غرض التحويل: ${CONFIG.transferPurpose}`;

      const starsBlock =
`الدفع بالنجوم: ${CONFIG.stars.amount}⭐
رابط 1: ${CONFIG.stars.link1}
رابط 2: ${CONFIG.stars.link2}
(ملاحظة: الدفع بالنجوم يتفعل تلقائيًا ولا يحتاج إيصال)`;

      const msg =
`اشتراك STEP مكثف 2026
الاسم: ${name}
يوزر تلجرام: ${tg}
موعد الاختبار: ${exam}
طريقة الدفع: ${pay}
ملاحظة: ${note}

${$("payMethod").value === "stars" ? starsBlock : bankBlock}

طلب: تفعيل الاشتراك وإرسال روابط الدخول بعد التأكيد ✅`;

      $("msg").value = msg;

      const tgLink = `https://t.me/${CONFIG.coordinatorUsername}?text=${encodeTg(msg)}`;
      $("sendToCoordinator").href = tgLink;

      return msg;
    }

    /***********************
     * أحداث
     ***********************/
    document.addEventListener("DOMContentLoaded", ()=>{
      fillUI();
      startCountdown();

      $("build").addEventListener("click", ()=>{
        buildMessage();
        toast("تم إنشاء الرسالة ✅");
      });

      $("copyMsg").addEventListener("click", async ()=>{
        const text = $("msg").value || buildMessage();
        await copyText(text);
      });

      $("copyBank").addEventListener("click", async ()=>{
        await copyText($("bankBox").textContent.replaceAll("**",""));
      });

      // أول رسالة افتراضية لطيفة
      buildMessage();
    });
  </script>
</body>
</html>
