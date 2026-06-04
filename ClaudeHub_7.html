<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>People Hub · 피플팀</title>
<link href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.min.css" rel="stylesheet">
<style>
:root {
  --bg:#F0F2F8; --surface:#FFFFFF; --surface2:#EEF1F8;
  --border:rgba(60,80,160,0.10); --border-med:rgba(60,80,160,0.18);
  --text:#1A1D2E; --text-2:#5A6180; --text-3:#9AA0BB;
  --sans:'Pretendard',-apple-system,sans-serif;
  --radius:14px; --radius-sm:9px;
  /* 포인트: 파란 계열 */
  --blue:#3C5CC8; --blue-bg:#EEF1FB; --blue-text:#1E3480;
  --blue-dark:#2A3F99; --blue-light:#D6DCFA;
  /* 셀 컬러 */
  --c1:#C17E3A; --c1-bg:#FBF1E6; --c1-text:#7A4A1A;
  --c2:#2A7A5A; --c2-bg:#E8F5EE; --c2-text:#185A3A;
  --c3:#5B4AB5; --c3-bg:#EEEAF8; --c3-text:#38288A;
  --red-bg:#FDECEC; --red-text:#8B2020;
  --lock-bg:#F2F1EE; --lock-text:#888680;
}
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:var(--sans);background:var(--bg);color:var(--text);min-height:100vh;font-size:14px;line-height:1.6;-webkit-font-smoothing:antialiased;}

/* ── 로그인 ── */
#login-screen{min-height:100vh;display:flex;align-items:center;justify-content:center;padding:2rem;background:linear-gradient(135deg,#E8EDF8 0%,#F0F2F8 100%);}
.login-card{background:var(--surface);border:1px solid var(--border);border-radius:20px;padding:3rem 2.5rem;width:100%;max-width:400px;text-align:center;box-shadow:0 8px 32px rgba(60,80,160,0.08);}
.login-icon{width:56px;height:56px;background:var(--blue);border-radius:16px;display:inline-flex;align-items:center;justify-content:center;margin-bottom:1.4rem;}
.login-icon svg{width:26px;height:26px;}
.login-title{font-size:22px;font-weight:700;letter-spacing:-0.5px;margin-bottom:0.3rem;}
.login-sub{font-size:13px;color:var(--text-2);margin-bottom:1.75rem;line-height:1.6;}
.input-wrap{position:relative;margin-bottom:0.85rem;}
.input-wrap svg{position:absolute;left:13px;top:50%;transform:translateY(-50%);color:var(--text-3);}
.input-wrap input{width:100%;height:46px;padding:0 1rem 0 2.6rem;border:1px solid var(--border-med);border-radius:var(--radius-sm);font-family:var(--sans);font-size:14px;background:var(--bg);color:var(--text);outline:none;transition:border-color 0.15s;}
.input-wrap input:focus{border-color:var(--blue);}
.btn-login{width:100%;height:46px;background:var(--blue);color:#fff;border:none;border-radius:var(--radius-sm);font-family:var(--sans);font-size:14px;font-weight:600;cursor:pointer;transition:opacity 0.15s;}
.btn-login:hover{opacity:0.88;} .btn-login:disabled{opacity:0.38;cursor:not-allowed;}
.login-err{margin-top:0.65rem;font-size:12px;color:var(--red-text);background:var(--red-bg);padding:0.5rem 0.75rem;border-radius:6px;display:none;}

/* ── 레이아웃 ── */
#app{display:none;min-height:100vh;}
.sidebar{position:fixed;top:0;left:0;width:210px;height:100vh;background:var(--surface);border-right:1px solid var(--border);display:flex;flex-direction:column;padding:1.4rem 0.9rem;z-index:100;overflow-y:auto;}
.sb-logo{display:flex;align-items:center;gap:9px;padding:0 0.4rem;margin-bottom:1.75rem;}
.sb-logo-icon{width:32px;height:32px;border-radius:9px;background:var(--blue);display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.sb-logo-icon svg{width:16px;height:16px;}
.sb-logo-name{font-size:15px;font-weight:700;letter-spacing:-0.3px;}
.sb-logo-sub{font-size:10px;color:var(--text-3);}
.sb-label{font-size:10px;font-weight:600;letter-spacing:0.08em;text-transform:uppercase;color:var(--text-3);padding:0 0.5rem;margin-bottom:0.3rem;margin-top:0.75rem;}
.sb-nav{list-style:none;}
.sb-nav li a{display:flex;align-items:center;gap:8px;padding:0.45rem 0.65rem;border-radius:8px;color:var(--text-2);font-size:13px;font-weight:400;text-decoration:none;cursor:pointer;transition:background 0.12s,color 0.12s;}
.sb-nav li a:hover{background:var(--blue-bg);color:var(--blue-text);}
.sb-nav li a.active{background:var(--blue-bg);color:var(--blue);font-weight:600;}
.sb-nav li a svg{width:15px;height:15px;opacity:0.65;flex-shrink:0;}
.sb-nav li a.active svg{opacity:1;}
.sb-cell-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0;}
.dot-c1{background:var(--c1);} .dot-c2{background:var(--c2);} .dot-c3{background:var(--c3);}
.sb-bottom{margin-top:auto;border-top:1px solid var(--border);padding-top:0.9rem;}
.sb-user{display:flex;align-items:center;gap:8px;padding:0.4rem 0.5rem;}
.sb-avatar{width:28px;height:28px;border-radius:50%;background:var(--blue-bg);color:var(--blue);font-size:11px;font-weight:700;display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.sb-user-email{font-size:11px;color:var(--text-2);overflow:hidden;text-overflow:ellipsis;white-space:nowrap;}
.btn-logout{width:100%;margin-top:0.4rem;padding:0.38rem;background:none;border:1px solid var(--border-med);border-radius:7px;font-family:var(--sans);font-size:12px;color:var(--text-2);cursor:pointer;transition:background 0.12s;}
.btn-logout:hover{background:var(--surface2);}

/* ── 메인 ── */
.main{margin-left:210px;padding:2rem 2.5rem;max-width:1100px;}
.page-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:1.75rem;gap:1rem;}
.page-title{font-size:20px;font-weight:700;letter-spacing:-0.5px;}
.page-title .accent{color:var(--blue);}
.page-title .accent2{color:var(--c2);}
.page-title .accent3{color:var(--c3);}

/* ── 셀 탭 ── */
.cell-tab-bar{display:flex;gap:5px;margin-bottom:1.75rem;background:var(--surface);border:1px solid var(--border);border-radius:12px;padding:5px;}
.cell-tab{flex:1;display:flex;align-items:center;justify-content:center;gap:6px;padding:0.5rem;border-radius:8px;border:none;background:none;font-family:var(--sans);font-size:13px;font-weight:500;color:var(--text-2);cursor:pointer;transition:all 0.15s;white-space:nowrap;}
.cell-tab:hover{background:var(--surface2);color:var(--text);}
.cell-tab .tab-dot{width:7px;height:7px;border-radius:50%;flex-shrink:0;}
.cell-tab.active-c1{background:var(--c1-bg);color:var(--c1-text);font-weight:700;}
.cell-tab.active-c2{background:var(--c2-bg);color:var(--c2-text);font-weight:700;}
.cell-tab.active-c3{background:var(--c3-bg);color:var(--c3-text);font-weight:700;}

/* 버튼 */
.btn-add{display:flex;align-items:center;gap:5px;height:36px;padding:0 1rem;background:var(--blue);color:#fff;border:none;border-radius:var(--radius-sm);font-family:var(--sans);font-size:13px;font-weight:600;cursor:pointer;white-space:nowrap;transition:opacity 0.15s;}
.btn-add:hover{opacity:0.85;}
.btn-add svg{width:13px;height:13px;}

/* ── 카테고리 그룹 레이아웃 ── */
.cat-section{margin-bottom:1.5rem;}
.cat-header{display:flex;align-items:center;gap:8px;margin-bottom:0.6rem;padding:0 0.25rem;}
.cat-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0;}
.cat-dot-data  {background:#C17E3A;}
.cat-dot-work  {background:#3C5CC8;}
.cat-dot-report{background:#5B4AB5;}
.cat-name{font-size:12px;font-weight:600;color:var(--text-2);text-transform:uppercase;letter-spacing:0.06em;}
.cat-count{font-size:11px;color:var(--text-3);}

/* ── 행 리스트 ── */
.tool-list{background:var(--surface);border:1px solid var(--border);border-radius:12px;overflow:hidden;}
.tool-row{display:flex;align-items:center;gap:0;padding:0.7rem 1rem;border-bottom:1px solid var(--border);transition:background 0.12s;cursor:pointer;text-decoration:none;color:inherit;}
.tool-row:last-child{border-bottom:none;}
.tool-row:hover{background:var(--blue-bg);}
.tool-row-left{flex:1;display:flex;align-items:center;gap:10px;min-width:0;}
.tool-name{font-size:13.5px;font-weight:500;color:var(--text);white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.tool-desc{font-size:12px;color:var(--text-3);margin-left:8px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;flex-shrink:1;}
.tool-row-right{display:flex;align-items:center;gap:6px;flex-shrink:0;margin-left:1rem;}

/* 뱃지 */
.badge{font-size:10px;font-weight:600;padding:2px 7px;border-radius:99px;white-space:nowrap;letter-spacing:0.02em;}
.badge-c1{background:var(--c1-bg);color:var(--c1-text);}
.badge-c2{background:var(--c2-bg);color:var(--c2-text);}
.badge-c3{background:var(--c3-bg);color:var(--c3-text);}
.badge-all{background:var(--surface2);color:var(--text-2);}
.badge-cat-data  {background:#FBF1E6;color:#7A4A1A;}
.badge-cat-work  {background:#EEF1FB;color:#1E3480;}
.badge-cat-report{background:#EEEAF8;color:#38288A;}
.badge-vis-open  {background:#E8F5EE;color:#185A3A;}
.badge-vis-team  {background:#EEF1FB;color:#1E3480;}
.badge-vis-perm  {background:#FBF1E6;color:#7A4A1A;}
.badge-vis-private{background:var(--lock-bg);color:var(--lock-text);}

/* 링크 버튼 (행 안) */
.row-link{display:inline-flex;align-items:center;gap:3px;font-size:11.5px;font-weight:500;color:var(--blue);background:var(--blue-bg);border:1px solid var(--blue-light);border-radius:6px;padding:3px 8px;text-decoration:none;transition:opacity 0.12s;}
.row-link:hover{opacity:0.8;}
.row-link svg{width:10px;height:10px;}
.row-link-sheet{color:var(--c2-text);background:var(--c2-bg);border-color:#A8DCC8;}
.info-chip{display:inline-flex;align-items:center;gap:3px;font-size:10.5px;font-weight:500;padding:3px 7px;border-radius:99px;background:var(--lock-bg);color:var(--lock-text);cursor:pointer;border:none;font-family:var(--sans);transition:background 0.12s;}
.info-chip:hover{background:var(--border-med);}
.info-chip svg{width:10px;height:10px;}

/* 빈상태/로딩 */
.empty{text-align:center;padding:3.5rem 2rem;color:var(--text-2);}
.empty svg{width:34px;height:34px;color:var(--text-3);margin-bottom:0.75rem;}
.empty p{font-size:13.5px;}
.loading{text-align:center;padding:3.5rem 2rem;color:var(--text-3);}
.spinner{width:24px;height:24px;border:2px solid var(--border-med);border-top-color:var(--blue);border-radius:50%;animation:spin 0.65s linear infinite;margin:0 auto 0.75rem;}
@keyframes spin{to{transform:rotate(360deg);}}

/* ── 모달 ── */
.overlay{display:none;position:fixed;inset:0;background:rgba(26,29,46,0.45);z-index:200;align-items:center;justify-content:center;padding:1rem;}
.overlay.open{display:flex;}
.modal{background:var(--surface);border-radius:18px;width:100%;max-width:520px;max-height:90vh;overflow-y:auto;padding:1.75rem;animation:mIn 0.18s ease;}
@keyframes mIn{from{opacity:0;transform:translateY(8px);}}
.modal-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:1.4rem;}
.modal-title{font-size:18px;font-weight:700;letter-spacing:-0.3px;}
.btn-close{width:30px;height:30px;border-radius:50%;background:var(--surface2);border:none;cursor:pointer;display:flex;align-items:center;justify-content:center;transition:background 0.12s;}
.btn-close:hover{background:var(--border-med);}
.btn-close svg{width:13px;height:13px;}

/* 비밀번호 모달 */
.pw-modal{max-width:340px;text-align:center;}
.pw-icon{width:48px;height:48px;border-radius:14px;background:var(--blue-bg);display:inline-flex;align-items:center;justify-content:center;margin-bottom:1rem;}
.pw-icon svg{width:22px;height:22px;color:var(--blue);}
.pw-value{font-size:22px;font-weight:700;letter-spacing:0.08em;color:var(--text);background:var(--surface2);border-radius:10px;padding:0.75rem 1.5rem;margin:1rem 0;display:inline-block;}
.pw-hint{font-size:12px;color:var(--text-3);}

/* 폼 */
.fg{margin-bottom:1rem;}
.fl{display:block;font-size:11.5px;font-weight:600;color:var(--text-2);margin-bottom:0.35rem;letter-spacing:0.02em;}
.fi,.fs,.ft{width:100%;padding:0.58rem 0.85rem;border:1px solid var(--border-med);border-radius:var(--radius-sm);font-family:var(--sans);font-size:13.5px;background:var(--bg);color:var(--text);outline:none;transition:border-color 0.15s;}
.fi:focus,.fs:focus,.ft:focus{border-color:var(--blue);}
.ft{resize:vertical;min-height:76px;}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:0.75rem;}
.modal-foot{display:flex;justify-content:flex-end;gap:0.55rem;margin-top:1.4rem;padding-top:1.1rem;border-top:1px solid var(--border);}
.btn-sec{height:38px;padding:0 1rem;background:none;border:1px solid var(--border-med);border-radius:var(--radius-sm);font-family:var(--sans);font-size:13px;color:var(--text-2);cursor:pointer;transition:background 0.12s;}
.btn-sec:hover{background:var(--surface2);}
.btn-sub{height:38px;padding:0 1.2rem;background:var(--blue);color:#fff;border:none;border-radius:var(--radius-sm);font-family:var(--sans);font-size:13px;font-weight:600;cursor:pointer;transition:opacity 0.15s;}
.btn-sub:hover{opacity:0.85;} .btn-sub:disabled{opacity:0.38;cursor:not-allowed;}

/* 상세 모달 링크 버튼 */
.detail-link-btn{display:inline-flex;align-items:center;gap:6px;height:36px;padding:0 1rem;border-radius:8px;font-family:var(--sans);font-size:13px;font-weight:600;cursor:pointer;text-decoration:none;transition:opacity 0.15s;}
.detail-link-btn:hover{opacity:0.82;}
.detail-link-claude{background:var(--blue);color:#fff;border:none;}
.detail-link-sheet{background:var(--surface2);color:var(--text);border:1px solid var(--border-med);}
.detail-link-btn svg{width:13px;height:13px;}

/* 권한 */
.perm-section{margin-top:1.25rem;}
.perm-head{font-size:11.5px;font-weight:600;color:var(--text-2);margin-bottom:0.65rem;letter-spacing:0.02em;}
.perm-row{display:flex;align-items:center;justify-content:space-between;padding:0.45rem 0;border-bottom:1px solid var(--border);font-size:13px;}
.perm-role{font-size:10.5px;color:var(--text-2);background:var(--surface2);padding:2px 8px;border-radius:99px;font-weight:500;}
.btn-prm-del{background:none;border:none;cursor:pointer;color:var(--text-3);font-size:12px;padding:2px 6px;border-radius:4px;transition:all 0.12s;}
.btn-prm-del:hover{background:var(--red-bg);color:var(--red-text);}
.perm-add{display:flex;gap:6px;margin-top:0.65rem;}
.perm-add input{flex:1;height:34px;padding:0 0.7rem;border:1px solid var(--border-med);border-radius:7px;font-family:var(--sans);font-size:12.5px;background:var(--bg);color:var(--text);outline:none;}
.perm-add input:focus{border-color:var(--blue);}
.perm-add select{height:34px;padding:0 0.5rem;border:1px solid var(--border-med);border-radius:7px;font-family:var(--sans);font-size:12px;background:var(--bg);color:var(--text);outline:none;}
.btn-prm-add{height:34px;padding:0 0.85rem;background:var(--blue);color:#fff;border:none;border-radius:7px;font-family:var(--sans);font-size:12px;font-weight:600;cursor:pointer;white-space:nowrap;transition:opacity 0.15s;}
.btn-prm-add:hover{opacity:0.85;}
.no-access-banner{background:var(--blue-bg);border:1px solid var(--blue-light);border-radius:10px;padding:0.65rem 0.9rem;display:flex;align-items:center;gap:8px;font-size:12.5px;color:var(--blue-text);margin-top:1rem;line-height:1.6;}
.no-access-banner svg{width:15px;height:15px;flex-shrink:0;}

#toast{position:fixed;bottom:2rem;left:50%;transform:translateX(-50%);background:var(--blue);color:#fff;padding:0.6rem 1.2rem;border-radius:99px;font-size:13px;font-weight:500;opacity:0;pointer-events:none;transition:opacity 0.22s;z-index:999;white-space:nowrap;}
#toast.show{opacity:1;}

@media(max-width:768px){
  .sidebar{display:none;} .main{margin-left:0;padding:1.25rem;}
  .form-row{grid-template-columns:1fr;} .cell-tab{font-size:12px;}
  .tool-desc{display:none;}
}
</style>
</head>
<body>

<!-- 로그인 -->
<div id="login-screen">
  <div class="login-card">
    <div class="login-icon">
      <svg viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round">
        <path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/>
        <path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/>
      </svg>
    </div>
    <div class="login-title">People Hub</div>
    <div class="login-sub">피플팀 전용 Claude 툴 허브<br>회사 이메일로 접속하세요</div>
    <div class="input-wrap">
      <svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
      <input type="email" id="email-input" placeholder="name@thesmc.co.kr" autocomplete="email"/>
    </div>
    <button class="btn-login" id="login-btn" onclick="login()">접속하기</button>
    <div class="login-err" id="login-err"></div>
  </div>
</div>

<!-- 앱 -->
<div id="app">
  <aside class="sidebar">
    <div class="sb-logo">
      <div class="sb-logo-icon">
        <svg viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
          <path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/>
          <path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/>
        </svg>
      </div>
      <div>
        <div class="sb-logo-name">People Hub</div>
        <div class="sb-logo-sub">피플팀 Claude 허브</div>
      </div>
    </div>

    <div class="sb-label">탐색</div>
    <ul class="sb-nav">
      <li><a id="nav-gallery" class="active" onclick="showView('gallery',event)">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>홈
      </a></li>
      <li><a id="nav-mine" onclick="showView('mine',event)">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>내가 등록한 것
      </a></li>
    </ul>

    <div class="sb-label">셀별 보기</div>
    <ul class="sb-nav">
      <li><a id="nav-cell-c1" class="active" onclick="setCellFromSidebar('c1',event)">
        <span class="sb-cell-dot dot-c1"></span>1셀
      </a></li>
      <li><a id="nav-cell-c2" onclick="setCellFromSidebar('c2',event)">
        <span class="sb-cell-dot dot-c2"></span>2셀
      </a></li>
      <li><a id="nav-cell-c3" onclick="setCellFromSidebar('c3',event)">
        <span class="sb-cell-dot dot-c3"></span>3셀
      </a></li>
    </ul>

    <div id="admin-nav" style="display:none">
      <div class="sb-label">어드민</div>
      <ul class="sb-nav">
        <li><a id="nav-admin" onclick="showView('admin',event)">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><circle cx="12" cy="12" r="3"/><path d="M19.07 4.93a10 10 0 0 1 0 14.14"/><path d="M4.93 4.93a10 10 0 0 0 0 14.14"/></svg>전체 관리
        </a></li>
      </ul>
    </div>

    <div class="sb-bottom">
      <div class="sb-user">
        <div class="sb-avatar" id="user-avatar">?</div>
        <div class="sb-user-email" id="user-email-disp">—</div>
      </div>
      <button class="btn-logout" onclick="logout()">로그아웃</button>
    </div>
  </aside>

  <main class="main">
    <div id="view-gallery">
      <div class="page-head">
        <div class="page-title">People <span class="accent">Hub</span></div>
      </div>
      <!-- 자주 방문하는 링크 -->
      <div style="background:var(--surface);border:1px solid var(--border);border-radius:14px;padding:1.5rem 1.75rem;margin-bottom:1.5rem;">
        <div style="display:flex;align-items:center;gap:8px;margin-bottom:1rem;">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="var(--blue)" stroke-width="2"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
          <span style="font-size:13px;font-weight:700;color:var(--text);">자주 방문하는 링크</span>
        </div>
        <div style="padding:2rem 0;text-align:center;">
          <div style="width:40px;height:40px;border-radius:50%;background:var(--blue-bg);display:inline-flex;align-items:center;justify-content:center;margin-bottom:0.75rem;">
            <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="var(--blue)" stroke-width="1.8"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"/><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"/></svg>
          </div>
          <p style="font-size:13px;color:var(--text-3);line-height:1.7;">자주 방문하는 링크가 등록될 예정입니다</p>
        </div>
      </div>
      <!-- 셀별 미리보기 -->
      <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:0.75rem;">
        <div onclick="setCellFromSidebar('c1',{currentTarget:document.getElementById('nav-cell-c1')})" style="background:var(--surface);border:1px solid var(--border);border-radius:12px;padding:1.1rem 1.2rem;cursor:pointer;transition:border-color 0.15s,box-shadow 0.15s;" onmouseover="this.style.borderColor='var(--c1)'" onmouseout="this.style.borderColor='var(--border)'">
          <div style="display:flex;align-items:center;gap:7px;margin-bottom:0.5rem;">
            <span style="width:10px;height:10px;border-radius:50%;background:var(--c1);flex-shrink:0;"></span>
            <span style="font-size:13px;font-weight:700;color:var(--text);">1셀 · 채용</span>
          </div>
          <p style="font-size:12px;color:var(--text-3);">채용 운영 관련 툴 모음</p>
          <div style="margin-top:0.75rem;font-size:11px;color:var(--c1);font-weight:600;">바로가기 →</div>
        </div>
        <div onclick="setCellFromSidebar('c2',{currentTarget:document.getElementById('nav-cell-c2')})" style="background:var(--surface);border:1px solid var(--border);border-radius:12px;padding:1.1rem 1.2rem;cursor:pointer;transition:border-color 0.15s;" onmouseover="this.style.borderColor='var(--c2)'" onmouseout="this.style.borderColor='var(--border)'">
          <div style="display:flex;align-items:center;gap:7px;margin-bottom:0.5rem;">
            <span style="width:10px;height:10px;border-radius:50%;background:var(--c2);flex-shrink:0;"></span>
            <span style="font-size:13px;font-weight:700;color:var(--text);">2셀 · 조직문화</span>
          </div>
          <p style="font-size:12px;color:var(--text-3);">조직문화 관련 툴 모음</p>
          <div style="margin-top:0.75rem;font-size:11px;color:var(--c2);font-weight:600;">바로가기 →</div>
        </div>
        <div onclick="setCellFromSidebar('c3',{currentTarget:document.getElementById('nav-cell-c3')})" style="background:var(--surface);border:1px solid var(--border);border-radius:12px;padding:1.1rem 1.2rem;cursor:pointer;transition:border-color 0.15s;" onmouseover="this.style.borderColor='var(--c3)'" onmouseout="this.style.borderColor='var(--border)'">
          <div style="display:flex;align-items:center;gap:7px;margin-bottom:0.5rem;">
            <span style="width:10px;height:10px;border-radius:50%;background:var(--c3);flex-shrink:0;"></span>
            <span style="font-size:13px;font-weight:700;color:var(--text);">3셀 · 급여·노무</span>
          </div>
          <p style="font-size:12px;color:var(--text-3);">급여·노무 관련 툴 모음</p>
          <div style="margin-top:0.75rem;font-size:11px;color:var(--c3);font-weight:600;">바로가기 →</div>
        </div>
      </div>
    </div>

    <div id="view-cell" style="display:none">
      <div class="page-head">
        <div class="page-title" id="cell-title">1셀 <span class="accent">채용</span></div>
        <button class="btn-add" onclick="openAddModal()">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>툴 등록
        </button>
      </div>
      <div class="cell-tab-bar">
        <button class="cell-tab active-c1" data-cell="c1" onclick="setCell(this,'c1')">
          <span class="tab-dot" style="background:var(--c1)"></span>1셀
        </button>
        <button class="cell-tab" data-cell="c2" onclick="setCell(this,'c2')">
          <span class="tab-dot" style="background:var(--c2)"></span>2셀
        </button>
        <button class="cell-tab" data-cell="c3" onclick="setCell(this,'c3')">
          <span class="tab-dot" style="background:var(--c3)"></span>3셀
        </button>
      </div>
      <div id="card-container"><div class="loading"><div class="spinner"></div><p>불러오는 중...</p></div></div>
    </div>
      <div class="page-head">
        <div class="page-title">내가 <span class="accent">등록한 것</span></div>
        <button class="btn-add" onclick="openAddModal()">
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>툴 등록
        </button>
      </div>
      <div id="mine-container"></div>
    </div>

    <div id="view-mine" style="display:none">
      <div class="page-head"><div class="page-title">전체 <span class="accent">관리</span></div></div>
      <div id="admin-container"></div>
    </div>
  </main>
</div>

<!-- 등록/수정 모달 -->
<div class="overlay" id="modal-add">
  <div class="modal">
    <div class="modal-head">
      <div class="modal-title" id="modal-add-title">툴 등록</div>
      <button class="btn-close" onclick="closeModal('modal-add')"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg></button>
    </div>
    <input type="hidden" id="edit-id"/>
    <div class="fg"><label class="fl">툴 이름 *</label><input class="fi" id="f-name" placeholder="예: 채용 공고 초안 생성기"/></div>
    <div class="fg"><label class="fl">Claude URL *</label><input class="fi" id="f-url" placeholder="https://..."/></div>
    <div class="fg"><label class="fl">스프레드시트 URL (있는 경우)</label><input class="fi" id="f-sheet-url" placeholder="https://docs.google.com/spreadsheets/..."/></div>
    <div class="fg"><label class="fl">설명</label><textarea class="ft" id="f-desc" placeholder="어떤 툴인지 간단히 설명해주세요"></textarea></div>
    <div class="form-row">
      <div class="fg"><label class="fl">셀 *</label>
        <select class="fs" id="f-cell">
          <option value="c1">1셀 · 채용</option>
          <option value="c2">2셀 · 조직문화</option>
          <option value="c3">3셀 · 급여·노무</option>
          <option value="all">피플팀 공통</option>
        </select>
      </div>
      <div class="fg"><label class="fl">카테고리</label>
        <select class="fs" id="f-cat">
          <option value="데이터">데이터</option>
          <option value="실무">실무</option>
          <option value="보고">보고</option>
        </select>
      </div>
    </div>
    <div class="form-row">
      <div class="fg"><label class="fl">공개 범위 *</label>
        <select class="fs" id="f-vis">
          <option value="all">전체 공개</option>
          <option value="team">팀 공개</option>
          <option value="private">비공개</option>
        </select>
      </div>
      <div class="fg"><label class="fl">비밀번호 (있는 경우)</label><input class="fi" id="f-pw" placeholder="예: thesmc!"/></div>
    </div>
    <div class="fg"><label class="fl">접근 안내</label><input class="fi" id="f-note" placeholder="예: 회사 구글 계정 로그인 필요"/></div>
    <div class="modal-foot">
      <button class="btn-sec" onclick="closeModal('modal-add')">취소</button>
      <button class="btn-sub" id="submit-btn" onclick="submitDashboard()">등록하기</button>
    </div>
  </div>
</div>

<!-- 상세 모달 -->
<div class="overlay" id="modal-detail">
  <div class="modal">
    <div class="modal-head">
      <div class="modal-title" id="detail-title">—</div>
      <button class="btn-close" onclick="closeModal('modal-detail')"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg></button>
    </div>
    <div id="detail-body"></div>
    <div class="modal-foot" id="detail-foot"></div>
  </div>
</div>

<!-- 비밀번호 모달 -->
<div class="overlay" id="modal-pw">
  <div class="modal pw-modal">
    <div class="modal-head" style="justify-content:flex-end;margin-bottom:0;">
      <button class="btn-close" onclick="closeModal('modal-pw')"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg></button>
    </div>
    <div style="padding:0 0.5rem 1.5rem;">
      <div class="pw-icon"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg></div>
      <div style="font-size:13px;color:var(--text-2);margin-bottom:0.25rem;" id="pw-modal-name">—</div>
      <div style="font-size:15px;font-weight:700;color:var(--text);margin-bottom:0.75rem;">접속 비밀번호</div>
      <div class="pw-value" id="pw-modal-value">—</div>
      <div class="pw-hint">복사 후 툴에 입력해주세요</div>
      <button onclick="copyPw()" style="margin-top:1rem;width:100%;height:40px;background:var(--blue);color:#fff;border:none;border-radius:8px;font-family:var(--sans);font-size:13px;font-weight:600;cursor:pointer;">비밀번호 복사</button>
    </div>
  </div>
</div>

<div id="toast"></div>

<script>
const API='https://script.google.com/macros/s/AKfycbwX2KPdoIUcoHzCdiikoH3QxQ9koYunaRYgrr03Fh-uoyD9HSNe-kfl2tUwY2YPrZQ/exec';

const CELLS={
  all:{label:'공통',badgeCls:'badge-all',barCls:'bar-all'},
  c1:{label:'1셀',badgeCls:'badge-c1',barCls:'bar-c1'},
  c2:{label:'2셀',badgeCls:'badge-c2',barCls:'bar-c2'},
  c3:{label:'3셀',badgeCls:'badge-c3',barCls:'bar-c3'},
};
const CAT_CLS={'데이터':'badge-cat-data','실무':'badge-cat-work','보고':'badge-cat-report'};
const CAT_ORDER=['데이터','실무','보고'];

let state={email:'',isAdmin:false,dashboards:[],currentCell:'c1',currentView:'gallery',editingId:null,currentPw:''};

function toast(msg){const t=document.getElementById('toast');t.textContent=msg;t.classList.add('show');setTimeout(()=>t.classList.remove('show'),2500);}
function esc(s){if(!s)return'';return String(s).replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;').replace(/"/g,'&quot;');}
function initials(e){const p=e.split('@')[0].split('.');return(p[0][0]+(p[1]?p[1][0]:'')).toUpperCase();}
function visInfo(v){
  if(v==='all')   return{text:'전체 공개',cls:'badge-vis-open'};
  if(v==='team')  return{text:'팀 공개',cls:'badge-vis-team'};
  if(v==='perm')  return{text:'권한 필요',cls:'badge-vis-perm'};
  return{text:'비공개',cls:'badge-vis-private'};
}
function hasPw(d){const p=d.password&&String(d.password).trim();return p&&p.toLowerCase()!=='x'&&p!=='-'&&p!=='';}
function hasSheet(d){return d.sheet_url&&String(d.sheet_url).trim()!=='';}
function hasNote(d){return d.access_note&&String(d.access_note).trim()!=='';}

let _ci=0;
function jsonp(params){
  return new Promise((resolve,reject)=>{
    const cb='__phcb_'+(++_ci);
    const tid=setTimeout(()=>{delete window[cb];reject(new Error('timeout'));},14000);
    window[cb]=data=>{clearTimeout(tid);delete window[cb];document.getElementById('_s_'+cb)?.remove();resolve(data);};
    const qs=new URLSearchParams({...params,callback:cb}).toString();
    const s=document.createElement('script');
    s.id='_s_'+cb;s.src=API+'?'+qs;
    s.onerror=()=>{clearTimeout(tid);delete window[cb];s.remove();reject(new Error('net'));};
    document.head.appendChild(s);
  });
}
function apiGet(p){return jsonp(p);}
function apiPost(b){return jsonp({...b,_method:'POST'});}

async function login(){
  const email=document.getElementById('email-input').value.trim();
  const errEl=document.getElementById('login-err');
  errEl.style.display='none';
  if(!email||!email.includes('@')){errEl.textContent='올바른 이메일 주소를 입력해주세요.';errEl.style.display='block';return;}
  const btn=document.getElementById('login-btn');
  btn.disabled=true;btn.textContent='확인 중...';
  try{
    const res=await apiGet({action:'check',email});
    if(res.status!=='ok') throw new Error();
    state.email=email;state.isAdmin=res.data.is_admin;
    document.getElementById('user-email-disp').textContent=email;
    document.getElementById('user-avatar').textContent=initials(email);
    if(state.isAdmin) document.getElementById('admin-nav').style.display='block';
    document.getElementById('login-screen').style.display='none';
    document.getElementById('app').style.display='block';
    await loadDashboards();
  }catch(e){errEl.textContent='접속 중 오류가 발생했습니다.';errEl.style.display='block';}
  finally{btn.disabled=false;btn.textContent='접속하기';}
}
document.getElementById('email-input').addEventListener('keydown',e=>{if(e.key==='Enter')login();});

function logout(){
  state={email:'',isAdmin:false,dashboards:[],currentCell:'c1',currentView:'gallery',editingId:null,currentPw:''};
  document.getElementById('app').style.display='none';
  document.getElementById('login-screen').style.display='flex';
  document.getElementById('email-input').value='';
}

async function loadDashboards(){
  const c=document.getElementById('card-container');
  if(c) c.innerHTML='<div class="loading"><div class="spinner"></div><p>불러오는 중...</p></div>';
  try{
    const res=await apiGet({action:'list',email:state.email});
    if(res.status!=='ok') throw new Error();
    state.dashboards=res.data||[];
    renderCards();
  }catch(e){
    if(c) c.innerHTML='<div class="empty"><p>데이터를 불러오지 못했습니다.</p></div>';
  }
}

// ── 카테고리별 그룹 리스트 렌더 ──
function renderGroupedList(list, containerId){
  const container=document.getElementById(containerId);
  if(!container) return;
  if(list.length===0){
    container.innerHTML=`<div class="empty"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg><p>등록된 툴이 없어요.</p></div>`;
    return;
  }
  // 카테고리별 그룹핑
  const groups={};
  list.forEach(d=>{
    const cat=d.category||'기타';
    if(!groups[cat]) groups[cat]=[];
    groups[cat].push(d);
  });
  const order=[...CAT_ORDER,...Object.keys(groups).filter(k=>!CAT_ORDER.includes(k))];
  let html='';
  order.forEach(cat=>{
    if(!groups[cat]) return;
    const dotCls=cat==='데이터'?'cat-dot-data':cat==='실무'?'cat-dot-work':'cat-dot-report';
    html+=`<div class="cat-section">
      <div class="cat-header">
        <div class="cat-dot ${dotCls}"></div>
        <span class="cat-name">${esc(cat)}</span>
        <span class="cat-count">${groups[cat].length}개</span>
      </div>
      <div class="tool-list">${groups[cat].map(rowHTML).join('')}</div>
    </div>`;
  });
  container.innerHTML=html;
}

function rowHTML(d){
  const vis=visInfo(d.visibility);
  const pw=hasPw(d);
  const sheet=hasSheet(d);
  const note=hasNote(d);
  return `<div class="tool-row" onclick="openDetail('${esc(d.id)}')">
    <div class="tool-row-left">
      <span class="tool-name">${esc(d.name)}</span>
      ${d.description?`<span class="tool-desc">${esc(d.description)}</span>`:''}
    </div>
    <div class="tool-row-right">
      <span class="badge ${vis.cls}">${vis.text}</span>
      <a class="row-link" href="${esc(d.url)}" target="_blank" onclick="event.stopPropagation()">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="7" y1="17" x2="17" y2="7"/><polyline points="7 7 17 7 17 17"/></svg>열기
      </a>
      ${sheet?`<a class="row-link row-link-sheet" href="${esc(d.sheet_url)}" target="_blank" onclick="event.stopPropagation()">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="7" y1="17" x2="17" y2="7"/><polyline points="7 7 17 7 17 17"/></svg>시트
      </a>`:''}
      ${pw?`<button class="info-chip" onclick="event.stopPropagation();showPw('${esc(d.id)}')">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>비밀번호
      </button>`:''}
      ${note?`<button class="info-chip" onclick="event.stopPropagation();showNote('${esc(d.id)}')">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="12"/><line x1="12" y1="16" x2="12.01" y2="16"/></svg>안내
      </button>`:''}
    </div>
  </div>`;
}

function renderCards(){
  const cell=state.currentCell;
  const list=state.dashboards.filter(d=>cell==='all'||d.cell===cell);
  renderGroupedList(list,'card-container');
}

function setCell(el,cell){
  state.currentCell=cell;
  document.querySelectorAll('.cell-tab').forEach(b=>{b.className='cell-tab';if(b.dataset.cell===cell)b.classList.add('active-'+cell);});
  const titles={c1:'1셀 <span class="accent">채용</span>',c2:'2셀 <span class="accent2">조직문화</span>',c3:'3셀 <span class="accent3">급여·노무</span>'};
  document.getElementById('cell-title').innerHTML=titles[cell]||titles['c1'];
  renderCards();
}

function setCellFromSidebar(cell,e){
  // 뷰 전환
  ['gallery','cell','mine','admin'].forEach(v=>{
    const el=document.getElementById('view-'+v);
    if(el) el.style.display='none';
  });
  document.getElementById('view-cell').style.display='block';
  state.currentView='cell';

  // 사이드바 활성 표시
  document.querySelectorAll('.sb-nav a').forEach(a=>a.classList.remove('active'));
  document.querySelectorAll('#nav-cell-c1,#nav-cell-c2,#nav-cell-c3').forEach(a=>a.classList.remove('active'));
  document.getElementById('nav-cell-'+cell)?.classList.add('active');

  // 탭 세팅 → setCell 내부에서 renderCards 호출
  const tabEl=document.querySelector(`.cell-tab[data-cell="${cell}"]`);
  if(tabEl) setCell(tabEl, cell);
  else { state.currentCell=cell; renderCards(); }
}

function showView(view,e){
  state.currentView=view;
  ['gallery','cell','mine','admin'].forEach(v=>{
    const el=document.getElementById('view-'+v);
    if(el) el.style.display='none';
  });
  const target=document.getElementById('view-'+view);
  if(target) target.style.display='block';
  document.querySelectorAll('.sb-nav a').forEach(a=>a.classList.remove('active'));
  if(e&&e.currentTarget) e.currentTarget.classList.add('active');
  if(view==='mine') renderMine();
  if(view==='admin') renderAdmin();
}

function renderMine(){
  // 내가 등록한 것 — owner_email 기준
  const mine=state.dashboards.filter(d=>d.owner_email===state.email);
  renderGroupedList(mine,'mine-container');
}
async function renderAdmin(){
  if(!state.isAdmin)return;
  const c=document.getElementById('admin-container');
  c.innerHTML='<div class="loading"><div class="spinner"></div><p>불러오는 중...</p></div>';
  try{
    const res=await apiGet({action:'all',email:state.email});
    if(res.status!=='ok') throw new Error(res.data?.message||'API 오류');
    const all=res.data?.dashboards||[];
    c.innerHTML='';
    if(all.length===0){
      c.innerHTML='<div class="empty"><p>등록된 툴이 없어요.</p></div>';
      return;
    }
    renderGroupedList(all,'admin-container');
  }catch(e){
    c.innerHTML=`<div class="empty"><p>오류가 발생했습니다.<br><span style="font-size:11px;color:var(--text-3);">${e.message||''}</span></p></div>`;
  }
}

function showPw(id){
  const d=state.dashboards.find(x=>String(x.id)===String(id));
  if(!d)return;
  document.getElementById('pw-modal-name').textContent=d.name||'';
  document.getElementById('pw-modal-value').textContent=d.password||'—';
  state.currentPw=d.password||'';
  document.getElementById('modal-pw').classList.add('open');
}
function copyPw(){
  if(state.currentPw)navigator.clipboard.writeText(state.currentPw).then(()=>toast('비밀번호가 복사됐습니다.'));
}
function showNote(id){
  const d=state.dashboards.find(x=>String(x.id)===String(id));
  if(!d)return;
  document.getElementById('detail-title').textContent=d.name||'—';
  document.getElementById('detail-body').innerHTML=`<div style="background:var(--blue-bg);border-radius:10px;padding:1rem 1.1rem;font-size:13.5px;color:var(--blue-text);line-height:1.7;">${esc(d.access_note)}</div>`;
  document.getElementById('detail-foot').innerHTML=`<button class="btn-sec" onclick="closeModal('modal-detail')">닫기</button>`;
  document.getElementById('modal-detail').classList.add('open');
}

async function openDetail(id){
  const d=state.dashboards.find(x=>String(x.id)===String(id));
  if(!d)return;
  const cellInfo=CELLS[d.cell]||CELLS['all'];
  const vis=visInfo(d.visibility);
  const catCls=CAT_CLS[d.category]||'badge-all';
  const isOwner=d.owner_email===state.email;
  const canManage=state.isAdmin||isOwner;
  const pw=hasPw(d);const sheet=hasSheet(d);

  let perms=[];
  if(canManage){try{const res=await apiGet({action:'detail',email:state.email,id});perms=res.data?.permissions||[];}catch(e){}}

  document.getElementById('detail-title').textContent=d.name||'—';
  document.getElementById('detail-body').innerHTML=`
    <table style="width:100%;font-size:13px;border-collapse:collapse;margin-bottom:1rem;">
      <tr><td style="padding:6px 0;color:var(--text-2);width:80px;font-weight:500;">셀</td>
          <td style="padding:6px 0;"><span class="badge ${cellInfo.badgeCls}">${cellInfo.label}</span></td></tr>
      ${d.category?`<tr><td style="padding:6px 0;color:var(--text-2);font-weight:500;">카테고리</td>
          <td style="padding:6px 0;"><span class="badge ${catCls}">${esc(d.category)}</span></td></tr>`:''}
      <tr><td style="padding:6px 0;color:var(--text-2);font-weight:500;">공개 범위</td>
          <td style="padding:6px 0;"><span class="badge ${vis.cls}">${vis.text}</span></td></tr>
      <tr><td style="padding:6px 0;color:var(--text-2);font-weight:500;">담당자</td>
          <td style="padding:6px 0;font-size:12.5px;">${esc(d.owner_email)||'—'}</td></tr>
      ${d.description?`<tr><td style="padding:6px 0;color:var(--text-2);font-weight:500;vertical-align:top;">설명</td>
          <td style="padding:6px 0;font-size:13px;line-height:1.6;">${esc(d.description)}</td></tr>`:''}
      ${d.access_note?`<tr><td style="padding:6px 0;color:var(--text-2);font-weight:500;vertical-align:top;">접근 안내</td>
          <td style="padding:6px 0;font-size:12.5px;color:var(--blue-text);">${esc(d.access_note)}</td></tr>`:''}
    </table>
    <div style="display:flex;gap:8px;flex-wrap:wrap;margin-bottom:${canManage?'1rem':'0'};">
      <a class="detail-link-btn detail-link-claude" href="${esc(d.url)}" target="_blank">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="7" y1="17" x2="17" y2="7"/><polyline points="7 7 17 7 17 17"/></svg>Claude 툴 열기
      </a>
      ${sheet?`<a class="detail-link-btn detail-link-sheet" href="${esc(d.sheet_url)}" target="_blank">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="7" y1="17" x2="17" y2="7"/><polyline points="7 7 17 7 17 17"/></svg>스프레드시트 열기
      </a>`:''}
      ${pw?`<button class="detail-link-btn detail-link-sheet" onclick="showPw('${esc(d.id)}')">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="11" width="18" height="11" rx="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>비밀번호 확인
      </button>`:''}
    </div>
    ${canManage?`
    <div style="display:flex;gap:7px;margin-bottom:1rem;">
      <button class="btn-sec" style="flex:1" onclick="openEditModal('${esc(d.id)}')">수정</button>
      <button class="btn-sec" style="flex:1;color:var(--red-text);" onclick="deactivate('${esc(d.id)}')">비활성화</button>
    </div>
    <div class="perm-section">
      <div class="perm-head">접근 권한 관리</div>
      ${perms.length?perms.map(p=>`
        <div class="perm-row">
          <span>${esc(p.email)}</span>
          <span class="perm-role">${p.role||'viewer'}</span>
          <button class="btn-prm-del" onclick="removePerm('${esc(d.id)}','${esc(p.email)}')">제거</button>
        </div>`).join(''):`<div style="font-size:12px;color:var(--text-3);padding:0.4rem 0;">등록된 개인 권한 없음</div>`}
      <div class="perm-add">
        <input id="perm-ei" type="email" placeholder="추가할 이메일"/>
        <select id="perm-role"><option value="viewer">viewer</option><option value="editor">editor</option></select>
        <button class="btn-prm-add" onclick="addPerm('${esc(d.id)}')">추가</button>
      </div>
    </div>`:`
    <div class="no-access-banner">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8"><circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="12"/><line x1="12" y1="16" x2="12.01" y2="16"/></svg>
      열람 권한만 있어요. 권한 변경은 담당자에게 문의하세요.
    </div>`}
  `;
  document.getElementById('detail-foot').innerHTML=`<button class="btn-sec" onclick="closeModal('modal-detail')">닫기</button>`;
  document.getElementById('modal-detail').classList.add('open');
}

async function addPerm(id){
  const email=document.getElementById('perm-ei').value.trim();
  const role=document.getElementById('perm-role').value;
  if(!email)return toast('이메일을 입력해주세요.');
  try{const res=await apiPost({action:'add_permission',email:state.email,dashboard_id:id,target_email:email,role});
  if(res.status!=='ok')return toast(res.data?.message||'오류');toast('권한이 추가됐습니다.');openDetail(id);}
  catch{toast('오류가 발생했습니다.');}
}
async function removePerm(id,target){
  try{const res=await apiPost({action:'remove_permission',email:state.email,dashboard_id:id,target_email:target});
  if(res.status!=='ok')return toast(res.data?.message||'오류');toast('권한이 제거됐습니다.');openDetail(id);}
  catch{toast('오류가 발생했습니다.');}
}

function openAddModal(){
  state.editingId=null;
  document.getElementById('modal-add-title').textContent='툴 등록';
  document.getElementById('submit-btn').textContent='등록하기';
  ['f-name','f-url','f-sheet-url','f-desc','f-pw','f-note'].forEach(i=>document.getElementById(i).value='');
  document.getElementById('f-cell').value='c1';
  document.getElementById('f-cat').value='실무';
  document.getElementById('f-vis').value='all';
  document.getElementById('edit-id').value='';
  document.getElementById('modal-add').classList.add('open');
}
function openEditModal(id){
  const d=state.dashboards.find(x=>String(x.id)===String(id));
  if(!d)return;
  closeModal('modal-detail');
  state.editingId=id;
  document.getElementById('modal-add-title').textContent='툴 수정';
  document.getElementById('submit-btn').textContent='수정하기';
  document.getElementById('edit-id').value=id;
  document.getElementById('f-name').value=d.name||'';
  document.getElementById('f-url').value=d.url||'';
  document.getElementById('f-sheet-url').value=d.sheet_url||'';
  document.getElementById('f-desc').value=d.description||'';
  document.getElementById('f-cell').value=d.cell||'c1';
  document.getElementById('f-cat').value=d.category||'실무';
  document.getElementById('f-vis').value=d.visibility||'all';
  document.getElementById('f-pw').value=d.password||'';
  document.getElementById('f-note').value=d.access_note||'';
  document.getElementById('modal-add').classList.add('open');
}
async function submitDashboard(){
  const name=document.getElementById('f-name').value.trim();
  const url=document.getElementById('f-url').value.trim();
  if(!name||!url)return toast('이름과 URL은 필수입니다.');
  const btn=document.getElementById('submit-btn');
  btn.disabled=true;btn.textContent='처리 중...';
  const body={email:state.email,name,url,
    sheet_url:document.getElementById('f-sheet-url').value.trim(),
    description:document.getElementById('f-desc').value.trim(),
    team:document.getElementById('f-cell').value,
    cell:document.getElementById('f-cell').value,
    category:document.getElementById('f-cat').value,
    visibility:document.getElementById('f-vis').value,
    password:document.getElementById('f-pw').value.trim(),
    access_note:document.getElementById('f-note').value.trim(),
  };
  try{
    body.action=state.editingId?'update':'add';
    if(state.editingId)body.id=state.editingId;
    const res=await apiPost(body);
    if(res.status!=='ok'){toast(res.data?.message||'오류가 발생했습니다.');return;}
    toast(state.editingId?'수정됐습니다.':'등록됐습니다!');
    closeModal('modal-add');await loadDashboards();
  }catch{toast('오류가 발생했습니다.');}
  finally{btn.disabled=false;btn.textContent=state.editingId?'수정하기':'등록하기';}
}
async function deactivate(id){
  if(!confirm('이 툴을 비활성화할까요?'))return;
  try{const res=await apiPost({action:'deactivate',email:state.email,id});
  if(res.status!=='ok')return toast(res.data?.message||'오류');
  toast('비활성화됐습니다.');closeModal('modal-detail');await loadDashboards();}
  catch{toast('오류가 발생했습니다.');}
}

function closeModal(id){document.getElementById(id).classList.remove('open');}
document.querySelectorAll('.overlay').forEach(el=>{el.addEventListener('click',e=>{if(e.target===el)el.classList.remove('open');});});
</script>
</body>
</html>
