<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>나 어떤 사람임? — 바이브 테스트</title>
<link href="https://fonts.googleapis.com/css2?family=Black+Han+Sans&family=Noto+Sans+KR:wght@400;500;700;900&display=swap" rel="stylesheet"/>
<style>
:root {
  --cream: #FFF8EE;
  --black: #1a1008;
  --pink: #FF2D78;
  --lime: #BFFF00;
  --orange: #FF6B1A;
  --sky: #00C2FF;
  --purple: #8B00FF;
  --yellow: #FFE500;
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{
  background:var(--cream);
  font-family:'Noto Sans KR',sans-serif;
  color:var(--black);
  min-height:100vh;
  overflow-x:hidden;
  cursor: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24'%3E%3Ccircle cx='12' cy='12' r='5' fill='%23FF2D78'/%3E%3C/svg%3E") 12 12, auto;
}

/* ── NOISE OVERLAY ── */
body::before{
  content:'';position:fixed;inset:0;
  background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
  pointer-events:none;z-index:999;opacity:.5;
}

/* ── TICKER ── */
.ticker{
  background:var(--black);color:var(--lime);
  font-family:'Black Han Sans',sans-serif;
  font-size:13px;letter-spacing:.15em;
  padding:8px 0;overflow:hidden;white-space:nowrap;
  border-bottom:3px solid var(--pink);
}
.ticker-inner{display:inline-block;animation:tick 20s linear infinite;}
@keyframes tick{from{transform:translateX(0)}to{transform:translateX(-50%)}}

/* ── LAYOUT ── */
#app{max-width:720px;margin:0 auto;padding:20px 20px 60px;}

/* ── SCREEN ── */
.screen{display:none;}
.screen.active{display:block;animation:popIn .4s cubic-bezier(.175,.885,.32,1.275);}
@keyframes popIn{from{opacity:0;transform:scale(.94) translateY(10px)}to{opacity:1;transform:scale(1) translateY(0)}}

/* ── INTRO ── */
.intro-hero{
  margin-top:32px;
  background:var(--black);
  border-radius:28px;
  padding:48px 40px;
  position:relative;
  overflow:hidden;
  border:3px solid var(--black);
}
.intro-hero::before{
  content:'★';position:absolute;top:-20px;right:30px;
  font-size:160px;color:var(--yellow);opacity:.12;line-height:1;
  pointer-events:none;
}
.intro-tag{
  display:inline-block;
  background:var(--lime);color:var(--black);
  font-weight:900;font-size:11px;letter-spacing:.12em;
  padding:5px 14px;border-radius:100px;margin-bottom:20px;
  text-transform:uppercase;
}
.intro-title{
  font-family:'Black Han Sans',sans-serif;
  font-size:clamp(38px,8vw,64px);
  color:#fff;line-height:1.05;
  margin-bottom:8px;
}
.intro-title span{color:var(--pink);}
.intro-sub{
  color:rgba(255,255,255,.55);font-size:15px;line-height:1.7;
  margin-bottom:32px;margin-top:12px;
}
.intro-meta{
  display:flex;gap:12px;flex-wrap:wrap;margin-bottom:32px;
}
.intro-meta span{
  background:rgba(255,255,255,.08);border:1px solid rgba(255,255,255,.15);
  border-radius:100px;padding:6px 14px;font-size:12px;color:rgba(255,255,255,.7);
}
.btn-start{
  display:inline-block;
  background:var(--pink);color:#fff;
  font-family:'Black Han Sans',sans-serif;font-size:20px;
  padding:16px 40px;border-radius:14px;border:none;cursor:pointer;
  letter-spacing:.05em;
  box-shadow:4px 4px 0 var(--yellow);
  transition:transform .15s,box-shadow .15s;
}
.btn-start:hover{transform:translate(-2px,-2px);box-shadow:6px 6px 0 var(--yellow);}
.btn-start:active{transform:translate(2px,2px);box-shadow:2px 2px 0 var(--yellow);}

.type-preview{
  display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:28px;
}
.type-chip{
  background:rgba(255,255,255,.06);border:1px solid rgba(255,255,255,.12);
  border-radius:10px;padding:10px 12px;text-align:center;
}
.type-chip .chip-emoji{font-size:20px;display:block;margin-bottom:4px;}
.type-chip .chip-name{font-size:11px;color:rgba(255,255,255,.6);font-weight:500;}

/* ── QUESTION ── */
.q-header{
  display:flex;align-items:center;justify-content:space-between;
  margin-bottom:20px;margin-top:28px;
}
.q-count{
  font-family:'Black Han Sans',sans-serif;font-size:14px;letter-spacing:.1em;color:rgba(0,0,0,.35);
}
.q-num-big{font-size:22px;color:var(--black);}
.prog-track{
  flex:1;margin:0 16px;height:8px;
  background:rgba(0,0,0,.08);border-radius:100px;overflow:hidden;
}
.prog-fill{
  height:100%;background:linear-gradient(90deg,var(--pink),var(--orange));
  border-radius:100px;transition:width .5s cubic-bezier(.4,0,.2,1);
}
.q-card{
  background:#fff;border:3px solid var(--black);border-radius:24px;
  padding:36px 32px;position:relative;overflow:hidden;
  box-shadow:6px 6px 0 var(--black);
}
.q-card::after{
  content:'?';position:absolute;bottom:-20px;right:20px;
  font-family:'Black Han Sans',sans-serif;font-size:120px;
  color:rgba(0,0,0,.04);pointer-events:none;line-height:1;
}
.q-label{
  display:inline-block;background:var(--yellow);
  font-weight:900;font-size:11px;letter-spacing:.1em;
  padding:4px 12px;border-radius:6px;margin-bottom:16px;
  border:2px solid var(--black);
}
.q-text{
  font-size:clamp(18px,4vw,22px);font-weight:700;line-height:1.5;
  margin-bottom:28px;
}
.choices{display:flex;flex-direction:column;gap:10px;}
.choice-btn{
  display:flex;align-items:flex-start;gap:14px;
  padding:16px 18px;
  background:var(--cream);border:2px solid rgba(0,0,0,.12);
  border-radius:14px;cursor:pointer;text-align:left;font-family:inherit;
  transition:all .18s;width:100%;
}
.choice-btn:hover{
  background:var(--pink);color:#fff;border-color:var(--pink);
  transform:translateX(4px);
}
.choice-btn:hover .choice-no{background:#fff;color:var(--pink);border-color:#fff;}
.choice-no{
  min-width:28px;height:28px;border-radius:8px;
  background:var(--black);color:#fff;
  font-size:12px;font-weight:900;
  display:flex;align-items:center;justify-content:center;flex-shrink:0;
  border:2px solid var(--black);transition:all .18s;
}
.choice-text{font-size:14px;line-height:1.6;padding-top:3px;font-weight:500;}
.q-nav{display:flex;justify-content:space-between;align-items:center;margin-top:20px;}
.btn-back{
  background:none;border:2px solid rgba(0,0,0,.15);
  border-radius:10px;padding:8px 16px;font-size:13px;
  cursor:pointer;font-family:inherit;color:rgba(0,0,0,.45);
  transition:all .15s;
}
.btn-back:hover{border-color:var(--black);color:var(--black);}

/* ── LOADING ── */
.loading-wrap{text-align:center;padding:80px 20px;}
.loading-emoji{font-size:64px;animation:spin 1s linear infinite;display:inline-block;}
@keyframes spin{to{transform:rotate(360deg)}}
.loading-text{
  font-family:'Black Han Sans',sans-serif;font-size:24px;
  margin-top:20px;color:var(--black);
}
.loading-sub{font-size:13px;color:rgba(0,0,0,.4);margin-top:8px;}

/* ── RESULT ── */
.result-wrap{margin-top:28px;}
.result-hero{
  border-radius:28px;padding:44px 36px;
  border:3px solid var(--black);position:relative;overflow:hidden;
  box-shadow:8px 8px 0 var(--black);margin-bottom:20px;
}
.result-tag{
  display:inline-block;background:rgba(0,0,0,.12);
  font-weight:900;font-size:11px;letter-spacing:.12em;
  padding:5px 14px;border-radius:100px;margin-bottom:16px;
  text-transform:uppercase;
}
.result-emoji-big{font-size:72px;line-height:1;margin-bottom:16px;display:block;}
.result-type-name{
  font-family:'Black Han Sans',sans-serif;
  font-size:clamp(30px,7vw,52px);line-height:1.1;margin-bottom:10px;
}
.result-sub-name{font-size:16px;font-weight:700;opacity:.65;margin-bottom:20px;}
.result-hook{
  font-size:clamp(15px,3vw,18px);font-weight:700;
  line-height:1.7;
  background:rgba(255,255,255,.2);backdrop-filter:blur(4px);
  border-radius:16px;padding:20px;border:2px solid rgba(255,255,255,.3);
}

/* Result sections */
.result-section{
  background:#fff;border:3px solid var(--black);border-radius:20px;
  padding:28px;margin-bottom:16px;
  box-shadow:4px 4px 0 var(--black);
}
.section-title{
  font-family:'Black Han Sans',sans-serif;font-size:18px;
  margin-bottom:14px;display:flex;align-items:center;gap:8px;
}
.section-badge{
  display:inline-block;
  font-size:11px;font-family:'Noto Sans KR',sans-serif;font-weight:900;
  padding:3px 10px;border-radius:6px;letter-spacing:.08em;
  vertical-align:middle;
}
.section-text{font-size:14px;line-height:1.9;color:rgba(0,0,0,.75);}
.section-text strong{color:var(--black);font-weight:900;}
.section-text em{
  background:var(--yellow);font-style:normal;padding:0 4px;border-radius:3px;
}

/* Traits */
.traits-grid{display:flex;flex-wrap:wrap;gap:8px;margin-top:14px;}
.trait{
  padding:7px 14px;border-radius:100px;font-size:13px;font-weight:700;
  border:2px solid var(--black);
}

/* stat bars */
.stat-row{display:flex;flex-direction:column;gap:10px;margin-top:10px;}
.stat-item{display:flex;align-items:center;gap:10px;}
.stat-label{font-size:12px;font-weight:700;min-width:70px;color:rgba(0,0,0,.6);}
.stat-track{flex:1;height:10px;background:rgba(0,0,0,.08);border-radius:100px;overflow:hidden;}
.stat-fill{height:100%;border-radius:100px;transition:width 1s .3s ease;}
.stat-pct{font-size:12px;font-weight:900;min-width:34px;text-align:right;}

/* Compatible */
.compat-row{display:flex;gap:10px;margin-top:12px;flex-wrap:wrap;}
.compat-card{
  flex:1;min-width:120px;
  background:var(--cream);border:2px solid rgba(0,0,0,.1);
  border-radius:14px;padding:14px;text-align:center;
}
.compat-card .c-emoji{font-size:28px;display:block;margin-bottom:6px;}
.compat-card .c-name{font-size:12px;font-weight:700;margin-bottom:3px;}
.compat-card .c-label{font-size:10px;color:rgba(0,0,0,.45);}

/* Share btn */
.btn-restart{
  display:block;width:100%;
  background:var(--black);color:#fff;
  font-family:'Black Han Sans',sans-serif;font-size:18px;
  padding:18px;border-radius:14px;border:none;cursor:pointer;
  letter-spacing:.05em;margin-top:24px;
  box-shadow:4px 4px 0 var(--pink);
  transition:transform .15s,box-shadow .15s;
}
.btn-restart:hover{transform:translate(-2px,-2px);box-shadow:6px 6px 0 var(--pink);}

/* Decorative stickers */
.sticker{
  position:absolute;font-size:22px;
  animation:wobble 3s ease-in-out infinite;pointer-events:none;
}
@keyframes wobble{
  0%,100%{transform:rotate(-8deg) scale(1)}
  50%{transform:rotate(8deg) scale(1.1)}
}

@media(max-width:480px){
  .intro-hero{padding:32px 24px;}
  .q-card{padding:28px 20px;}
  .result-hero{padding:32px 24px;}
  .type-preview{grid-template-columns:repeat(2,1fr);}
}
</style>
</head>
<body>

<div class="ticker">
  <span class="ticker-inner">
    ✦ 나 어떤 사람임? 바이브 테스트 ✦ 솔직하게 골라야 정확함 ✦ 12가지 유형 ✦ 공유 필수 ✦ 나 어떤 사람임? 바이브 테스트 ✦ 솔직하게 골라야 정확함 ✦ 12가지 유형 ✦ 공유 필수 ✦
  </span>
</div>

<div id="app">

  <div id="screen-intro" class="screen active">
    <div class="intro-hero">
      <div class="sticker" style="top:20px;right:24px;animation-delay:.5s">⚡</div>
      <div class="sticker" style="top:60px;right:60px;font-size:16px;animation-delay:1s">★</div>
      <div class="intro-tag">✦ 2025 바이브 테스트</div>
      <div class="intro-title">나<span>,</span><br>어떤<br>사람임?</div>
      <p class="intro-sub">
        "나 MBTI N이야" 같은 거 말고,<br>
        진짜로 어떤 바이브인지 15문제로 확인해봐.<br>
        <strong style="color:var(--lime)">12가지 유형</strong> 중 네가 어디 해당하는지 솔직하게 나옴.
      </p>
      <div class="intro-meta">
        <span>⚡ 15문항</span>
        <span>🎯 12가지 유형</span>
        <span>⏱ 약 3분</span>
        <span>🔥 공유각</span>
      </div>
      <button class="btn-start" onclick="startTest()">테스트 시작 →</button>

      <div class="type-preview">
        <div class="type-chip"><span class="chip-emoji">🌋</span><span class="chip-name">폭발형 천재</span></div>
        <div class="type-chip"><span class="chip-emoji">🧊</span><span class="chip-name">냉정 분석가</span></div>
        <div class="type-chip"><span class="chip-emoji">🌈</span><span class="chip-name">무지개 광인</span></div>
        <div class="type-chip"><span class="chip-emoji">🕳️</span><span class="chip-name">흑구멍형</span></div>
        <div class="type-chip"><span class="chip-emoji">🦅</span><span class="chip-name">독고다이 독수리</span></div>
        <div class="type-chip"><span class="chip-emoji">🍯</span><span class="chip-name">꿀단지 인싸</span></div>
      </div>
    </div>
  </div>

  <div id="screen-question" class="screen">
    <div class="q-header">
      <span class="q-count"><span class="q-num-big" id="qNumBig">1</span> / 15</span>
      <div class="prog-track"><div class="prog-fill" id="progFill" style="width:0%"></div></div>
      <span style="font-size:12px;color:rgba(0,0,0,.3);font-weight:700;">VIBE TEST</span>
    </div>
    <div class="q-card" id="qCard">
      <div class="q-label" id="qLabel">Q01</div>
      <div class="q-text" id="qText"></div>
      <div class="choices" id="choicesWrap"></div>
    </div>
    <div class="q-nav">
      <button class="btn-back" id="btnBack" onclick="goBack()">← 이전</button>
      <span style="font-size:12px;color:rgba(0,0,0,.3)">골라야 넘어감</span>
    </div>
  </div>

  <div id="screen-loading" class="screen">
    <div class="loading-wrap">
      <div class="loading-emoji" id="loadEmoji">🔍</div>
      <div class="loading-text" id="loadText">분석 중...</div>
      <div class="loading-sub" id="loadSub">너의 바이브를 계산하는 중</div>
    </div>
  </div>

  <div id="screen-result" class="screen">
    <div class="result-wrap" id="resultWrap"></div>
  </div>

</div>

<script>
/* ════════════════════════════════
   DATA
════════════════════════════════ */

const QUESTIONS = [
  {
    text: "단톡방에 초대됐는데 아무도 모르는 사람들임. 첫 반응은?",
    label: "사회성 테스트",
    choices: [
      "일단 '안녕하세요~' 치고 친해지려 함",
      "존재감 없이 조용히 읽씹 모드",
      "'왜 나를 여기에...' 하며 나가기 고민",
      "뭔 단톡인지 파악 후 전략적으로 첫 마디 계산"
    ],
    weights: [
      {social:2, energy:1},
      {solo:2, calm:1},
      {rebel:1, solo:1, dark:1},
      {strategy:2, calm:1}
    ]
  },
  {
    text: "주말에 아무 계획 없음. 진짜 속마음은?",
    label: "에너지 방향",
    choices: [
      "신났다! 뭐 새로운 거 해볼까 검색 시작",
      "드디어... 침대랑 하루 종일 있을 수 있다",
      "뭐 할지 몰라서 불안함 사실",
      "빈 캘린더 보면서 아무것도 못 함"
    ],
    weights: [
      {energy:2, chaos:1},
      {solo:2, calm:1},
      {anxiety:2, social:1},
      {dark:2, calm:1}
    ]
  },
  {
    text: "팀플에서 내가 맡은 역할은 항상?",
    label: "협업 스타일",
    choices: [
      "어느새 팀장 되어있음 (아무도 안 하니까)",
      "시키는 거 착실하게 잘 함",
      "아이디어 폭발, 실행은 남이",
      "혼자 다 하고 나중에 멘탈 터짐"
    ],
    weights: [
      {leader:2, strategy:1},
      {calm:2, solo:1},
      {chaos:2, energy:1},
      {solo:2, dark:1}
    ]
  },
  {
    text: "친한 친구가 나를 한 마디로 표현한다면?",
    label: "타인의 시각",
    choices: [
      "\"얘는 진짜 재밌음 ㅋㅋㅋ\"",
      "\"조용한데 할 말은 다 함\"",
      "\"갑자기 어디 감? 연락도 없이\"",
      "\"겉은 쿨한데 속에 뭔가 있음\""
    ],
    weights: [
      {social:2, energy:1},
      {calm:2, strategy:1},
      {rebel:2, solo:1},
      {dark:2, strategy:1}
    ]
  },
  {
    text: "OTT 뭐 볼지 1시간째 못 고름. 이때 나는?",
    label: "결정 방식",
    choices: [
      "친구한테 전화해서 '야 뭐 봐' 물어봄",
      "그냥 예전에 봤던 거 또 봄",
      "못 고르다 그냥 잠듦",
      "스프레드시트로 장르별 정리 후 선택"
    ],
    weights: [
      {social:2, energy:1},
      {calm:2, solo:1},
      {dark:1, calm:1, anxiety:1},
      {strategy:2, leader:1}
    ]
  },
  {
    text: "카페 가서 자리 잡을 때 선호는?",
    label: "공간 감각",
    choices: [
      "중앙 테이블, 사람 보이는 곳",
      "구석 벽면, 나 안 보이는 곳",
      "창가, 밖 볼 수 있는 곳",
      "콘센트 옆, 실용성 최우선"
    ],
    weights: [
      {social:2, energy:1},
      {solo:2, dark:1},
      {dream:2, calm:1},
      {strategy:2, calm:1}
    ]
  },
  {
    text: "갑자기 '너 요즘 좀 이상한 것 같아' 들었을 때?",
    label: "피드백 반응",
    choices: [
      "\"응? 나 뭐가?\" 하며 바로 캐물음",
      "표정은 멀쩡한데 속으로 한 시간 곱씹음",
      "\"원래 이래요~\" 하고 쿨하게 넘김",
      "그 사람 말이 맞을 수도 있으니 진지하게 분석"
    ],
    weights: [
      {social:1, energy:1, chaos:1},
      {dark:2, anxiety:1},
      {rebel:2, calm:1},
      {strategy:2, calm:1}
    ]
  },
  {
    text: "연락 스타일 솔직하게?",
    label: "소통 방식",
    choices: [
      "연락 빠름, 답장 빠름, 먼저 연락도 함",
      "오면 답하는데 먼저는 절대 안 함",
      "연락 자체를 까먹음 (의도 없음)",
      "하고 싶은 말 있을 때만 핀포인트 연락"
    ],
    weights: [
      {social:2, energy:2},
      {solo:2, calm:1},
      {chaos:2, dream:1},
      {strategy:2, solo:1}
    ]
  },
  {
    text: "새로운 뭔가를 시작할 때 나는?",
    label: "시작 방식",
    choices: [
      "일단 해보고 나중에 배움 (몸이 먼저)",
      "정보 수집만 3주, 시작은 아직",
      "기분 내키면 갑자기 시작, 기분 꺾이면 갑자기 중단",
      "계획 세우고 준비 다 되면 시작"
    ],
    weights: [
      {energy:2, chaos:1, rebel:1},
      {anxiety:2, strategy:1},
      {chaos:2, dream:1},
      {strategy:2, leader:1}
    ]
  },
  {
    text: "스트레스 받을 때 해소법은?",
    label: "감정 처리",
    choices: [
      "친구 만나서 떠들면 해결됨",
      "혼자 조용히 있어야 함",
      "갑자기 이상한 짓 함 (충동구매, 새벽드라이브 등)",
      "원인 파악 후 논리적으로 해결 시도"
    ],
    weights: [
      {social:2, energy:1},
      {solo:2, calm:1},
      {chaos:2, rebel:1},
      {strategy:2, calm:1}
    ]
  },
  {
    text: "나에 대한 평가가 틀렸을 때?",
    label: "자기인식",
    choices: [
      "바로 '아닌데요?' 하며 반박",
      "틀렸다는 걸 알지만 그냥 넘김",
      "속으로 '걔가 뭘 안다고' 하고 무시",
      "내가 진짜 그런 면이 있나 다시 생각해봄"
    ],
    weights: [
      {energy:1, social:1, rebel:1},
      {calm:2, solo:1},
      {rebel:2, dark:1},
      {strategy:1, anxiety:1, calm:1}
    ]
  },
  {
    text: "인생에서 가장 피하고 싶은 상황은?",
    label: "공포 포인트",
    choices: [
      "아무도 나에게 관심 없는 것",
      "사람들 앞에서 갑자기 주목받는 것",
      "모든 게 예측 가능하고 루틴한 삶",
      "뭔가 내 뜻대로 안 되는 것"
    ],
    weights: [
      {social:2, energy:1},
      {solo:2, anxiety:1},
      {chaos:2, rebel:1},
      {leader:2, strategy:1}
    ]
  },
  {
    text: "나의 아이디어나 생각은?",
    label: "창의성",
    choices: [
      "맨날 넘쳐서 정리가 안 됨",
      "별로 없는 것 같은데 갑자기 한 방이 나옴",
      "남들이 생각 못 한 거 생각함 (진심으로)",
      "아이디어보다 실행이 중요하다고 생각"
    ],
    weights: [
      {chaos:2, dream:1, energy:1},
      {dark:1, calm:1, strategy:1},
      {dream:2, rebel:1},
      {strategy:2, leader:1}
    ]
  },
  {
    text: "나를 가장 잘 설명하는 문장은?",
    label: "자기정의",
    choices: [
      "\"일단 가고 보는 스타일\"",
      "\"조용히 내 할 일 하는 스타일\"",
      "\"뭔가 좀 남다른 것 같음\"",
      "\"계획 없이는 못 살겠음\""
    ],
    weights: [
      {energy:2, chaos:1, rebel:1},
      {solo:2, calm:2},
      {dream:2, dark:1, rebel:1},
      {strategy:2, leader:1}
    ]
  },
  {
    text: "이 테스트 다 하고 나서 할 것 같은 행동은?",
    label: "마지막 체크",
    choices: [
      "결과 스크린샷 찍어서 바로 공유",
      "혼자 읽고 '음...' 하고 끝냄",
      "결과 보고 '이게 나야?' 하며 의심",
      "결과 분석해서 맞는지 검증 시작"
    ],
    weights: [
      {social:2, energy:2},
      {solo:2, calm:1},
      {rebel:1, dark:1, anxiety:1},
      {strategy:2, leader:1}
    ]
  }
];

/* ════ 12가지 유형 ════ */
const TYPES = {
  volcano: {
    id:'volcano', emoji:'🌋', name:'폭발형 천재',
    sub:'말보다 몸이 먼저, 뇌보다 심장이 먼저',
    color:'#FF2D78', bg:'#FFF0F4', accent:'#FF2D78',
    hook:`솔직히 말할게. 너 엄청난 에너지 가지고 있는데 그게 가끔 '테러'처럼 느껴질 수도 있음. 근데 그게 매력임. 진짜로.`,
    real:`<strong>일단 해보고 생각하는 스타일.</strong> 계획은 딱 질색이고, 지루함이 제일 두려움. 누군가 "잠깐 기다려봐"라고 하면 이미 세 걸음은 더 나가 있음.<br><br>불이 4개면 사주에서 엄청난 거라는데, 너의 바이브도 딱 그거임. <em>열정이 넘쳐서 주변을 데울 수 있지만, 가끔은 화상 입히기도 함.</em> 본인은 뒤끝 없다고 생각하겠지만 당하는 사람 입장도 생각해봐.<br><br>완주율이 좀 문제임. 시작은 항상 거창한데 마무리가... 흐지부지되는 경우 많지 않아? 취미 시작한 게 몇 개인지 세어봐. 거기서 끝까지 간 게 몇 개야.`,
    tip:`<strong>개운법:</strong> 뭔가 시작하기 전에 딱 24시간만 참아봐. 바로 질러버리고 싶은 그 충동, 하루만 자고 일어나서도 하고 싶으면 그때 해. 충동적 에너지가 엄청난 무기인데, 방향만 잡으면 진짜 무서운 사람 됨.`,
    traits:['즉흥적','열정 과부하','뒤끝 없음','일 크게 벌림'],
    stats:{열정:92, 공감:65, 계획성:28, 추진력:95, 지속력:40},
    good:'냉정 분석가', good_emoji:'🧊', good_reason:'브레이크 역할 가능',
    bad:'흑구멍형', bad_emoji:'🕳️', bad_reason:'에너지 싸움 남',
  },
  iceberg: {
    id:'iceberg', emoji:'🧊', name:'냉정 분석가',
    sub:'겉은 얼음, 속은 용암인데 아무도 모름',
    color:'#00C2FF', bg:'#F0FBFF', accent:'#0097CC',
    hook:`표정 변화 없이 핵심 한 마디로 상황 정리함. 근데 그게 무서운 거야. 아무도 네가 뭘 생각하는지 모름.`,
    real:`<strong>관찰하고, 분석하고, 확신이 생길 때만 말함.</strong> 그래서 말수는 적은데 말하면 맞음. 주변에서 "걔 말은 믿어도 돼"라는 소리 들어봤지?<br><br>근데 솔직히 <em>감정 표현이 좀 서툰 거 알지?</em> 속으로는 엄청 많이 느끼는데 밖으로 표현을 안 하니까 가까운 사람들이 "얘 나 싫어하는 거 아냐?" 오해하기도 함. 의도 없는 냉담함이 관계를 망칠 수 있음.<br><br>완벽주의 성향도 있어서 준비가 안 됐다 싶으면 시작을 안 함. 정보 수집하다가 기회를 놓치는 경우 있음. 완벽한 타이밍은 없다는 거 알면서도 기다리는 거잖아.`,
    tip:`<strong>오늘의 처방:</strong> 하루에 한 번만 '쓸데없는 감정'을 표현해봐. 카톡 하나에 이모지 하나 추가하는 것부터 시작. 겉의 얼음을 조금씩 녹이는 연습. 그게 약점이 아니라 무기가 됨.`,
    traits:['과묵','관찰력 끝판','신중함','논리 우선'],
    stats:{열정:58, 공감:72, 계획성:85, 추진력:60, 지속력:90},
    good:'꿀단지 인싸', good_emoji:'🍯', good_reason:'따뜻한 기운 공급',
    bad:'폭발형 천재', bad_emoji:'🌋', bad_reason:'속도 차이로 충돌',
  },
  rainbow: {
    id:'rainbow', emoji:'🌈', name:'무지개 광인',
    sub:'오늘 다른 색, 내일 다른 색, 모자람이 없음',
    color:'#FF6B1A', bg:'#FFF5F0', accent:'#E55A00',
    hook:`뭐 하나만 좋아하는 게 없음. 다 좋음. 다 재밌음. 그게 장점이자 단점인 거 알지?`,
    real:`<strong>관심사가 10개임. 동시에.</strong> 이것도 해보고 싶고 저것도 해보고 싶어서 에너지가 사방팔방으로 흩어짐. 남들이 보면 '저 사람은 진짜 뭐든지 하네' 싶은데, 당사자는 '나 뭐가 좋은 건지 모르겠어'인 경우 많음.<br><br><em>감정 기복이 꽤 있음.</em> 오늘 완전 흥분된 상태였다가 다음날 완전 가라앉아 있음. 주변에서 '얘 오늘 왜 이래?'를 자주 듣는 편. 본인은 당연한 거라 생각하지만 상대방은 혼란스러울 수 있음.<br><br>진지한 대화보다 가벼운 웃음을 택함. 깊어지는 관계가 좀 무서울 수 있음. 책임감이 생기는 게 부담스러운 거잖아.`,
    tip:`<strong>이번 달 미션:</strong> 지금 관심사 중 하나만 골라서 한 달 동안만 깊이 파봐. 딱 하나만. 산만함을 에너지로 전환하는 가장 빠른 방법임. 네 다양함이 사실 재능이야, 진짜로.`,
    traits:['에너지 폭발','감정 기복','만능 관심러','가볍고 재밌음'],
    stats:{열정:88, 공감:78, 계획성:35, 추진력:75, 지속력:42},
    good:'독고다이 독수리', good_emoji:'🦅', good_reason:'집중력 공급 가능',
    bad:'조용한 관찰자', bad_emoji:'🦉', bad_reason:'속도와 온도 차이',
  },
  blackhole: {
    id:'blackhole', emoji:'🕳️', name:'흑구멍형',
    sub:'존재하는데 어디 있는지 모름. 근데 없으면 허전함',
    color:'#1a1008', bg:'#F5F5F5', accent:'#333',
    hook:`있는 듯 없는 듯, 근데 사라지면 왜인지 공기가 달라짐. 그게 너야.`,
    real:`<strong>혼자 있는 게 진짜 충전임.</strong> 사람들이랑 있으면 겉으로는 괜찮아 보이는데 속으로 에너지가 빠르게 닳음. 집에 와서 뻗어버리는 거 맞지?<br><br>관찰을 엄청 잘 함. 말은 안 하지만 <em>모든 걸 다 보고 있음.</em> 그래서 나중에 뭔가 말했을 때 '얘 어떻게 알았지?' 반응 자주 받음. 조용한데 날카로운 스타일.<br><br>자기 감정을 밖에 내놓는 게 되게 불편함. 공감받고 싶긴 한데 먼저 열기가 싫음. 그래서 오해받는 경우가 좀 있음. '저 사람 차갑다'는 오해.`,
    tip:`<strong>처방전:</strong> 신뢰하는 사람 딱 한 명한테만 요즘 어떤지 말해봐. 전부 다 말 안 해도 됨. 근데 완전히 닫혀있으면 연결이 안 됨. 네가 열어주는 만큼 상대방도 들어올 수 있어.`,
    traits:['관찰의 달인','내향 끝판','독립적','말수 적음'],
    stats:{열정:45, 공감:80, 계획성:65, 추진력:50, 지속력:82},
    good:'폭발형 천재', good_emoji:'🌋', bad_reason:'에너지 공급원',
    bad:'무지개 광인', bad_emoji:'🌈', bad_reason:'피로도 급상승',
  },
  eagle: {
    id:'eagle', emoji:'🦅', name:'독고다이 독수리',
    sub:'혼자가 편함. 근데 사실 그게 제일 강한 거임',
    color:'#8B00FF', bg:'#F8F0FF', accent:'#6B00CC',
    hook:`팀플 싫어함. 근데 혼자 하면 잘 함. 의존 안 함. 근데 도움 요청도 안 함. 둘 다 문제임.`,
    real:`<strong>자기 페이스가 생명임.</strong> 남이 속도 맞춰달라 하면 스트레스 받음. 내가 생각하는 방식이 있는데 그걸 설명하기 귀찮고, 그냥 혼자 하는 게 빠름.<br><br>능력이 실제로 있음. 근데 <em>어필을 안 함.</em> 자기 PR이 너무 약해서 능력 대비 저평가받는 경우 있음. '알아서 알아주겠지'는 현실에서 안 통함.<br><br>감정을 가지고 결정하는 걸 싫어함. 논리와 효율 우선. 근데 그러다 보면 주변 사람들이 '저 사람 나를 어떻게 생각하는 걸까' 불안해하기도 함.`,
    tip:`<strong>이번 주 숙제:</strong> 뭔가 잘 됐을 때 주변에 자랑해봐. 딱 한 번만. 겸손이 미덕인 건 알지만, 세상은 말하는 사람 편임. 네 능력을 네가 먼저 알려야 해.`,
    traits:['독립적','효율주의','과묵한 실력자','팀플 기피'],
    stats:{열정:70, 공감:55, 계획성:78, 추진력:82, 지속력:88},
    good:'꿀단지 인싸', good_emoji:'🍯', good_reason:'홍보팀 역할 가능',
    bad:'무지개 광인', bad_emoji:'🌈', bad_reason:'에너지 방향이 달라서',
  },
  honey: {
    id:'honey', emoji:'🍯', name:'꿀단지 인싸',
    sub:'있으면 모두가 달라붙음. 없으면 뭔가 허전함',
    color:'#FFB800', bg:'#FFFBF0', accent:'#CC8A00',
    hook:`어딜 가도 친구 생김. 근데 진짜 내 편이 몇 명인지는 가끔 헷갈리지?`,
    real:`<strong>분위기 메이커 역할을 자동으로 함.</strong> 의도한 게 아닌데 어딜 가면 중심이 되고 있음. 그게 재능인데, 가끔 피곤함. 항상 밝아야 한다는 암묵적 압박이 있음.<br><br>남의 기분을 잘 읽음. <em>눈치가 빠름.</em> 그래서 분위기 맞추느라 정작 내 의견을 못 말하는 경우 있음. 속으론 다른 생각인데 "맞아 맞아" 하고 있는 거 알아.<br><br>관계가 넓어서 좋은데, 깊은 관계는 의외로 몇 없음. 많은 사람이랑 적당히 친한 것보다 적어도 완전히 편한 관계가 필요한 때가 있음.`,
    tip:`<strong>셀프 처방:</strong> 이번 주에 싫은 거 한 번만 싫다고 말해봐. 거절 한 번. 관계가 깨지지 않아. 오히려 네 말이 맞다고 맞장구 쳐줄 사람 나타남. 'No'를 말할 수 있어야 진짜 관계가 됨.`,
    traits:['공감능력 최상','분위기 메이커','넓은 인맥','눈치 과부하'],
    stats:{열정:80, 공감:95, 계획성:55, 추진력:68, 지속력:72},
    good:'냉정 분석가', good_emoji:'🧊', good_reason:'팩트 폭격 균형 역할',
    bad:'흑구멍형', bad_emoji:'🕳️', bad_reason:'소통 방식이 너무 달라',
  },
  dreamer: {
    id:'dreamer', emoji:'🌙', name:'몽환 드리머',
    sub:'현실에 발 딛고 있지만 머릿속은 다른 세계',
    color:'#5B6BFF', bg:'#F0F2FF', accent:'#3344DD',
    hook:`생각이 너무 많아서 실행이 늦는 타입. 근데 생각의 퀄리티가 진짜임.`,
    real:`<strong>상상력이 압도적임.</strong> 남들이 생각 못 한 아이디어가 불쑥불쑥 나옴. 근데 "그거 어떻게 할 건데?"라는 질문 앞에서 막히는 경우 많음. 비전은 있는데 실행 계획이 약함.<br><br>혼자 있는 시간에 제일 충전됨. 그 시간에 아이디어가 나오고, 글도 쓰이고, 뭔가 만들어짐. <em>창작 활동과 궁합이 좋음.</em><br><br>현실 감각이 살짝 낮을 때가 있음. 이상이 너무 높아서 현재 상황이 초라하게 느껴지는 것도 있고. 완벽한 조건 갖추고 시작하려다 타이밍 놓치는 거 자주 있음.`,
    tip:`<strong>처방:</strong> 아이디어 노트 써봐. 생각이 많을수록 기록이 중요함. 그리고 완벽하지 않아도 일단 0.1버전으로 시작해봐. 세상에 완성된 채로 나온 건 없음.`,
    traits:['상상력 폭발','창의적','현실과 괴리','감성 풍부'],
    stats:{열정:74, 공감:82, 계획성:40, 추진력:52, 지속력:60},
    good:'냉정 분석가', good_emoji:'🧊', good_reason:'실행력 보완 가능',
    bad:'폭발형 천재', bad_emoji:'🌋', bad_reason:'속도와 에너지 충돌',
  },
  rebel: {
    id:'rebel', emoji:'⚡', name:'아웃사이더 반란군',
    sub:'틀에 끼워 맞추려 하면 박살냄',
    color:'#FF2D78', bg:'#FFF0F4', accent:'#CC1560',
    hook:`규칙이 이상하면 따르지 않음. 그게 용감한 건지 무모한 건지는 상황 봐서.`,
    real:`<strong>자기만의 기준이 있음.</strong> 남들이 다 하는 거라고 따라가지 않음. '왜 이렇게 해야 해?'라는 질문을 항상 함. 그게 가끔 마찰을 만들지만, 그게 없었다면 평범하게 살았을 거야.<br><br>반복되는 일상에 견디기 힘듦. <em>자극이 없으면 살아있는 느낌이 안 남.</em> 새로운 것, 다른 것, 낯선 것을 끊임없이 찾음.<br><br>권위에 반응이 좀 있음. '그냥 이렇게 하라니까' 이런 말 들으면 오히려 반대로 하고 싶어짐. 복종보다 납득이 먼저 필요한 타입.`,
    tip:`<strong>오늘 할 것:</strong> 반항하고 싶은 충동이 생길 때, 이게 진짜 가치 있는 싸움인지 아닌지 5초만 생각해봐. 모든 전쟁을 다 싸울 필요 없음. 에너지 선택적으로 써야 진짜 반란군임.`,
    traits:['반골 기질','독자적 사고','자극 추구','규칙 거부'],
    stats:{열정:85, 공감:60, 계획성:38, 추진력:88, 지속력:55},
    good:'냉정 분석가', good_emoji:'🧊', good_reason:'논리로 방향 잡아줌',
    bad:'꿀단지 인싸', bad_emoji:'🍯', bad_reason:'눈치 게임 vs 무시 충돌',
  },
  planner: {
    id:'planner', emoji:'📐', name:'마스터 플래너',
    sub:'계획이 없으면 불안함. 근데 계획대로 안 되면 더 불안함',
    color:'#00C2FF', bg:'#F0FBFF', accent:'#007FAA',
    hook:`캘린더 색깔별로 구분함. 투두리스트에 완료 체크할 때 도파민 나옴. 맞지?`,
    real:`<strong>준비가 돼야 움직임.</strong> 즉흥적인 것보다 계획된 것이 훨씬 더 잘됨. 갑자기 뭔가 바뀌면 내심 스트레스 받음. 겉으로 티는 덜 내지만.<br><br>책임감이 강함. 맡은 일은 끝까지 함. 그래서 신뢰를 많이 받음. 근데 그게 <em>나한테 일이 계속 몰리는 이유</em>이기도 함. '쟤한테 주면 됨'이 되어버리는 거.<br><br>완벽주의 때문에 시작이 늦어지는 경우 있음. 준비가 충분히 됐다 싶어야 첫발을 뗌. 근데 완벽한 준비라는 건 없음.`,
    tip:`<strong>이번 주 실험:</strong> 계획 없이 뭔가 하나 해봐. 진짜로. 그게 밥이든 여행이든. 결과가 생각보다 나쁘지 않을 거야. 유연함을 연습해야 더 큰 계획을 실행할 수 있음.`,
    traits:['계획 덕후','책임감 끝판','완벽주의','변화에 민감'],
    stats:{열정:65, 공감:70, 계획성:98, 추진력:72, 지속력:90},
    good:'폭발형 천재', good_emoji:'🌋', good_reason:'실행력 충전 가능',
    bad:'무지개 광인', bad_emoji:'🌈', bad_reason:'예측불가 에너지에 지침',
  },
  owl: {
    id:'owl', emoji:'🦉', name:'조용한 관찰자',
    sub:'말은 안 해도 다 알고 있음. 무서운 거 맞음',
    color:'#556B2F', bg:'#F4F8F0', accent:'#3A5220',
    hook:`대화 중에 별 말 안 하는데 나중에 "그때 왜 그랬어" 정확하게 짚음. 그게 너야.`,
    real:`<strong>들을 때 진짜로 들음.</strong> 겉으로는 가만히 있는 것 같지만 모든 걸 흡수하고 있음. 그래서 사람 파악이 빠름. '저 사람 뭔가 있다' 이런 직감이 거의 틀리지 않음.<br><br>말을 아끼는 대신 한 번 말할 때 무게가 있음. <em>그 한 마디가 핵심을 찌름.</em> 그게 능력이야. 근데 너무 아끼면 주변이 '얘 뭔 생각이야?'라고 답답해하기도 함.<br><br>감정 처리를 혼자 함. 위로받는 것보다 혼자 해결하는 걸 선호. 그게 강한 거기도 하지만, 너무 혼자 짊어지면 과부하 올 수 있음.`,
    tip:`<strong>처방:</strong> 이번 주 모임에서 의견 한 번 더 말해봐. 생각이 있으면 꺼내줘야 함. 침묵이 항상 강한 건 아님. 네 생각을 듣고 싶어하는 사람이 분명 있어.`,
    traits:['경청의 달인','통찰력','과묵','혼자 처리'],
    stats:{열정:52, 공감:88, 계획성:70, 추진력:55, 지속력:85},
    good:'폭발형 천재', good_emoji:'🌋', good_reason:'방향 제시 가능',
    bad:'무지개 광인', bad_emoji:'🌈', bad_reason:'에너지 소모 극심',
  },
  fixer: {
    id:'fixer', emoji:'🔧', name:'현실 픽서',
    sub:'문제 있으면 해결함. 감성은 나중에',
    color:'#FF6B1A', bg:'#FFF5EE', accent:'#CC4400',
    hook:`친구가 고민 털어놓으면 공감보다 해결책이 먼저 나옴. 그게 장점이자 단점임.`,
    real:`<strong>실용주의자.</strong> '그래서 어쩌라고'보다 '그럼 이렇게 하자'가 먼저 나옴. 효율이 중요함. 쓸데없는 과정, 의미없는 대화, 낭비되는 시간이 불편함.<br><br>감정적인 대화가 좀 어색함. 누군가 감정을 쏟아내면 뭐라고 반응해야 할지 잠깐 멈추게 됨. <em>공감하고 싶은데 방식을 모름.</em> 그래서 해결책을 말하는 건데, 상대는 해결을 원한 게 아닐 수도 있음.<br><br>일처리는 정말 잘 함. 믿고 맡길 수 있는 타입. 근데 가끔 너무 냉정해 보여서 차갑다는 오해를 받음. 따뜻한 사람인데.`,
    tip:`<strong>이번 달 과제:</strong> 친구가 힘들다고 할 때, 해결책 말하기 전에 딱 한 마디만 먼저 해봐. "많이 힘들겠다." 그거 하나로 관계가 달라질 수 있음.`,
    traits:['실용주의','해결 중심','효율 우선','감정 표현 서툼'],
    stats:{열정:72, 공감:58, 계획성:80, 추진력:85, 지속력:82},
    good:'몽환 드리머', good_emoji:'🌙', good_reason:'상상을 현실로 만들어줌',
    bad:'무지개 광인', bad_emoji:'🌈', bad_reason:'비효율 에너지에 지침',
  },
  mystic: {
    id:'mystic', emoji:'🔮', name:'내면 탐험가',
    sub:'나에 대해 나보다 더 많이 아는 사람 없음',
    color:'#8B00FF', bg:'#F8F0FF', accent:'#6600CC',
    hook:`자기분석을 이렇게 좋아하는 사람이 또 있을까. 근데 그러다 자기 과잉 분석으로 갇히기도 함.`,
    real:`<strong>자기 자신에 대한 이해도가 높음.</strong> 왜 내가 이런 반응을 했는지, 뭐가 불편한 건지 꽤 잘 파악함. 그게 성숙함의 증거임.<br><br>가치관이 중요함. 맞지 않는 사람이랑은 억지로 어울리기 힘듦. 피상적인 관계보다 깊은 관계 몇 개를 선호함. <em>의미 없는 만남에 에너지를 쓰기 싫어함.</em><br><br>가끔 너무 깊이 생각해서 행동이 느려짐. 모든 걸 이해하고 납득이 된 후에 움직이려다 보니 기회를 놓치기도 함. 생각과 행동 사이의 갭을 줄여야 해.`,
    tip:`<strong>처방:</strong> 분석하는 에너지를 행동에 써봐. 나를 이해하는 것만큼, 나를 표현하는 것도 중요함. 오늘 생각한 거 하나만 실제로 해봐.`,
    traits:['자기성찰','가치관 중심','깊은 관계 선호','과분석 주의'],
    stats:{열정:68, 공감:85, 계획성:62, 추진력:58, 지속력:78},
    good:'현실 픽서', good_emoji:'🔧', good_reason:'행동으로 끌어줌',
    bad:'폭발형 천재', bad_emoji:'🌋', bad_reason:'충동적 에너지에 압도됨',
  },
};

/* ════ Scoring ════ */
function calcType(answers) {
  const score = {};
  answers.forEach((ai, qi) => {
    const w = QUESTIONS[qi].weights[ai];
    Object.entries(w).forEach(([k,v]) => { score[k] = (score[k]||0)+v; });
  });

  // map dominant traits to types
  const pairs = [
    [{social:1,energy:1}, 'volcano'],
    [{social:2}, 'honey'],
    [{strategy:2,calm:1}, 'iceberg'],
    [{strategy:2,leader:1}, 'planner'],
    [{solo:2,calm:2}, 'blackhole'],
    [{solo:2,dark:1}, 'owl'],
    [{chaos:2,energy:1}, 'rainbow'],
    [{chaos:2,rebel:1}, 'rebel'],
    [{dream:2}, 'dreamer'],
    [{leader:2}, 'eagle'],
    [{strategy:1,leader:1}, 'fixer'],
    [{dark:1,anxiety:1}, 'mystic'],
  ];

  let best = 'volcano', bestScore = -1;
  const typeScores = {};

  pairs.forEach(([weights, type]) => {
    let s = 0;
    Object.entries(weights).forEach(([k,v]) => { s += (score[k]||0)*v; });
    typeScores[type] = (typeScores[type]||0)+s;
  });

  Object.entries(typeScores).forEach(([t,s]) => {
    if(s > bestScore){ bestScore = s; best = t; }
  });

  return TYPES[best];
}

/* ════ STATE ════ */
let currentQ = 0;
let answers = [];

/* ════ INIT ════ */
function startTest() {
  currentQ = 0; answers = [];
  showScreen('question');
  renderQuestion();
}

function showScreen(id) {
  document.querySelectorAll('.screen').forEach(s => {
    s.classList.remove('active');
  });
  const el = document.getElementById('screen-'+id);
  el.classList.add('active');
}

function renderQuestion() {
  const q = QUESTIONS[currentQ];
  const pct = (currentQ/QUESTIONS.length)*100;

  document.getElementById('qNumBig').textContent = currentQ+1;
  document.getElementById('progFill').style.width = pct+'%';
  document.getElementById('qLabel').textContent = q.label;
  document.getElementById('qText').textContent = q.text;

  const wrap = document.getElementById('choicesWrap');
  wrap.innerHTML = '';
  const labels = ['①','②','③','④'];
  q.choices.forEach((c,i) => {
    const btn = document.createElement('button');
    btn.className = 'choice-btn';
    btn.innerHTML = `<span class="choice-no">${labels[i]}</span><span class="choice-text">${c}</span>`;
    btn.onclick = () => selectAnswer(i);
    wrap.appendChild(btn);
  });

  document.getElementById('btnBack').style.visibility = currentQ > 0 ? 'visible':'hidden';

  // card animation
  const card = document.getElementById('qCard');
  card.style.animation = 'none';
  requestAnimationFrame(()=>{ card.style.animation = 'popIn .35s cubic-bezier(.175,.885,.32,1.275)'; });
}

function selectAnswer(i) {
  answers[currentQ] = i;

  if(currentQ < QUESTIONS.length-1) {
    currentQ++;
    renderQuestion();
  } else {
    showLoading();
  }
}

function goBack() {
  if(currentQ > 0){ currentQ--; renderQuestion(); }
}

function showLoading() {
  showScreen('loading');
  const emojis = ['🔍','🌀','✨','🔮','⚡'];
  const texts = ['바이브 분석 중...','성격 패턴 계산 중...','너의 진짜 모습 찾는 중...','결과 거의 다 됨...'];
  let step = 0;
  const iv = setInterval(() => {
    step++;
    if(step < emojis.length) {
      document.getElementById('loadEmoji').textContent = emojis[step];
      document.getElementById('loadText').textContent = texts[Math.min(step-1, texts.length-1)];
    }
    if(step >= 4) { clearInterval(iv); showResult(); }
  }, 500);
}

function showResult() {
  const type = calcType(answers);
  const wrap = document.getElementById('resultWrap');

  const statHTML = Object.entries(type.stats).map(([k,v]) => {
    const colors = {열정:'#FF2D78',공감:'#00C2FF',계획성:'#8B00FF',추진력:'#FF6B1A',지속력:'#BFFF00'};
    return `<div class="stat-item">
      <span class="stat-label">${k}</span>
      <div class="stat-track"><div class="stat-fill" style="width:0%;background:${colors[k]||'#333'}" data-val="${v}"></div></div>
      <span class="stat-pct" style="color:${colors[k]||'#333'}">${v}</span>
    </div>`;
  }).join('');

  const traitHTML = type.traits.map(t =>
    `<span class="trait" style="background:${type.color}22;border-color:${type.color}55;color:${type.color}">${t}</span>`
  ).join('');

  wrap.innerHTML = `
    <div class="result-hero" style="background:${type.bg};border-color:${type.color}">
      <div class="sticker" style="top:10px;right:20px">${type.emoji}</div>
      <div class="result-tag" style="color:${type.color};background:${type.color}22">✦ 당신의 유형</div>
      <span class="result-emoji-big">${type.emoji}</span>
      <div class="result-type-name" style="color:${type.color}">${type.name}</div>
      <div class="result-sub-name">${type.sub}</div>
      <div class="result-hook">${type.hook}</div>
    </div>

    <div class="result-section">
      <div class="section-title">
        🔍 솔직한 분석
        <span class="section-badge" style="background:${type.color}22;color:${type.color}">REAL TALK</span>
      </div>
      <div class="section-text">${type.real}</div>
      <div class="traits-grid">${traitHTML}</div>
    </div>

    <div class="result-section">
      <div class="section-title">
        📊 바이브 스탯
        <span class="section-badge" style="background:#00C2FF22;color:#0097CC">STATS</span>
      </div>
      <div class="stat-row">${statHTML}</div>
    </div>

    <div class="result-section">
      <div class="section-title">
        💊 처방전
        <span class="section-badge" style="background:#BFFF0033;color:#556600">TODAY'S RX</span>
      </div>
      <div class="section-text">${type.tip}</div>
    </div>

    <div class="result-section">
      <div class="section-title">
        🤝 궁합 분석
        <span class="section-badge" style="background:#FF6B1A22;color:#CC4400">VIBE CHECK</span>
      </div>
      <div class="compat-row">
        <div class="compat-card">
          <span class="c-emoji">${type.good_emoji}</span>
          <div class="c-name" style="color:${type.color}">${type.good}</div>
          <div class="c-label">💚 찰떡궁합</div>
          <div style="font-size:11px;color:rgba(0,0,0,.45);margin-top:4px">${type.good_reason}</div>
        </div>
        <div class="compat-card">
          <span class="c-emoji">${type.bad_emoji}</span>
          <div class="c-name">${type.bad}</div>
          <div class="c-label">💥 환장 궁합</div>
          <div style="font-size:11px;color:rgba(0,0,0,.45);margin-top:4px">${type.bad_reason}</div>
        </div>
      </div>
    </div>

    <button class="btn-restart" onclick="restart()">🔄 다시 테스트하기</button>
    <p style="text-align:center;font-size:12px;color:rgba(0,0,0,.3);margin-top:16px;">결과 스크린샷 찍어서 친구한테 공유각</p>
  `;

  showScreen('result');

  // Animate stat bars
  setTimeout(() => {
    document.querySelectorAll('.stat-fill').forEach(el => {
      el.style.width = el.dataset.val + '%';
    });
  }, 300);
}

function restart() {
  currentQ = 0; answers = [];
  showScreen('intro');
}
</script>
</body>
</html>
