/* LICENSE */
.license-page{
  background:
    radial-gradient(circle at 50% 23%,rgba(255,0,30,.20),transparent 28%),
    radial-gradient(circle at 50% 45%,rgba(180,0,20,.12),transparent 35%),
    #050000;
}

.logo-mark{
  border-color:#a80018;
  background:
    radial-gradient(circle at 50% 45%,
      #d10b27 0%,
      #6e0718 25%,
      #250309 55%,
      #050000 75%);
  box-shadow:
    0 0 35px rgba(255,0,40,.35),
    inset 0 0 35px rgba(255,0,40,.25);
  text-shadow:0 0 18px #ff203f;
}

.activation{
  color:#ff304d;
}

.key-input{
  border-color:#70101c;
  background:#160306;
}

.key-input:focus{
  border-color:#ff193d;
  box-shadow:0 0 20px rgba(255,0,40,.20);
}

.activate-btn{
  background:linear-gradient(135deg,#b30925,#ff183d);
  color:#fff;
  box-shadow:0 0 25px rgba(255,0,40,.18);
}

.activate-btn:hover{
  filter:brightness(1.15);
}

.message.ok{
  color:#ff405a;
}

.footer{
  color:#8f7377;
}


/* DASHBOARD */
.dashboard{
  background:
    radial-gradient(circle at 50% 0%,#6d0712 0%,#250207 35%,#090103 75%,#030001 100%);
}

.hex{
  background:#5d0712;
  color:#ff304b;
}

.ready{
  background:#25070c;
  border-color:#671622;
}

.ready span{
  color:#ff2145;
}

.status{
  border-color:#b20d25;
  background:rgba(70,4,12,.70);
  box-shadow:0 0 20px rgba(255,0,35,.08);
}

.status-left,
.status-right{
  color:#ff4b5f;
}

.time-card{
  border-color:#861524;
  background:rgba(42,5,12,.85);
}

.clock{
  background:linear-gradient(135deg,#8e0d20,#4c0610);
  box-shadow:0 0 20px rgba(255,0,40,.15);
}

.active{
  background:#360812;
  color:#ff3154;
}

.game{
  border-color:#861524;
  background:#350811;
}

.game.disabled{
  border-color:#43272b;
  background:#160709;
}

.selected{
  color:#ff3048;
}

.game-info{
  border-color:#64121c;
  background:rgba(25,3,7,.88);
}

.game-icon{
  background:linear-gradient(135deg,#8b1020,#4b0710);
}

.available{
  color:#ff3154;
}

.filter{
  color:#ff3048;
}

.function{
  background:linear-gradient(
    90deg,
    #26070c,
    #120205
  );
  border-color:#50151d;
}

.function-icon{
  background:linear-gradient(135deg,#80101e,#450711);
  color:#ff4055;
}

.switch.on{
  background:linear-gradient(90deg,#8e0d22,#ff1741);
}

.switch.on + .switch-label{
  color:#ff3154;
}

<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DEK MASH - License Activation</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=Kanit:wght@400;500;600;700;800&display=swap');

*{box-sizing:border-box;margin:0;padding:0}
body{
  min-height:100vh;
  background:#000;
  color:#fff;
  font-family:'Kanit',sans-serif;
}
.hidden{display:none!important}

/* LICENSE SCREEN */
.license-page{
  min-height:100vh;
  display:flex;
  justify-content:center;
  align-items:flex-start;
  padding:70px 22px 50px;
  background:
    radial-gradient(circle at 50% 23%,rgba(0,128,170,.16),transparent 28%),
    radial-gradient(circle at 50% 45%,rgba(0,80,110,.08),transparent 35%),
    #000;
}
.license-box{
  width:100%;
  max-width:760px;
  text-align:center;
}
.logo-mark{
  width:260px;
  height:260px;
  margin:0 auto 58px;
  border-radius:58px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:92px;
  font-weight:800;
  color:#dff9ff;
  letter-spacing:-8px;
  border:3px solid #007da3;
  background:
    radial-gradient(circle at 50% 45%,#087ca5 0%,#06344b 25%,#020a10 55%,#000 75%);
  box-shadow:0 0 35px rgba(0,174,230,.28),inset 0 0 35px rgba(0,122,170,.25);
  text-shadow:0 0 18px #20cfff;
}
.brand{
  font-size:58px;
  line-height:1;
  font-weight:800;
  letter-spacing:4px;
}
.activation{
  color:#26c8f2;
  font-size:38px;
  font-weight:600;
  margin-top:28px;
}
.description{
  color:#777b82;
  font-size:23px;
  margin-top:22px;
}
.key-input{
  width:100%;
  height:120px;
  margin-top:58px;
  padding:0 34px;
  border-radius:38px;
  border:3px solid #075f79;
  outline:none;
  background:#17191b;
  color:#fff;
  font-family:'Kanit',sans-serif;
  font-size:30px;
  letter-spacing:2px;
  text-align:left;
  transition:.2s;
}
.key-input:focus{
  border-color:#16bce9;
  box-shadow:0 0 20px rgba(0,194,240,.15);
}
.key-input::placeholder{color:#555a60}
.activate-btn{
  width:100%;
  height:120px;
  margin-top:28px;
  border:0;
  border-radius:38px;
  background:#27839d;
  color:#073747;
  font-family:'Kanit',sans-serif;
  font-size:36px;
  font-weight:700;
  cursor:pointer;
  transition:.2s;
}
.activate-btn:active{transform:scale(.99)}
.activate-btn:hover{filter:brightness(1.08)}
.message{
  min-height:34px;
  margin-top:18px;
  font-size:18px;
  color:#ff5d67;
}
.message.ok{color:#35d5ff}
.footer{
  margin-top:95px;
  color:#85888f;
  font-size:20px;
  letter-spacing:1px;
}

/* DASHBOARD */
.dashboard{
  min-height:100vh;
  background:radial-gradient(circle at 50% 0%,#3b0808 0%,#100304 45%,#050101 100%);
  padding:20px 18px 40px;
}
.app{max-width:780px;margin:auto}
.header{display:flex;justify-content:space-between;align-items:center;margin-bottom:28px}
.logo{font-size:42px;font-weight:800;letter-spacing:2px}
.hex{display:inline-block;background:#4d0808;color:#ff3b3b;padding:7px 18px;border-radius:30px;font-size:20px;margin-left:8px}
.subtitle{color:#8d6d70;font-size:14px;letter-spacing:5px;margin-top:-5px}
.ready{background:#281012;border:1px solid #542226;border-radius:30px;padding:12px 20px;color:#d4bfc1;font-weight:700}
.ready span{color:#ff3155;margin-right:8px}
.status{border:2px solid #a71924;border-radius:24px;padding:18px 24px;background:rgba(55,7,12,.65);display:flex;justify-content:space-between;align-items:center;margin-bottom:28px}
.status-left,.status-right{color:#ff5961;font-weight:700;letter-spacing:2px}
.time-card{border:2px solid #64151d;border-radius:30px;padding:22px;display:flex;align-items:center;background:rgba(30,7,12,.8);margin-bottom:28px}
.clock{width:86px;height:86px;border-radius:25px;background:#70151d;display:flex;justify-content:center;align-items:center;font-size:40px;margin-right:22px}
.time-title{color:#9b8083;font-size:17px}
.time{font-size:32px;font-weight:700}
.active{margin-left:auto;padding:10px 18px;background:#2b1115;color:#ff315c;border-radius:25px;font-weight:700}
.games{display:flex;gap:12px;margin-bottom:30px}
.game{flex:1;border:2px solid #69151d;border-radius:30px;padding:15px 20px;display:flex;align-items:center;background:#280b10;cursor:pointer}
.game.disabled{opacity:.4;border-color:#3b2628;background:#14090a;cursor:not-allowed}
.game img{width:58px;height:58px;border-radius:18px;object-fit:cover;margin-right:15px}
.game-name{font-size:22px;font-weight:700}
.selected{color:#ff3b45;font-size:14px;letter-spacing:2px}
.game-info{border:2px solid #47151b;border-radius:30px;padding:28px;display:flex;align-items:center;background:rgba(17,4,7,.82);margin-bottom:30px}
.game-icon{width:120px;height:120px;border-radius:30px;background:#65121a;padding:12px;margin-right:28px}
.game-icon img{width:100%;height:100%;border-radius:22px;object-fit:cover}
.game-info h1{font-size:36px}
.modules{color:#8b7477;font-weight:700;letter-spacing:2px}
.available{color:#ff315c;margin-top:8px;font-size:18px}
.section-title{display:flex;justify-content:space-between;align-items:center;margin-bottom:18px}
.section-title h2{font-size:28px;letter-spacing:3px}
.section-title p{color:#8b7477}
.filter{font-size:28px;color:#ff3342}
.function{background:linear-gradient(90deg,#18090c,#0d0507);border:2px solid #3c171b;border-radius:30px;padding:20px 24px;display:flex;align-items:center;margin-bottom:18px}
.function-icon{width:72px;height:72px;border-radius:23px;background:#5b1018;display:flex;justify-content:center;align-items:center;color:#ff4652;font-size:32px;margin-right:25px}
.function-text{flex:1}
.function-text h3{font-size:25px}
.function-text p{color:#79696b;font-size:16px}
.switch{width:86px;height:52px;background:#4a4244;border-radius:30px;padding:5px;cursor:pointer;transition:.25s}
.knob{width:42px;height:42px;border-radius:50%;background:#fff;transition:.25s}
.switch.on{background:#b4142c}
.switch.on .knob{transform:translateX(34px)}
.switch-wrap{text-align:center}
.switch-label{color:#686062;font-weight:700;margin-top:3px}
.switch.on + .switch-label{color:#ff315c}

@media(max-width:600px){
  .license-page{padding:55px 16px 35px}
  .logo-mark{width:180px;height:180px;border-radius:42px;font-size:64px;margin-bottom:42px}
  .brand{font-size:39px}
  .activation{font-size:28px;margin-top:18px}
  .description{font-size:16px;margin-top:15px}
  .key-input{height:82px;margin-top:38px;padding:0 22px;border-radius:27px;font-size:20px}
  .activate-btn{height:82px;margin-top:18px;border-radius:27px;font-size:25px}
  .footer{margin-top:55px;font-size:15px}
  .dashboard{padding:15px 10px 30px}
  .logo{font-size:28px}.hex{font-size:14px}.ready{padding:8px 12px;font-size:12px}
  .status{padding:15px;font-size:12px}.time{font-size:23px}.time-card{padding:15px}
  .clock{width:65px;height:65px;font-size:28px}
  .games{flex-direction:column}.game-info{padding:18px}.game-icon{width:85px;height:85px;margin-right:15px}
  .game-info h1{font-size:25px}.function{padding:16px}.function-icon{width:60px;height:60px;margin-right:15px}
  .function-text h3{font-size:19px}.function-text p{font-size:13px}
  .switch{width:70px;height:44px}.knob{width:34px;height:34px}.switch.on .knob{transform:translateX(26px)}
}
</style>
</head>

<body>

<!-- หน้าใส่รหัส -->
<section id="licensePage" class="license-page">
  <div class="license-box">
    <div class="logo-mark">DM</div>

    <div class="brand">DEK MASH</div>
    <div class="activation">License Activation</div>
    <div class="description">กรอกคีย์เพื่อเปิดใช้งานและเชื่อมต่อระบบไฟล์</div>

    <input
      id="licenseKey"
      class="key-input"
      type="text"
      autocomplete="off"
      spellcheck="false"
      placeholder="DEK-XXXX-XXXX-XXXX"
      maxlength="19"
    >

    <button class="activate-btn" onclick="activateLicense()">เปิดใช้งาน</button>
    <div id="message" class="message"></div>

    <div class="footer">🔒 &nbsp; License • Session • Secure API</div>
  </div>
</section>

<!-- หน้าหลักเดิม -->
<section id="dashboard" class="dashboard hidden">
  <div class="app">

    <div class="header">
      <div>
        <div class="logo">DEK MASH <span class="hex">HEX</span></div>
        <div class="subtitle">PATCH CONSOLE</div>
      </div>
      <div class="ready"><span>●</span> READY</div>
    </div>

    <div class="status">
      <div class="status-left">🔒 SECURE</div>
      <b>DEK MASH // CORE</b>
      <div class="status-right">⌁ ONLINE</div>
    </div>

    <div class="time-card">
      <div class="clock">◷</div>
      <div>
        <div class="time-title">เวลาที่คงเหลือ</div>
        <div class="time" id="time">24:00:00</div>
      </div>
      <div class="active">ACTIVE</div>
    </div>

    <div class="games">
      <div class="game">
        <img src="https://placehold.co/100x100/5b1018/ffffff?text=FF" alt="FF">
        <div><div class="game-name">FFTH</div><div class="selected">SELECTED</div></div>
      </div>
      <div class="game disabled">
        <img src="https://placehold.co/100x100/3a2427/ffffff?text=FF" alt="FF">
        <div><div class="game-name">FFMAX</div><div class="selected">SELECT</div></div>
      </div>
    </div>

    <div class="game-info">
      <div class="game-icon">
        <img src="https://placehold.co/200x200/5b1018/ffffff?text=FF" alt="FF">
      </div>
      <div>
        <h1>FREE FIRE</h1>
        <div class="modules">6 FUNCTION MODULES</div>
        <div class="available">✓ พร้อมใช้งาน</div>
      </div>
    </div>

    <div class="section-title">
      <div>
        <h2>FUNCTIONS</h2>
        <p>เปิดหรือปิดฟังก์ชันที่ต้องการ</p>
      </div>
      <div class="filter">☷</div>
    </div>

    <div id="functions"></div>
  </div>
</section>

<script>
/*
  ระบบคีย์ตัวอย่างแบบฝั่งหน้าเว็บ
  คีย์ทดลอง: DEK-2026-MASH-0001
  หมายเหตุ: ระบบนี้เป็น Client-side demo
  หากต้องการความปลอดภัยจริง ควรตรวจสอบ License ผ่าน Backend/API
*/

const VALID_KEYS = [
  "DEK-2026-MASH-0001",
  "DEK-MASH-HEX-2026"
];

const functions = [
  ["▣","กันแชร์จอ","ระบบป้องกันการบันทึกและแชร์จอ"],
  ["⌾","ยิงตัวเข้าหัว FreeFire","ตัวอย่างฟังก์ชัน UI"],
  ["↗","ขยายหัว FreeFire","ตัวอย่างฟังก์ชัน UI"],
  ["◎","ยิงคอเข้าหัว FreeFire","ตัวอย่างฟังก์ชัน UI"],
  ["⌾","มองปืน FreeFire","ตัวอย่างฟังก์ชัน UI"],
  ["◉","ฟังก์ชันเพิ่มเติม","ตัวอย่างฟังก์ชัน UI"]
];

const container = document.getElementById("functions");

functions.forEach(item => {
  const card = document.createElement("div");
  card.className = "function";
  card.innerHTML = `
    <div class="function-icon">${item[0]}</div>
    <div class="function-text">
      <h3>${item[1]}</h3>
      <p>${item[2]}</p>
    </div>
    <div class="switch-wrap">
      <div class="switch" onclick="toggleSwitch(this)">
        <div class="knob"></div>
      </div>
      <div class="switch-label">OFF</div>
    </div>`;
  container.appendChild(card);
});

function toggleSwitch(el){
  el.classList.toggle("on");
  el.nextElementSibling.textContent =
    el.classList.contains("on") ? "ON" : "OFF";
}

function activateLicense(){
  const input = document.getElementById("licenseKey");
  const message = document.getElementById("message");
  const key = input.value.trim().toUpperCase();

  if(!key){
    message.className = "message";
    message.textContent = "กรุณากรอกรหัส License";
    return;
  }

  if(VALID_KEYS.includes(key)){
    localStorage.setItem("dekMashLicense", key);
    message.className = "message ok";
    message.textContent = "✓ เปิดใช้งานสำเร็จ";

    setTimeout(() => {
      document.getElementById("licensePage").classList.add("hidden");
      document.getElementById("dashboard").classList.remove("hidden");
    }, 500);
  }else{
    message.className = "message";
    message.textContent = "✕ รหัสไม่ถูกต้อง กรุณาตรวจสอบอีกครั้ง";
  }
}

document.getElementById("licenseKey").addEventListener("keydown", e => {
  if(e.key === "Enter") activateLicense();
});

let seconds = 24 * 60 * 60;

function updateTime(){
  if(seconds > 0) seconds--;
  const h = String(Math.floor(seconds / 3600)).padStart(2,"0");
  const m = String(Math.floor((seconds % 3600) / 60)).padStart(2,"0");
  const s = String(seconds % 60).padStart(2,"0");
  document.getElementById("time").textContent = `${h}:${m}:${s}`;
}

setInterval(updateTime,1000);
</script>

</body>
</html>

<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DEKMASH HEX</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Kanit:wght@400;500;600;700;800&display=swap');

*{box-sizing:border-box;margin:0;padding:0}
body{
  min-height:100vh;
  background:radial-gradient(circle at 50% 0%,#3b0808 0%,#100304 45%,#050101 100%);
  color:#fff;font-family:'Kanit',sans-serif;padding:20px 18px 40px
}
.app{max-width:780px;margin:auto}
.header{display:flex;justify-content:space-between;align-items:center;margin-bottom:28px}
.logo{font-size:42px;font-weight:800;letter-spacing:2px}
.hex{display:inline-block;background:#4d0808;color:#ff3b3b;padding:7px 18px;border-radius:30px;font-size:20px;margin-left:8px}
.subtitle{color:#8d6d70;font-size:14px;letter-spacing:5px;margin-top:-5px}
.ready{background:#281012;border:1px solid #542226;border-radius:30px;padding:12px 20px;color:#d4bfc1;font-weight:700}
.ready span{color:#ff3155;margin-right:8px}

.status{border:2px solid #a71924;border-radius:24px;padding:18px 24px;background:rgba(55,7,12,.65);display:flex;justify-content:space-between;align-items:center;margin-bottom:28px}
.status-left,.status-right{color:#ff5961;font-weight:700;letter-spacing:2px}

.time-card{border:2px solid #64151d;border-radius:30px;padding:22px;display:flex;align-items:center;background:rgba(30,7,12,.8);margin-bottom:28px}
.clock{width:86px;height:86px;border-radius:25px;background:#70151d;display:flex;justify-content:center;align-items:center;font-size:40px;margin-right:22px}
.time-title{color:#9b8083;font-size:17px}
.time{font-size:32px;font-weight:700}
.active{margin-left:auto;padding:10px 18px;background:#2b1115;color:#ff315c;border-radius:25px;font-weight:700}

.games{display:flex;gap:12px;margin-bottom:30px}
.game{flex:1;border:2px solid #69151d;border-radius:30px;padding:15px 20px;display:flex;align-items:center;background:#280b10;cursor:pointer}
.game.disabled{opacity:.4;border-color:#3b2628;background:#14090a}
.game img{width:58px;height:58px;border-radius:18px;object-fit:cover;margin-right:15px}
.game-name{font-size:22px;font-weight:700}
.selected{color:#ff3b45;font-size:14px;letter-spacing:2px}

.game-info{border:2px solid #47151b;border-radius:30px;padding:28px;display:flex;align-items:center;background:rgba(17,4,7,.82);margin-bottom:30px}
.game-icon{width:120px;height:120px;border-radius:30px;background:#65121a;padding:12px;margin-right:28px}
.game-icon img{width:100%;height:100%;border-radius:22px;object-fit:cover}
.game-info h1{font-size:36px}
.modules{color:#8b7477;font-weight:700;letter-spacing:2px}
.available{color:#ff315c;margin-top:8px;font-size:18px}

.section-title{display:flex;justify-content:space-between;align-items:center;margin-bottom:18px}
.section-title h2{font-size:28px;letter-spacing:3px}
.section-title p{color:#8b7477}
.filter{font-size:28px;color:#ff3342}

.function{background:linear-gradient(90deg,#18090c,#0d0507);border:2px solid #3c171b;border-radius:30px;padding:20px 24px;display:flex;align-items:center;margin-bottom:18px}
.function-icon{width:72px;height:72px;border-radius:23px;background:#5b1018;display:flex;justify-content:center;align-items:center;color:#ff4652;font-size:32px;margin-right:25px}
.function-text{flex:1}
.function-text h3{font-size:25px}
.function-text p{color:#79696b;font-size:16px}

.switch{width:86px;height:52px;background:#4a4244;border-radius:30px;padding:5px;cursor:pointer;transition:.25s}
.knob{width:42px;height:42px;border-radius:50%;background:#fff;transition:.25s}
.switch.on{background:#b4142c}
.switch.on .knob{transform:translateX(34px)}
.switch-wrap{text-align:center}
.switch-label{color:#686062;font-weight:700;margin-top:3px}
.switch.on + .switch-label{color:#ff315c}

@media(max-width:600px){
  body{padding:15px 10px 30px}
  .logo{font-size:28px}.hex{font-size:14px}
  .ready{padding:8px 12px;font-size:12px}
  .status{padding:15px;font-size:12px}
  .time{font-size:23px}.time-card{padding:15px}
  .clock{width:65px;height:65px;font-size:28px}
  .games{flex-direction:column}
  .game-info{padding:18px}.game-icon{width:85px;height:85px;margin-right:15px}
  .game-info h1{font-size:25px}
  .function{padding:16px}.function-icon{width:60px;height:60px;margin-right:15px}
  .function-text h3{font-size:19px}.function-text p{font-size:13px}
  .switch{width:70px;height:44px}.knob{width:34px;height:34px}
  .switch.on .knob{transform:translateX(26px)}
}
</style>
</head>

<body>
<div class="app">

  <div class="header">
    <div>
      <div class="logo">DEKMASH <span class="hex">HEX</span></div>
      <div class="subtitle">PATCH CONSOLE</div>
    </div>
    <div class="ready"><span>●</span> READY</div>
  </div>

  <div class="status">
    <div class="status-left">🔒 SECURE</div>
    <b>DEKMASH // CORE</b>
    <div class="status-right">⌁ ONLINE</div>
  </div>

  <div class="time-card">
    <div class="clock">◷</div>
    <div>
      <div class="time-title">เวลาที่คงเหลือ</div>
      <div class="time" id="time"></div>
    </div>
    <div class="active">ACTIVE</div>
  </div>

  <div class="games">
    <div class="game">
      <img src="https://placehold.co/100x100/5b1018/ffffff?text=FF" alt="FF">
      <div><div class="game-name">FFTH</div><div class="selected">SELECTED</div></div>
    </div>
    <div class="game disabled">
      <img src="https://placehold.co/100x100/3a2427/ffffff?text=FF" alt="FF">
      <div><div class="game-name">FFMAX</div><div class="selected">SELECT</div></div>
    </div>
  </div>

  <div class="game-info">
    <div class="game-icon">
      <img src="https://placehold.co/200x200/5b1018/ffffff?text=FF" alt="FF">
    </div>
    <div>
      <h1>FREE FIRE</h1>
      <div class="modules">6 FUNCTION MODULES</div>
      <div class="available">✓ พร้อมใช้งาน</div>
    </div>
  </div>

  <div class="section-title">
    <div>
      <h2>FUNCTIONS</h2>
      <p>เปิดหรือปิดฟังก์ชันที่ต้องการ</p>
    </div>
    <div class="filter">☷</div>
  </div>

  <div id="functions"></div>
</div>

<script>
const functions=[
  ["▣","กันแชร์จอ","ระบบป้องกันการบันทึกและแชร์จอ"],
  ["⌾","ยิงตัวเข้าหัว FreeFire","ตัวอย่างฟังก์ชัน UI"],
  ["↗","ขยายหัว FreeFire","ตัวอย่างฟังก์ชัน UI"],
  ["◎","ยิงคอเข้าหัว FreeFire","ตัวอย่างฟังก์ชัน UI"],
  ["⌾","มองปืน FreeFire","ตัวอย่างฟังก์ชัน UI"],
  ["◉","ฟังก์ชันเพิ่มเติม","ตัวอย่างฟังก์ชัน UI"]
];

const container=document.getElementById("functions");
functions.forEach(item=>{
  const card=document.createElement("div");
  card.className="function";
  card.innerHTML=`
    <div class="function-icon">${item[0]}</div>
    <div class="function-text">
      <h3>${item[1]}</h3>
      <p>${item[2]}</p>
    </div>
    <div class="switch-wrap">
      <div class="switch" onclick="toggleSwitch(this)">
        <div class="knob"></div>
      </div>
      <div class="switch-label">OFF</div>
    </div>`;
  container.appendChild(card);
});

function toggleSwitch(el){
  el.classList.toggle("on");
  el.nextElementSibling.textContent=el.classList.contains("on")?"ON":"OFF";
}
</script>
</body>
</html>
