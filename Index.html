<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>سیستم مدیریت فابریکه</title>
<style>
*{box-sizing:border-box;font-family:Tahoma,Arial,sans-serif}
body{margin:0;background:#f0f2f5;color:#222;font-size:14px}
header{background:linear-gradient(135deg,#1e3a5f,#2c3e50);color:#fff;padding:12px 15px;display:flex;flex-wrap:wrap;justify-content:space-between;align-items:center;gap:10px;position:sticky;top:0;z-index:100;box-shadow:0 2px 10px rgba(0,0,0,.2)}
header h1{margin:0;font-size:17px}
.ubar{display:flex;gap:6px;align-items:center;font-size:12px;flex-wrap:wrap}
.ubar button{padding:7px 11px;border:none;border-radius:6px;cursor:pointer;font-weight:bold;font-size:12px;color:#fff}
.bg{background:#27ae60}.br{background:#e74c3c}.bb{background:#2980b9}.bo{background:#f39c12}.bp{background:#8e44ad}
nav{display:flex;flex-wrap:wrap;background:#34495e;overflow-x:auto}
nav button{flex:1;min-width:95px;padding:10px 6px;border:none;background:none;color:#fff;cursor:pointer;font-size:12px;border-bottom:3px solid transparent;white-space:nowrap}
nav button:hover{background:#2c3e50}
nav button.active{background:#2c3e50;border-bottom-color:#f1c40f;font-weight:bold}
main{padding:12px;max-width:1400px;margin:auto;padding-bottom:80px}
.page{display:none}.page.active{display:block}
.card{background:#fff;border-radius:10px;padding:14px;margin-bottom:12px;box-shadow:0 2px 6px rgba(0,0,0,.06)}
.card h3{margin:0 0 12px;color:#1e3a5f;font-size:15px;display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:8px}
.card h3 .actions{display:flex;gap:6px;flex-wrap:wrap}
.card h3 .actions button{font-size:11px;padding:5px 10px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:8px}
.grid input,.grid select,.grid textarea{width:100%;padding:8px;border:1px solid #ccd;border-radius:7px;font-size:13px;font-family:inherit}
.grid button{padding:9px;background:#2980b9;color:#fff;border:none;border-radius:7px;cursor:pointer;font-weight:bold;font-size:13px}
.grid button:hover{background:#1c5980}
.grid button.cancel{background:#95a5a6}
.grid button.update{background:#f39c12}
.tw{overflow-x:auto}
table{width:100%;border-collapse:collapse;margin-top:8px;font-size:12px;min-width:500px}
th,td{border:1px solid #dde;padding:7px;text-align:right;vertical-align:middle}
th{background:#ecf0f1;color:#1e3a5f;font-weight:bold;position:sticky;top:0}
tr:nth-child(even){background:#fafbfc}
tr:hover{background:#eef5ff}
.del{background:#e74c3c;color:#fff;border:none;padding:4px 8px;border-radius:4px;cursor:pointer;font-size:11px;margin:1px}
.edt{background:#f39c12;color:#fff;border:none;padding:4px 8px;border-radius:4px;cursor:pointer;font-size:11px;margin:1px}
.stat{background:linear-gradient(135deg,#ecf0f1,#dfe6e9);padding:14px;border-radius:9px;text-align:center}
.stat span{font-size:12px;color:#555;display:block}
.stat b{display:block;font-size:18px;color:#1e3a5f;margin-top:4px}
.stat.green b{color:#27ae60}.stat.red b{color:#c0392b}.stat.blue b{color:#2980b9}.stat.orange b{color:#e67e22}
.login-bg{min-height:100vh;background:linear-gradient(135deg,#1e3a5f,#2c3e50);display:flex;align-items:center;justify-content:center;padding:20px}
.login-box{width:100%;max-width:360px;background:#fff;padding:28px;border-radius:14px;box-shadow:0 20px 60px rgba(0,0,0,.35)}
.login-box h2{text-align:center;color:#1e3a5f;margin:0 0 6px;font-size:20px}
.login-box p{text-align:center;color:#888;font-size:12px;margin:0 0 18px}
.login-box input{width:100%;padding:11px;margin:5px 0;border:1px solid #ccd;border-radius:8px;font-size:14px}
.login-box button{width:100%;padding:11px;background:#2980b9;color:#fff;border:none;border-radius:8px;cursor:pointer;font-weight:bold;margin-top:8px;font-size:14px}
.error{color:#e74c3c;text-align:center;margin-top:8px;font-size:12px;min-height:16px}
.hint{font-size:11px;color:#888;text-align:center;margin-top:12px;padding:9px;background:#f8f9fa;border-radius:6px}
.empty{text-align:center;padding:22px;color:#999;font-size:13px}
.tabs{display:flex;gap:6px;flex-wrap:wrap;margin-bottom:10px}
.tabs button{padding:7px 12px;border:1px solid #ccd;background:#fff;border-radius:20px;cursor:pointer;font-size:12px}
.tabs button.active{background:#2980b9;color:#fff;border-color:#2980b9}
.positive{color:#27ae60;font-weight:bold}
.negative{color:#c0392b;font-weight:bold}
tr.clickable{cursor:pointer}
tr.clickable:hover{background:#dff0ff}
.ledger-head{background:#f8f9fa;padding:12px;border-radius:8px;margin-bottom:12px;display:flex;justify-content:space-between;flex-wrap:wrap;gap:10px;align-items:center}
.ledger-head b{color:#1e3a5f}
@media(max-width:600px){nav button{min-width:75px;font-size:11px;padding:9px 4px}.stat b{font-size:15px}header h1{font-size:15px}}
</style>
</head>
<body>

<div id="loginView" class="login-bg">
  <div class="login-box">
    <h2>🏭 سیستم مدیریت فابریکه</h2>
    <p>واردات • خرڅلاو • ګدام • حسابونه</p>
    <input type="text" id="lgUser" placeholder="نام کاربر">
    <input type="password" id="lgPass" placeholder="رمز">
    <button onclick="doLogin()">ورود</button>
    <div class="error" id="lgErr"></div>
    <div class="hint">ورود اول: <b>admin</b> / <b>admin123</b></div>
  </div>
</div>

<div id="appView" style="display:none">
  <header>
    <h1>🏭 سیستم مدیریت فابریکه</h1>
    <div class="ubar">
      <span id="currentUser"></span>
      <button class="bo" id="usersBtn" onclick="showPage('users',document.querySelector('nav button[data-p=users]'))" style="display:none">👥 کاربران</button>
      <button class="bg" onclick="exportData()">⬇ بکاپ</button>
      <button class="bb" onclick="document.getElementById('impFile').click()">⬆ بازگردانی</button>
      <button class="br" onclick="doLogout()">خروج</button>
      <input type="file" id="impFile" accept=".json" style="display:none" onchange="importData(event)">
    </div>
  </header>

  <nav>
    <button class="active" data-p="dashboard" onclick="showPage('dashboard',this)">📊 داشبورد</button>
    <button data-p="imports" onclick="showPage('imports',this)">📥 واردات</button>
    <button data-p="sales" onclick="showPage('sales',this)">📤 خرڅلاو</button>
    <button data-p="warehouse" onclick="showPage('warehouse',this)">📦 ګدام</button>
    <button data-p="expenses" onclick="showPage('expenses',this)">💸 مصارف</button>
    <button data-p="incomes" onclick="showPage('incomes',this)">💰 عاید</button>
    <button data-p="workers" onclick="showPage('workers',this)">👷 کارګران</button>
    <button data-p="salesmen" onclick="showPage('salesmen',this)">🚗 سیل مینان</button>
    <button data-p="loans" onclick="showPage('loans',this)">💵 قرضونه</button>
    <button data-p="reports" onclick="showPage('reports',this)">📈 راپورونه</button>
    <button data-p="users" onclick="showPage('users',this)">👥 کاربران</button>
  </nav>

  <main>

    <!-- DASHBOARD -->
    <div id="dashboard" class="page active">
      <div class="card"><h3>📊 خلاصه کل</h3>
        <div class="grid">
          <div class="stat blue"><span>ارزش کل واردات</span><b id="dImp">0</b></div>
          <div class="stat green"><span>ارزش کل خرڅلاو</span><b id="dSal">0</b></div>
          <div class="stat orange"><span>ارزش ګدام</span><b id="dWh">0</b></div>
          <div class="stat red"><span>کل مصارف</span><b id="dExp">0</b></div>
          <div class="stat green"><span>عاید نور</span><b id="dInc">0</b></div>
          <div class="stat green"><span>ګټه ناخالصه</span><b id="dProfit">0</b></div>
        </div>
      </div>
      <div class="card"><h3>💵 وضعیت پول</h3>
        <div class="grid">
          <div class="stat green"><span>پول رسیده (خرڅلاو)</span><b id="dIn">0</b></div>
          <div class="stat red"><span>پول پرداخته (واردات)</span><b id="dOut">0</b></div>
          <div class="stat"><span>پول باقی صندوق</span><b id="dCash">0</b></div>
        </div>
      </div>
      <div class="card"><h3>⚖️ حساب‌های معلق</h3>
        <div class="grid">
          <div class="stat green"><span>طلب ما (خرڅلاو باقی)</span><b id="dRecv">0</b></div>
          <div class="stat red"><span>بدهی ما (واردات باقی)</span><b id="dPay">0</b></div>
          <div class="stat red"><span>معاش باقی کارګران</span><b id="dWkBal">0</b></div>
          <div class="stat green"><span>طلب از سیل مینان</span><b id="dSmBal">0</b></div>
        </div>
      </div>
    </div>

    <!-- IMPORTS -->
    <div id="imports" class="page">
      <div class="card">
        <h3><span id="impTitle">➕ ثبت واردات جدید</span></h3>
        <form onsubmit="saveImport(event)" id="impForm">
          <div class="grid">
            <input name="date" type="date" required>
            <input name="supplier" placeholder="عرضه‌کننده / فروشنده" required>
            <input name="item" placeholder="جنس (نام مواد)" required>
            <input name="vehicle" placeholder="نمبر موتر / بل">
            <input name="kg" type="number" step="any" placeholder="وزن (کیلو)" required oninput="calcImp()">
            <input name="rate" type="number" step="any" placeholder="قیمت فی کیلو" required oninput="calcImp()">
            <input name="total" type="number" step="any" placeholder="مجموع پول (خودکار)">
            <input name="paid" type="number" step="any" placeholder="پرداخت شده" value="0" oninput="calcImp()">
            <input name="remaining" type="number" step="any" placeholder="باقی (خودکار)">
            <input name="note" placeholder="یادداشت">
            <button type="submit" id="impBtn">ثبت</button>
            <button type="button" class="cancel" id="impCancel" onclick="cancelEdit('imports')" style="display:none">لغو</button>
          </div>
        </form>
      </div>
      <div class="card"><h3><span>📥 لیست واردات</span><span id="impSum"></span></h3>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>تاریخ</th><th>عرضه‌کننده</th><th>جنس</th><th>موتر</th><th>کیلو</th><th>فی کیلو</th><th>مجموع</th><th>پرداخت</th><th>باقی</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-imports"></tbody>
        </table></div>
      </div>
    </div>

    <!-- SALES -->
    <div id="sales" class="page">
      <div class="card">
        <h3><span id="salTitle">➕ ثبت خرڅلاو جدید</span></h3>
        <form onsubmit="saveSale(event)" id="salForm">
          <div class="grid">
            <input name="date" type="date" required>
            <input name="customer" placeholder="خریدار" required>
            <input name="salesman" placeholder="سیل مین">
            <input name="item" placeholder="جنس" required>
            <input name="kg" type="number" step="any" placeholder="وزن (کیلو)" required oninput="calcSal()">
            <input name="rate" type="number" step="any" placeholder="قیمت فی کیلو" required oninput="calcSal()">
            <input name="total" type="number" step="any" placeholder="مجموع (خودکار)">
            <input name="paid" type="number" step="any" placeholder="رسیده" value="0" oninput="calcSal()">
            <input name="remaining" type="number" step="any" placeholder="باقی (خودکار)">
            <input name="note" placeholder="یادداشت">
            <button type="submit" id="salBtn">ثبت</button>
            <button type="button" class="cancel" id="salCancel" onclick="cancelEdit('sales')" style="display:none">لغو</button>
          </div>
        </form>
      </div>
      <div class="card"><h3><span>📤 لیست خرڅلاو</span><span id="salSum"></span></h3>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>تاریخ</th><th>خریدار</th><th>سیل مین</th><th>جنس</th><th>کیلو</th><th>فی کیلو</th><th>مجموع</th><th>رسیده</th><th>باقی</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-sales"></tbody>
        </table></div>
      </div>
    </div>

    <!-- WAREHOUSE -->
    <div id="warehouse" class="page">
      <div class="card"><h3>📦 موجودی ګدام (محاسبه خودکار)</h3>
        <p style="color:#666;font-size:12px;margin:0 0 10px">موجودی هر جنس = کل واردات − کل خرڅلاو</p>
        <div class="tw"><table>
          <thead><tr><th>جنس</th><th>وارد شده (کیلو)</th><th>خرڅ شده (کیلو)</th><th>موجود (کیلو)</th><th>ارزش خرید</th><th>ارزش فروش تخمینی</th><th>سود تخمینی</th></tr></thead>
          <tbody id="tb-warehouse"></tbody>
        </table></div>
      </div>
    </div>

    <!-- EXPENSES -->
    <div id="expenses" class="page">
      <div class="card">
        <h3><span id="expTitle">➕ ثبت مصرف جدید</span></h3>
        <form onsubmit="saveSimple(event,'expenses',['date','category','descr','amount','note'])" id="expForm">
          <div class="grid">
            <input name="date" type="date" required>
            <select name="category">
              <option>کرایه</option><option>برق</option><option>معاش کارګر</option><option>ترانسپورت</option>
              <option>سوخت</option><option>تعمیرات</option><option>خرید لوازم</option><option>نور</option>
            </select>
            <input name="descr" placeholder="تفصیل" required>
            <input name="amount" type="number" step="any" placeholder="مقدار (افغانی)" required>
            <input name="note" placeholder="یادداشت">
            <button type="submit" id="expBtn">ثبت</button>
            <button type="button" class="cancel" id="expCancel" onclick="cancelEdit('expenses')" style="display:none">لغو</button>
          </div>
        </form>
      </div>
      <div class="card"><h3><span>💸 لیست مصارف</span><span id="expSum"></span></h3>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>تاریخ</th><th>دسته</th><th>تفصیل</th><th>مقدار</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-expenses"></tbody>
        </table></div>
      </div>
    </div>

    <!-- INCOMES -->
    <div id="incomes" class="page">
      <div class="card">
        <h3><span id="incTitle">➕ ثبت عاید جدید</span></h3>
        <form onsubmit="saveSimple(event,'incomes',['date','source','amount','note'])" id="incForm">
          <div class="grid">
            <input name="date" type="date" required>
            <input name="source" placeholder="منبع عاید" required>
            <input name="amount" type="number" step="any" placeholder="مقدار (افغانی)" required>
            <input name="note" placeholder="یادداشت">
            <button type="submit" id="incBtn">ثبت</button>
            <button type="button" class="cancel" id="incCancel" onclick="cancelEdit('incomes')" style="display:none">لغو</button>
          </div>
        </form>
      </div>
      <div class="card"><h3><span>💰 لیست عاید</span><span id="incSum"></span></h3>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>تاریخ</th><th>منبع</th><th>مقدار</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-incomes"></tbody>
        </table></div>
      </div>
    </div>

    <!-- WORKERS -->
    <div id="workers" class="page">
      <div class="card">
        <h3><span id="wkTitle">➕ کارګر جدید</span></h3>
        <form onsubmit="saveSimple(event,'workers',['name','phone','position','salary','note'])" id="wkForm">
          <div class="grid">
            <input name="name" placeholder="نام کارګر" required>
            <input name="phone" placeholder="شماره تماس">
            <input name="position" placeholder="وظیفه / بخش">
            <input name="salary" type="number" step="any" placeholder="معاش ماهانه">
            <input name="note" placeholder="یادداشت">
            <button type="submit" id="wkBtn">ثبت</button>
            <button type="button" class="cancel" id="wkCancel" onclick="cancelEdit('workers')" style="display:none">لغو</button>
          </div>
        </form>
      </div>
      <div class="card"><h3>👷 لیست کارګران</h3>
        <p style="color:#666;font-size:12px;margin:0 0 8px">برای دیدن دفتر حساب هر کارګر، روی نامش کلیک کن</p>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>نام</th><th>تماس</th><th>وظیفه</th><th>معاش</th><th>باقی معاش</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-workers"></tbody>
        </table></div>
      </div>
    </div>

    <!-- WORKER LEDGER -->
    <div id="workerLedger" class="page">
      <div class="card">
        <div class="ledger-head">
          <div><b id="wklName"></b><br><span style="font-size:12px;color:#666" id="wklPos"></span></div>
          <div><span style="font-size:12px">باقی مانده:</span> <b id="wklBal" style="font-size:18px"></b></div>
          <button class="bb" onclick="backToWorkers()">↩ برگشت</button>
        </div>
        <form onsubmit="addWorkerTx(event)">
          <input type="hidden" name="workerId" id="wklId">
          <div class="grid">
            <input name="date" type="date" required>
            <select name="type" required>
              <option value="salary">معاش (طلب کارګر)</option>
              <option value="advance">پیشکی (پول دادیم)</option>
              <option value="payment">تصفیه معاش (پول دادیم)</option>
              <option value="bonus">بونس (طلب کارګر)</option>
              <option value="fine">جریمه (طلب ما)</option>
            </select>
            <input name="amount" type="number" step="any" placeholder="مقدار" required>
            <input name="note" placeholder="یادداشت">
            <button type="submit">ثبت تراکنش</button>
          </div>
        </form>
      </div>
      <div class="card"><h3>📒 دفتر حساب کارګر</h3>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>تاریخ</th><th>نوعیت</th><th>طلب کارګر</th><th>طلب ما</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-wktx"></tbody>
        </table></div>
      </div>
    </div>

    <!-- SALESMEN -->
    <div id="salesmen" class="page">
      <div class="card">
        <h3><span id="smTitle">➕ سیل مین جدید</span></h3>
        <form onsubmit="saveSimple(event,'salesmen',['name','phone','commission','note'])" id="smForm">
          <div class="grid">
            <input name="name" placeholder="نام سیل مین" required>
            <input name="phone" placeholder="شماره تماس">
            <input name="commission" type="number" step="any" placeholder="فیصدی کمیشن">
            <input name="note" placeholder="یادداشت">
            <button type="submit" id="smBtn">ثبت</button>
            <button type="button" class="cancel" id="smCancel" onclick="cancelEdit('salesmen')" style="display:none">لغو</button>
          </div>
        </form>
      </div>
      <div class="card"><h3>🚗 لیست سیل مینان</h3>
        <p style="color:#666;font-size:12px;margin:0 0 8px">برای دیدن دفتر حساب، روی نام کلیک کن</p>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>نام</th><th>تماس</th><th>کمیشن ٪</th><th>طلب از او</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-salesmen"></tbody>
        </table></div>
      </div>
    </div>

    <!-- SALESMAN LEDGER -->
    <div id="salesmanLedger" class="page">
      <div class="card">
        <div class="ledger-head">
          <div><b id="smlName"></b><br><span style="font-size:12px;color:#666" id="smlPh"></span></div>
          <div><span style="font-size:12px">باقی:</span> <b id="smlBal" style="font-size:18px"></b></div>
          <button class="bb" onclick="backToSalesmen()">↩ برگشت</button>
        </div>
        <form onsubmit="addSalesmanTx(event)">
          <input type="hidden" name="salesmanId" id="smlId">
          <div class="grid">
            <input name="date" type="date" required>
            <select name="type" required>
              <option value="sale">خرڅلاو (طلب ما از او)</option>
              <option value="received">پول رسیده (او داد)</option>
              <option value="commission">کمیشن (طلب او از ما)</option>
              <option value="paid">پرداخت کمیشن (دادیم)</option>
              <option value="advance">پیشکی (دادیم)</option>
            </select>
            <input name="amount" type="number" step="any" placeholder="مقدار" required>
            <input name="note" placeholder="یادداشت">
            <button type="submit">ثبت تراکنش</button>
          </div>
        </form>
      </div>
      <div class="card"><h3>📒 دفتر حساب سیل مین</h3>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>تاریخ</th><th>نوعیت</th><th>طلب ما از او</th><th>طلب او از ما</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-smtx"></tbody>
        </table></div>
      </div>
    </div>

    <!-- LOANS -->
    <div id="loans" class="page">
      <div class="card">
        <h3><span id="lnTitle">➕ ثبت قرض جدید</span></h3>
        <form onsubmit="saveSimple(event,'loans',['date','person','type','amount','paid','note'])" id="lnForm">
          <div class="grid">
            <input name="date" type="date" required>
            <input name="person" placeholder="نام شخص" required>
            <select name="type">
              <option value="given">ما دادیم (طلب ما)</option>
              <option value="taken">ما گرفتیم (بدهی ما)</option>
            </select>
            <input name="amount" type="number" step="any" placeholder="مقدار قرض" required>
            <input name="paid" type="number" step="any" placeholder="تصفیه شده" value="0">
            <input name="note" placeholder="یادداشت">
            <button type="submit" id="lnBtn">ثبت</button>
            <button type="button" class="cancel" id="lnCancel" onclick="cancelEdit('loans')" style="display:none">لغو</button>
          </div>
        </form>
      </div>
      <div class="card"><h3>💵 لیست قرضونه</h3>
        <div class="tw"><table>
          <thead><tr><th>#</th><th>تاریخ</th><th>شخص</th><th>نوعیت</th><th>مقدار</th><th>تصفیه</th><th>باقی</th><th>یادداشت</th><th>عملیات</th></tr></thead>
          <tbody id="tb-loans"></tbody>
        </table></div>
      </div>
    </div>

    <!-- REPORTS -->
    <div id="reports" class="page">
      <div class="card"><h3>📈 فلتر تاریخ</h3>
        <div class="grid">
          <input type="date" id="rFrom">
          <input type="date" id="rTo">
          <button onclick="renderReports()">نمایش</button>
          <button class="cancel" onclick="clearDateFilter()">پاک کردن فلتر</button>
        </div>
      </div>
      <div class="card"><h3>📊 خلاصه دوره</h3><div id="rSummary"></div></div>
      <div class="card"><h3>📦 راپور هر جنس</h3><div class="tw"><table id="rItems"></table></div></div>
      <div class="card"><h3>👷 راپور کارګران</h3><div class="tw"><table id="rWorkers"></table></div></div>
      <div class="card"><h3>🚗 راپور سیل مینان</h3><div class="tw"><table id="rSalesmen"></table></div></div>
    </div>

    <!-- USERS -->
    <div id="users" class="page">
      <div class="card"><h3>➕ کاربر جدید</h3>
        <form onsubmit="addUser(event)">
          <div class="grid">
            <input name="username" placeholder="نام کاربری" required>
            <input name="password" type="password" placeholder="رمز" required>
            <select name="role"><option value="user">کاربر عادی</option><option value="admin">ادمین</option></select>
            <button type="submit">ثبت</button>
          </div>
        </form>
      </div>
      <div class="card"><h3>👥 کاربران</h3>
        <div class="tw"><table><thead><tr><th>ID</th><th>نام</th><th>نقش</th><th>عملیات</th></tr></thead><tbody id="tb-users"></tbody></table></div>
      </div>
    </div>

  </main>
</div>

<div id="toast" style="position:fixed;bottom:20px;left:50%;transform:translateX(-50%) translateY(100px);background:#27ae60;color:#fff;padding:12px 22px;border-radius:8px;font-weight:bold;box-shadow:0 4px 20px rgba(0,0,0,.25);transition:transform .3s;z-index:999"></div>

<script>
const KEY='factory_full_v1';
let data={users:[{id:1,username:'admin',password:'admin123',role:'admin'}],
imports:[],sales:[],expenses:[],incomes:[],workers:[],workerTx:[],salesmen:[],salesmanTx:[],loans:[],
currentUser:null,nextId:{imports:1,sales:1,expenses:1,incomes:1,workers:1,workerTx:1,salesmen:1,salesmanTx:1,loans:1,users:2}};
let editing={section:null,id:null};

function save(){localStorage.setItem(KEY,JSON.stringify(data))}
function load(){const s=localStorage.getItem(KEY);if(s){try{data=JSON.parse(s)}catch(e){}}if(!data.nextId)data.nextId={imports:1,sales:1,expenses:1,incomes:1,workers:1,workerTx:1,salesmen:1,salesmanTx:1,loans:1,users:2};if(!data.users||!data.users.length)data.users=[{id:1,username:'admin',password:'admin123',role:'admin'}]}
function uid(t){const id=data.nextId[t]||1;data.nextId[t]=id+1;return id}
function fmt(n){n=Number(n||0);return n.toLocaleString('fa-AF',{maximumFractionDigits:2})}
function money(n){return fmt(n)+' ؋'}
function today(){return new Date().toISOString().slice(0,10)}
function $(id){return document.getElementById(id)}
function toast(msg,err){const t=$('toast');t.textContent=msg;t.style.background=err?'#e74c3c':'#27ae60';t.style.transform='translateX(-50%) translateY(0)';setTimeout(()=>t.style.transform='translateX(-50%) translateY(100px)',2000)}

function doLogin(){const u=$('lgUser').value.trim(),p=$('lgPass').value;const user=data.users.find(x=>x.username===u&&x.password===p);if(!user){$('lgErr').textContent='نام یا رمز غلط است';return}data.currentUser={id:user.id,username:user.username,role:user.role};save();startApp()}
function doLogout(){data.currentUser=null;save();$('appView').style.display='none';$('loginView').style.display='flex';$('lgUser').value='';$('lgPass').value=''}

function startApp(){
  $('loginView').style.display='none';$('appView').style.display='block';
  const u=data.currentUser;
  $('currentUser').textContent='👤 '+u.username+(u.role==='admin'?' (ادمین)':'');
  $('usersBtn').style.display=u.role==='admin'?'':'none';
  setAllDates();renderAll();showPage('dashboard',document.querySelector('nav button[data-p=dashboard]'));
}
function setAllDates(){const t=today();document.querySelectorAll('input[type=date]').forEach(i=>{if(!i.value)i.value=t})}

function showPage(id,btn){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  const el=$(id);if(el)el.classList.add('active');
  document.querySelectorAll('nav button').forEach(b=>b.classList.remove('active'));
  if(btn)btn.classList.add('active');
  renderAll();
}
function renderAll(){
  renderDashboard();renderImports();renderSales();renderWarehouse();
  renderExpenses();renderIncomes();renderWorkers();renderSalesmen();renderLoans();
  if(data.currentUser&&data.currentUser.role==='admin')renderUsers();
  renderReports();
}

/* ---------- DASHBOARD ---------- */
function renderDashboard(){
  const impVal=data.imports.reduce((s,x)=>s+(+x.total||0),0);
  const salVal=data.sales.reduce((s,x)=>s+(+x.total||0),0);
  const expVal=data.expenses.reduce((s,x)=>s+(+x.amount||0),0);
  const incVal=data.incomes.reduce((s,x)=>s+(+x.amount||0),0);

  // warehouse value = sum of remaining kg × avg purchase rate per item
  let whVal=0;
  const items=warehouseByItem();
  items.forEach(it=>{whVal+=it.remainingKg*(it.avgBuyRate||0)});

  const profit=salVal-impVal-expVal+incVal;

  const received=data.sales.reduce((s,x)=>s+(+x.paid||0),0)+data.incomes.reduce((s,x)=>s+(+x.amount||0),0);
  const paid=data.imports.reduce((s,x)=>s+(+x.paid||0),0)+data.expenses.reduce((s,x)=>s+(+x.amount||0),0);

  const recv=data.sales.reduce((s,x)=>s+(+x.remaining||0),0);
  const pay=data.imports.reduce((s,x)=>s+(+x.remaining||0),0);

  // worker balances: positive = we owe worker
  let wkOwe=0;
  data.workers.forEach(w=>{const b=workerBalance(w.id);if(b>0)wkOwe+=b});

  // salesman balances: positive = salesman owes us
  let smOwe=0;
  data.salesmen.forEach(s=>{const b=salesmanBalance(s.id);if(b>0)smOwe+=b});

  $('dImp').textContent=money(impVal);
  $('dSal').textContent=money(salVal);
  $('dWh').textContent=money(whVal);
  $('dExp').textContent=money(expVal);
  $('dInc').textContent=money(incVal);
  $('dProfit').textContent=money(profit);
  $('dProfit').style.color=profit>=0?'#27ae60':'#c0392b';
  $('dIn').textContent=money(received);
  $('dOut').textContent=money(paid);
  $('dCash').textContent=money(received-paid);
  $('dRecv').textContent=money(recv);
  $('dPay').textContent=money(pay);
  $('dWkBal').textContent=money(wkOwe);
  $('dSmBal').textContent=money(smOwe);
}

/* ---------- IMPORTS ---------- */
function calcImp(){
  const f=$('impForm');const kg=+f.kg.value||0,rate=+f.rate.value||0,paid=+f.paid.value||0;
  f.total.value=(kg*rate).toFixed(2);f.remaining.value=(kg*rate-paid).toFixed(2);
}
function saveImport(e){
  e.preventDefault();const f=e.target;
  const rec={id:editing.id||uid('imports'),date:f.date.value,supplier:f.supplier.value,item:f.item.value,vehicle:f.vehicle.value,
    kg:+f.kg.value||0,rate:+f.rate.value||0,total:+f.total.value||0,paid:+f.paid.value||0,remaining:+f.remaining.value||0,note:f.note.value};
  if(editing.id){const i=data.imports.findIndex(x=>x.id===editing.id);data.imports[i]=rec;cancelEdit('imports');toast('✅ به‌روز شد')}
  else{data.imports.unshift(rec);toast('✅ ثبت شد')}
  save();f.reset();setAllDates();renderAll();
}
function renderImports(){
  const tb=$('tb-imports');const rows=data.imports;
  $('impSum').innerHTML='<span style="font-size:12px;color:#666">مجموع: <b>'+money(rows.reduce((s,x)=>s+(+x.total||0),0))+'</b></span>';
  if(!rows.length){tb.innerHTML='<tr><td colspan="12" class="empty">هیچ وارداتی ثبت نشده</td></tr>';return}
  tb.innerHTML=rows.map((r,i)=>`<tr>
    <td>${i+1}</td><td>${r.date||''}</td><td>${r.supplier||''}</td><td>${r.item||''}</td><td>${r.vehicle||'-'}</td>
    <td>${fmt(r.kg)}</td><td>${fmt(r.rate)}</td><td><b>${fmt(r.total)}</b></td><td>${fmt(r.paid)}</td>
    <td class="${r.remaining>0?'negative':'positive'}">${fmt(r.remaining)}</td><td>${r.note||'-'}</td>
    <td><button class="edt" onclick="editRow('imports',${r.id})">✏️</button><button class="del" onclick="delRow('imports',${r.id})">🗑</button></td>
  </tr>`).join('');
}

/* ---------- SALES ---------- */
function calcSal(){
  const f=$('salForm');const kg=+f.kg.value||0,rate=+f.rate.value||0,paid=+f.paid.value||0;
  f.total.value=(kg*rate).toFixed(2);f.remaining.value=(kg*rate-paid).toFixed(2);
}
function saveSale(e){
  e.preventDefault();const f=e.target;
  const rec={id:editing.id||uid('sales'),date:f.date.value,customer:f.customer.value,salesman:f.salesman.value,item:f.item.value,
    kg:+f.kg.value||0,rate:+f.rate.value||0,total:+f.total.value||0,paid:+f.paid.value||0,remaining:+f.remaining.value||0,note:f.note.value};
  if(editing.id){const i=data.sales.findIndex(x=>x.id===editing.id);data.sales[i]=rec;cancelEdit('sales');toast('✅ به‌روز شد')}
  else{data.sales.unshift(rec);toast('✅ ثبت شد')}
  save();f.reset();setAllDates();renderAll();
}
function renderSales(){
  const tb=$('tb-sales');const rows=data.sales;
  $('salSum').innerHTML='<span style="font-size:12px;color:#666">مجموع: <b>'+money(rows.reduce((s,x)=>s+(+x.total||0),0))+'</b></span>';
  if(!rows.length){tb.innerHTML='<tr><td colspan="12" class="empty">هیچ خرڅلاو ثبت نشده</td></tr>';return}
  tb.innerHTML=rows.map((r,i)=>`<tr>
    <td>${i+1}</td><td>${r.date||''}</td><td>${r.customer||''}</td><td>${r.salesman||'-'}</td><td>${r.item||''}</td>
    <td>${fmt(r.kg)}</td><td>${fmt(r.rate)}</td><td><b>${fmt(r.total)}</b></td><td>${fmt(r.paid)}</td>
    <td class="${r.remaining>0?'negative':'positive'}">${fmt(r.remaining)}</td><td>${r.note||'-'}</td>
    <td><button class="edt" onclick="editRow('sales',${r.id})">✏️</button><button class="del" onclick="delRow('sales',${r.id})">🗑</button></td>
  </tr>`).join('');
}

/* ---------- WAREHOUSE ---------- */
function warehouseByItem(){
  const map={};
  data.imports.forEach(r=>{
    const k=(r.item||'').trim();if(!k)return;
    if(!map[k])map[k]={item:k,inKg:0,inVal:0,outKg:0,outVal:0};
    map[k].inKg+=+r.kg||0;map[k].inVal+=+r.total||0;
  });
  data.sales.forEach(r=>{
    const k=(r.item||'').trim();if(!k)return;
    if(!map[k])map[k]={item:k,inKg:0,inVal:0,outKg:0,outVal:0};
    map[k].outKg+=+r.kg||0;map[k].outVal+=+r.total||0;
  });
  return Object.values(map).map(m=>({
    ...m,
    remainingKg:m.inKg-m.outKg,
    avgBuyRate:m.inKg>0?m.inVal/m.inKg:0,
    avgSellRate:m.outKg>0?m.outVal/m.outKg:0
  }));
}
function renderWarehouse(){
  const tb=$('tb-warehouse');const items=warehouseByItem();
  if(!items.length){tb.innerHTML='<tr><td colspan="7" class="empty">هیچ موجودی نیست</td></tr>';return}
  tb.innerHTML=items.map(it=>{
    const buyVal=it.remainingKg*it.avgBuyRate;
    const sellVal=it.remainingKg*it.avgSellRate;
    return `<tr>
      <td><b>${it.item}</b></td>
      <td>${fmt(it.inKg)}</td>
      <td>${fmt(it.outKg)}</td>
      <td class="${it.remainingKg<0?'negative':'positive'}"><b>${fmt(it.remainingKg)}</b></td>
      <td>${fmt(buyVal)}</td>
      <td>${fmt(sellVal)}</td>
      <td>${fmt(sellVal-buyVal)}</td>
    </tr>`;
  }).join('');
}

/* ---------- EXPENSES / INCOMES / LOANS ---------- */
function saveSimple(e,section,fields){
  e.preventDefault();const f=e.target;
  const rec={id:editing.id||uid(section)};
  fields.forEach(k=>{rec[k]=['amount','paid','salary','commission'].includes(k)?(+f[k].value||0):f[k].value});
  if(editing.id){const i=data[section].findIndex(x=>x.id===editing.id);data[section][i]=rec;cancelEdit(section);toast('✅ به‌روز شد')}
  else{data[section].unshift(rec);toast('✅ ثبت شد')}
  save();f.reset();setAllDates();renderAll();
}
function renderExpenses(){
  const tb=$('tb-expenses');const rows=data.expenses;
  $('expSum').innerHTML='<span style="font-size:12px;color:#666">مجموع: <b>'+money(rows.reduce((s,x)=>s+(+x.amount||0),0))+'</b></span>';
  if(!rows.length){tb.innerHTML='<tr><td colspan="7" class="empty">هیچ مصرفی نیست</td></tr>';return}
  tb.innerHTML=rows.map((r,i)=>`<tr><td>${i+1}</td><td>${r.date||''}</td><td>${r.category||''}</td><td>${r.descr||''}</td><td class="negative">${fmt(r.amount)}</td><td>${r.note||'-'}</td>
    <td><button class="edt" onclick="editRow('expenses',${r.id})">✏️</button><button class="del" onclick="delRow('expenses',${r.id})">🗑</button></td></tr>`).join('');
}
function renderIncomes(){
  const tb=$('tb-incomes');const rows=data.incomes;
  $('incSum').innerHTML='<span style="font-size:12px;color:#666">مجموع: <b>'+money(rows.reduce((s,x)=>s+(+x.amount||0),0))+'</b></span>';
  if(!rows.length){tb.innerHTML='<tr><td colspan="6" class="empty">هیچ عایدی نیست</td></tr>';return}
  tb.innerHTML=rows.map((r,i)=>`<tr><td>${i+1}</td><td>${r.date||''}</td><td>${r.source||''}</td><td class="positive">${fmt(r.amount)}</td><td>${r.note||'-'}</td>
    <td><button class="edt" onclick="editRow('incomes',${r.id})">✏️</button><button class="del" onclick="delRow('incomes',${r.id})">🗑</button></td></tr>`).join('');
}
function renderLoans(){
  const tb=$('tb-loans');const rows=data.loans;
  if(!rows.length){tb.innerHTML='<tr><td colspan="9" class="empty">هیچ قرضی نیست</td></tr>';return}
  tb.innerHTML=rows.map((r,i)=>{
    const rem=(+r.amount||0)-(+r.paid||0);
    const isGiven=r.type==='given';
    return `<tr>
      <td>${i+1}</td><td>${r.date||''}</td><td>${r.person||''}</td>
      <td class="${isGiven?'positive':'negative'}">${isGiven?'ما دادیم':'ما گرفتیم'}</td>
      <td>${fmt(r.amount)}</td><td>${fmt(r.paid)}</td><td><b>${fmt(rem)}</b></td><td>${r.note||'-'}</td>
      <td><button class="edt" onclick="editRow('loans',${r.id})">✏️</button><button class="del" onclick="delRow('loans',${r.id})">🗑</button></td>
    </tr>`;
  }).join('');
}

/* ---------- WORKERS ---------- */
function workerBalance(wid){
  let b=0;
  data.workerTx.filter(t=>t.workerId===wid).forEach(t=>{
    const a=+t.amount||0;
    if(t.type==='salary'||t.type==='bonus')b+=a; // we owe worker
    else if(t.type==='advance'||t.type==='payment')b-=a; // we paid worker
    else if(t.type==='fine')b-=a; // worker owes us (reduce our debt)
  });
  return b;
}
function renderWorkers(){
  const tb=$('tb-workers');const rows=data.workers;
  if(!rows.length){tb.innerHTML='<tr><td colspan="8" class="empty">هیچ کارګری نیست</td></tr>';return}
  tb.innerHTML=rows.map((r,i)=>{
    const bal=workerBalance(r.id);
    const cls=bal>0?'negative':bal<0?'positive':'';
    return `<tr>
      <td>${i+1}</td>
      <td><a href="javascript:void(0)" onclick="openWorker(${r.id})" style="color:#2980b9;font-weight:bold;text-decoration:none">${r.name}</a></td>
      <td>${r.phone||'-'}</td><td>${r.position||'-'}</td><td>${fmt(r.salary)}</td>
      <td class="${cls}"><b>${fmt(bal)}</b> ${bal>0?'(طلب او)':bal<0?'(طلب ما)':''}</td>
      <td>${r.note||'-'}</td>
      <td><button class="edt" onclick="editRow('workers',${r.id})">✏️</button><button class="del" onclick="delRow('workers',${r.id})">🗑</button></td>
    </tr>`;
  }).join('');
}
let currentWorkerId=null;
function openWorker(id){
  currentWorkerId=id;const w=data.workers.find(x=>x.id===id);if(!w)return;
  $('wklName').textContent='👷 '+w.name;
  $('wklPos').textContent=(w.position||'')+' • معاش ماهانه: '+money(w.salary||0);
  $('wklId').value=id;
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  $('workerLedger').classList.add('active');
  document.querySelectorAll('nav button').forEach(b=>b.classList.remove('active'));
  renderWorkerLedger();
}
function backToWorkers(){showPage('workers',document.querySelector('nav button[data-p=workers]'))}
function addWorkerTx(e){
  e.preventDefault();const f=e.target;
  data.workerTx.unshift({id:uid('workerTx'),workerId:+f.workerId.value,date:f.date.value,type:f.type.value,amount:+f.amount.value||0,note:f.note.value});
  save();f.reset();f.date.value=today();f.workerId.value=currentWorkerId;
  renderWorkerLedger();renderWorkers();renderDashboard();toast('✅ تراکنش ثبت شد');
}
function renderWorkerLedger(){
  const tb=$('tb-wktx');const w=data.workers.find(x=>x.id===currentWorkerId);
  if(!w)return;
  const bal=workerBalance(w.id);
  $('wklBal').textContent=money(Math.abs(bal));
  $('wklBal').style.color=bal>0?'#c0392b':bal<0?'#27ae60':'#333';
  const rows=data.workerTx.filter(t=>t.workerId===w.id);
  if(!rows.length){tb.innerHTML='<tr><td colspan="7" class="empty">هیچ تراکنشی نیست</td></tr>';return}
  tb.innerHTML=rows.map((t,i)=>{
    const a=+t.amount||0;let owe=0,give=0;
    if(t.type==='salary'||t.type==='bonus')owe=a;
    else if(t.type==='advance'||t.type==='payment'||t.type==='fine')give=a;
    const names={salary:'معاش',bonus:'بونس',advance:'پیشکی',payment:'تصفیه معاش',fine:'جریمه'};
    return `<tr><td>${i+1}</td><td>${t.date}</td><td>${names[t.type]||t.type}</td>
      <td class="negative">${owe?fmt(owe):'-'}</td>
      <td class="positive">${give?fmt(give):'-'}</td>
      <td>${t.note||'-'}</td>
      <td><button class="del" onclick="delWorkerTx(${t.id})">🗑</button></td></tr>`;
  }).join('');
}
function delWorkerTx(id){
  if(!confirm('مطمئن هستی؟'))return;
  data.workerTx=data.workerTx.filter(x=>x.id!==id);save();renderWorkerLedger();renderWorkers();renderDashboard();
}

/* ---------- SALESMEN ---------- */
function salesmanBalance(sid){
  let b=0;
  data.salesmanTx.filter(t=>t.salesmanId===sid).forEach(t=>{
    const a=+t.amount||0;
    if(t.type==='sale')b+=a; // salesman owes us
    else if(t.type==='received')b-=a; // he gave us money
    else if(t.type==='commission')b-=a; // we owe him (reduce his debt to us)
    else if(t.type==='paid')b+=a; // we paid commission (he owes us more? no—we paid him so his debt to us decreases... actually it's an extra)
    else if(t.type==='advance')b+=a; // we gave him money, he owes us
  });
  return b;
}
function renderSalesmen(){
  const tb=$('tb-salesmen');const rows=data.salesmen;
  if(!rows.length){tb.innerHTML='<tr><td colspan="7" class="empty">هیچ سیل مینی نیست</td></tr>';return}
  tb.innerHTML=rows.map((r,i)=>{
    const bal=salesmanBalance(r.id);
    return `<tr>
      <td>${i+1}</td>
      <td><a href="javascript:void(0)" onclick="openSalesman(${r.id})" style="color:#2980b9;font-weight:bold;text-decoration:none">${r.name}</a></td>
      <td>${r.phone||'-'}</td><td>${fmt(r.commission)}%</td>
      <td class="${bal>0?'negative':bal<0?'positive':''}"><b>${fmt(bal)}</b> ${bal>0?'(طلب ما)':bal<0?'(طلب او)':''}</td>
      <td>${r.note||'-'}</td>
      <td><button class="edt" onclick="editRow('salesmen',${r.id})">✏️</button><button class="del" onclick="delRow('salesmen',${r.id})">🗑</button></td>
    </tr>`;
  }).join('');
}
let currentSalesmanId=null;
function openSalesman(id){
  currentSalesmanId=id;const s=data.salesmen.find(x=>x.id===id);if(!s)return;
  $('smlName').textContent='🚗 '+s.name;
  $('smlPh').textContent=(s.phone||'')+' • کمیشن: '+(s.commission||0)+'%';
  $('smlId').value=id;
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  $('salesmanLedger').classList.add('active');
  document.querySelectorAll('nav button').forEach(b=>b.classList.remove('active'));
  renderSalesmanLedger();
}
function backToSalesmen(){showPage('salesmen',document.querySelector('nav button[data-p=salesmen]'))}
function addSalesmanTx(e){
  e.preventDefault();const f=e.target;
  data.salesmanTx.unshift({id:uid('salesmanTx'),salesmanId:+f.salesmanId.value,date:f.date.value,type:f.type.value,amount:+f.amount.value||0,note:f.note.value});
  save();f.reset();f.date.value=today();f.salesmanId.value=currentSalesmanId;
  renderSalesmanLedger();renderSalesmen();renderDashboard();toast('✅ تراکنش ثبت شد');
}
function renderSalesmanLedger(){
  const tb=$('tb-smtx');const s=data.salesmen.find(x=>x.id===currentSalesmanId);
  if(!s)return;
  const bal=salesmanBalance(s.id);
  $('smlBal').textContent=money(Math.abs(bal));
  $('smlBal').style.color=bal>0?'#c0392b':bal<0?'#27ae60':'#333';
  const rows=data.salesmanTx.filter(t=>t.salesmanId===s.id);
  if(!rows.length){tb.innerHTML='<tr><td colspan="7" class="empty">هیچ تراکنشی نیست</td></tr>';return}
  const names={sale:'خرڅلاو',received:'پول رسیده',commission:'کمیشن',paid:'پرداخت کمیشن',advance:'پیشکی'};
  tb.innerHTML=rows.map((t,i)=>{
    const a=+t.amount||0;let owe=0,us=0;
    if(t.type==='sale'||t.type==='paid'||t.type==='advance')owe=a; // he owes us
    else us=a; // we owe him
    return `<tr><td>${i+1}</td><td>${t.date}</td><td>${names[t.type]||t.type}</td>
      <td class="negative">${owe?fmt(owe):'-'}</td>
      <td class="positive">${us?fmt(us):'-'}</td>
      <td>${t.note||'-'}</td>
      <td><button class="del" onclick="delSalesmanTx(${t.id})">🗑</button></td></tr>`;
  }).join('');
}
function delSalesmanTx(id){
  if(!confirm('مطمئن هستی؟'))return;
  data.salesmanTx=data.salesmanTx.filter(x=>x.id!==id);save();renderSalesmanLedger();renderSalesmen();renderDashboard();
}

/* ---------- EDIT / DELETE ---------- */
function editRow(section,id){
  const row=data[section].find(x=>x.id===id);if(!row)return;
  editing.section=section;editing.id=id;
  const formMap={imports:'impForm',sales:'salForm',expenses:'expForm',incomes:'incForm',workers:'wkForm',salesmen:'smForm',loans:'lnForm'};
  const titleMap={imports:'impTitle',sales:'salTitle',expenses:'expTitle',incomes:'incTitle',workers:'wkTitle',salesmen:'smTitle',loans:'lnTitle'};
  const btnMap={imports:'impBtn',sales:'salBtn',expenses:'expBtn',incomes:'incBtn',workers:'wkBtn',salesmen:'smBtn',loans:'lnBtn'};
  const cancelMap={imports:'impCancel',sales:'salCancel',expenses:'expCancel',incomes:'incCancel',workers:'wkCancel',salesmen:'smCancel',loans:'lnCancel'};
  const f=$(formMap[section]);
  Object.keys(row).forEach(k=>{if(f[k]&&k!=='id')f[k].value=row[k]});
  $(titleMap[section]).textContent='✏️ ویرایش';
  $(btnMap[section]).textContent='به‌روزرسانی';
  $(btnMap[section]).classList.add('update');
  $(cancelMap[section]).style.display='';
  f.scrollIntoView({behavior:'smooth',block:'center'});
}
function cancelEdit(section){
  editing={section:null,id:null};
  const formMap={imports:'impForm',sales:'salForm',expenses:'expForm',incomes:'incForm',workers:'wkForm',salesmen:'smForm',loans:'lnForm'};
  const titleMap={imports:'impTitle',sales:'salTitle',expenses:'expTitle',incomes:'incTitle',workers:'wkTitle',salesmen:'smTitle',loans:'lnTitle'};
  const btnMap={imports:'impBtn',sales:'salBtn',expenses:'expBtn',incomes:'incBtn',workers:'wkBtn',salesmen:'smBtn',loans:'lnBtn'};
  const cancelMap={imports:'impCancel',sales:'salCancel',expenses:'expCancel',incomes:'incCancel',workers:'wkCancel',salesmen:'smCancel',loans:'lnCancel'};
  const titles={imports:'➕ ثبت واردات جدید',sales:'➕ ثبت خرڅلاو جدید',expenses:'➕ ثبت مصرف جدید',incomes:'➕ ثبت عاید جدید',workers:'➕ کارګر جدید',salesmen:'➕ سیل مین جدید',loans:'➕ ثبت قرض جدید'};
  $(formMap[section]).reset();
  $(titleMap[section]).textContent=titles[section];
  $(btnMap[section]).textContent='ثبت';
  $(btnMap[section]).classList.remove('update');
  $(cancelMap[section]).style.display='none';
  setAllDates();
}
function delRow(section,id){
  if(!confirm('آیا مطمئن هستی؟ این ریکارډ حذف می‌شود.'))return;
  if(section==='workers'){data.workerTx=data.workerTx.filter(t=>t.workerId!==id)}
  if(section==='salesmen'){data.salesmanTx=data.salesmanTx.filter(t=>t.salesmanId!==id)}
  data[section]=data[section].filter(x=>x.id!==id);
  save();renderAll();toast('🗑 حذف شد');
}

/* ---------- USERS ---------- */
function renderUsers(){
  const tb=$('tb-users');if(!tb)return;
  tb.innerHTML=data.users.map(u=>`<tr><td>${u.id}</td><td>${u.username}</td><td>${u.role}</td>
    <td>${u.id===data.currentUser.id?'—':`<button class="del" onclick="delUser(${u.id})">🗑</button>`}</td></tr>`).join('');
}
function addUser(e){
  e.preventDefault();const f=e.target;const un=f.username.value.trim();
  if(data.users.find(u=>u.username===un)){toast('این نام موجود است',true);return}
  data.users.push({id:uid('users'),username:un,password:f.password.value,role:f.role.value});
  save();f.reset();renderUsers();toast('✅ کاربر ساخته شد');
}
function delUser(id){if(!confirm('مطمئن هستی؟'))return;data.users=data.users.filter(u=>u.id!==id);save();renderUsers()}

/* ---------- REPORTS ---------- */
function inRange(d){
  const from=$('rFrom').value,to=$('rTo').value;
  if(from&&d<from)return false;
  if(to&&d>to)return false;
  return true;
}
function clearDateFilter(){$('rFrom').value='';$('rTo').value='';renderReports()}
function renderReports(){
  const imp=data.imports.filter(r=>inRange(r.date));
  const sal=data.sales.filter(r=>inRange(r.date));
  const exp=data.expenses.filter(r=>inRange(r.date));
  const inc=data.incomes.filter(r=>inRange(r.date));
  const impVal=imp.reduce((s,x)=>s+(+x.total||0),0);
  const salVal=sal.reduce((s,x)=>s+(+x.total||0),0);
  const expVal=exp.reduce((s,x)=>s+(+x.amount||0),0);
  const incVal=inc.reduce((s,x)=>s+(+x.amount||0),0);
  const profit=salVal-impVal-expVal+incVal;
  const impKg=imp.reduce((s,x)=>s+(+x.kg||0),0);
  const salKg=sal.reduce((s,x)=>s+(+x.kg||0),0);

  $('rSummary').innerHTML=`<div class="grid">
    <div class="stat blue"><span>واردات</span><b>${money(impVal)}</b></div>
    <div class="stat green"><span>خرڅلاو</span><b>${money(salVal)}</b></div>
    <div class="stat red"><span>مصارف</span><b>${money(expVal)}</b></div>
    <div class="stat green"><span>عاید</span><b>${money(incVal)}</b></div>
    <div class="stat ${profit>=0?'green':'red'}"><span>ګټه</span><b>${money(profit)}</b></div>
    <div class="stat"><span>کیلو وارد</span><b>${fmt(impKg)}</b></div>
    <div class="stat"><span>کیلو خرڅ</span><b>${fmt(salKg)}</b></div>
  </div>`;

  // items
  const itemMap={};
  imp.forEach(r=>{const k=r.item||'';if(!k)return;if(!itemMap[k])itemMap[k]={in:0,out:0};itemMap[k].in+=+r.kg||0});
  sal.forEach(r=>{const k=r.item||'';if(!k)return;if(!itemMap[k])itemMap[k]={in:0,out:0};itemMap[k].out+=+r.kg||0});
  const items=Object.entries(itemMap);
  $('rItems').innerHTML='<thead><tr><th>جنس</th><th>وارد (کیلو)</th><th>خرڅ (کیلو)</th><th>باقی (کیلو)</th></tr></thead><tbody>'+
    (items.length?items.map(([k,v])=>`<tr><td>${k}</td><td>${fmt(v.in)}</td><td>${fmt(v.out)}</td><td>${fmt(v.in-v.out)}</td></tr>`).join('')
    :'<tr><td colspan="4" class="empty">هیچ</td></tr>')+'</tbody>';

  // workers
  $('rWorkers').innerHTML='<thead><tr><th>کارګر</th><th>معاش+بونس دوره</th><th>پرداخت دوره</th><th>باقی کل</th></tr></thead><tbody>'+
    (data.workers.length?data.workers.map(w=>{
      const txs=data.workerTx.filter(t=>t.workerId===w.id&&inRange(t.date));
      let salary=0,paid=0;
      txs.forEach(t=>{const a=+t.amount||0;if(t.type==='salary'||t.type==='bonus')salary+=a;else paid+=a});
      const bal=workerBalance(w.id);
      return `<tr><td>${w.name}</td><td>${fmt(salary)}</td><td>${fmt(paid)}</td><td class="${bal>0?'negative':'positive'}"><b>${fmt(bal)}</b></td></tr>`;
    }).join(''):'<tr><td colspan="4" class="empty">هیچ</td></tr>')+'</tbody>';

  // salesmen
  $('rSalesmen').innerHTML='<thead><tr><th>سیل مین</th><th>خرڅلاو دوره</th><th>رسیده دوره</th><th>باقی کل</th></tr></thead><tbody>'+
    (data.salesmen.length?data.salesmen.map(s=>{
      const txs=data.salesmanTx.filter(t=>t.salesmanId===s.id&&inRange(t.date));
      let sale=0,recv=0;
      txs.forEach(t=>{const a=+t.amount||0;if(t.type==='sale')sale+=a;if(t.type==='received')recv+=a});
      const bal=salesmanBalance(s.id);
      return `<tr><td>${s.name}</td><td>${fmt(sale)}</td><td>${fmt(recv)}</td><td class="${bal>0?'negative':'positive'}"><b>${fmt(bal)}</b></td></tr>`;
    }).join(''):'<tr><td colspan="4" class="empty">هیچ</td></tr>')+'</tbody>';
}

/* ---------- BACKUP ---------- */
function exportData(){
  const c=JSON.parse(JSON.stringify(data));delete c.currentUser;
  const blob=new Blob([JSON.stringify(c,null,2)],{type:'application/json'});
  const a=document.createElement('a');a.href=URL.createObjectURL(blob);a.download='factory-backup-'+today()+'.json';a.click();
  toast('⬇ بکاپ دانلود شد');
}
function importData(ev){
  const file=ev.target.files[0];if(!file)return;
  const r=new FileReader();
  r.onload=()=>{try{
    const imp=JSON.parse(r.result);
    if(!confirm('داده‌های فعلی جایگزین می‌شود. ادامه؟'))return;
    const cur=data.currentUser;data=imp;data.currentUser=cur;
    if(!data.nextId)data.nextId={imports:1,sales:1,expenses:1,incomes:1,workers:1,workerTx:1,salesmen:1,salesmanTx:1,loans:1,users:2};
    if(!data.users)data.users=[{id:1,username:'admin',password:'admin123',role:'admin'}];
    save();renderAll();toast('✅ بازگردانی شد');
  }catch(e){toast('فایل معتبر نیست',true)}};
  r.readAsText(file);ev.target.value='';
}

/* ---------- START ---------- */
load();
if(data.currentUser)startApp();
$('lgPass').addEventListener('keydown',e=>{if(e.key==='Enter')doLogin()});
$('lgUser').addEventListener('keydown',e=>{if(e.key==='Enter')$('lgPass').focus()});
</script>
</body>
</html>
