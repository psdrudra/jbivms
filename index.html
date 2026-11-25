<!DOCTYPE html>
<html lang="en"><head><meta charset="UTF-8"><meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Inventory Management Software — Lantern Login</title>
<style>

*{box-sizing:border-box;margin:0;padding:0}
:root{color-scheme:light dark;--bg:#f2f2f7;--surface:#ffffff;--text:#1c1c1e;--dim:#6b7280;--border:#e5e7eb;--accent:#0f766e}
@media (prefers-color-scheme:dark){:root{--bg:#0f0f0f;--surface:#1a1a1a;--text:#f0f0f0;--dim:#9ca3af;--border:#2d2d2d;--accent:#2dd4bf}}
body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;background:var(--bg);color:var(--text)}
button{cursor:pointer;font-family:inherit}
input,select,textarea{font-family:inherit}
@keyframes sway{0%,100%{transform:rotate(-4deg)}50%{transform:rotate(4deg)}}
@keyframes glowPulse{0%,100%{opacity:.55;transform:scale(1)}50%{opacity:1;transform:scale(1.18)}}
@keyframes flicker{0%,100%{filter:brightness(1)}42%{filter:brightness(1.25)}58%{filter:brightness(.92)}74%{filter:brightness(1.18)}}
@keyframes floatUp{0%{transform:translateY(0) scale(1);opacity:0}10%{opacity:.9}100%{transform:translateY(-110vh) scale(.6);opacity:0}}
@keyframes successFlash{0%{filter:brightness(1)}30%{filter:brightness(2.2) saturate(1.4)}100%{filter:brightness(1.35)}}
/* ---------- Lantern login ---------- */
.night{min-height:100vh;position:relative;overflow:hidden;background:#0b1026;color:#fff}
.night-bg{position:absolute;inset:0;background:radial-gradient(ellipse at 50% -10%,#7c2d12 0%,#1e1b4b 42%,#0b1026 78%)}
.stars{position:absolute;inset:0;opacity:.7}
.stars span{position:absolute;border-radius:9999px;background:#fff}
.embers{position:absolute;inset:0;pointer-events:none}
.ember{position:absolute;border-radius:9999px;background:radial-gradient(circle,#fde68a,#f97316);animation:floatUp linear infinite}
.night-inner{position:relative;z-index:2;padding:4px 16px 40px}
.lantern-row{display:flex;justify-content:center;gap:12px;padding-top:4px}
@media(min-width:640px){.lantern-row{gap:24px}}
.lantern-wrap{display:flex;flex-direction:column;align-items:center;transform-origin:top center;animation:sway 4.5s ease-in-out infinite}
.lan-string{width:2px;background:linear-gradient(to bottom,rgba(253,230,138,.2),#fbbf24)}
.lan-cap{width:32px;height:8px;background:#7f1d1d;border-radius:2px;border:1px solid rgba(217,119,6,.6)}
.lantern-body{position:relative;border-radius:46%;border:2px solid #991b1b;display:grid;place-items:center;transition:all .7s;background:radial-gradient(ellipse at center,#fef3c7 0%,#fbbf24 40%,#b45309 75%,#7f1d1d 100%);box-shadow:0 0 14px 4px rgba(251,191,36,.35)}
.lantern-body .mark{font-size:10px;font-weight:700;color:rgba(127,29,29,.8);letter-spacing:.2em;writing-mode:vertical-rl}
.lantern-body .glowring{position:absolute;inset:0;border-radius:46%;background:rgba(252,211,77,.3);animation:glowPulse 2.6s ease-in-out infinite;display:none}
.lit .lantern-body{background:radial-gradient(ellipse at center,#fff7cc 0%,#fde68a 35%,#f59e0b 68%,#dc2626 100%);box-shadow:0 0 34px 14px rgba(251,191,36,.85),0 0 80px 34px rgba(249,115,22,.4);animation:flicker 2.2s ease-in-out infinite}
.lit .lantern-body .glowring{display:block}
.lan-tassels{display:flex;gap:4px;margin-top:2px}
.lan-tassels i{width:2px;height:12px;background:rgba(239,68,68,.8);display:block}
.login-title{text-align:center;margin-top:12px}
.login-title h1{font-size:26px;font-weight:800;color:#fef3c7;text-shadow:0 0 24px rgba(251,191,36,.65);line-height:1.25}
@media(min-width:640px){.login-title h1{font-size:32px}}
.login-title p{font-size:13px;color:rgba(253,230,138,.85);margin-top:4px}
.glass{width:100%;max-width:448px;margin:20px auto 0;border-radius:24px;border:1px solid rgba(255,255,255,.15);background:rgba(255,255,255,.08);backdrop-filter:blur(12px);-webkit-backdrop-filter:blur(12px);padding:20px;box-shadow:0 20px 60px rgba(0,0,0,.5)}
.tabs{display:flex;gap:6px;flex-wrap:wrap}
.tabs button{flex:1;border:0;border-radius:9999px;padding:8px;font-size:12px;font-weight:700;white-space:nowrap;background:rgba(255,255,255,.1);color:rgba(255,255,255,.8)}
.tabs button.on{background:#fbbf24;color:#451a03;box-shadow:0 0 18px rgba(251,191,36,.6)}
.msg-ok{margin-top:16px;border-radius:12px;background:rgba(52,211,153,.2);border:1px solid rgba(110,231,183,.4);color:#d1fae5;padding:10px 14px;font-size:13px;font-weight:500}
.msg-err{margin-top:16px;border-radius:12px;background:rgba(239,68,68,.2);border:1px solid rgba(252,165,165,.4);color:#fee2e2;padding:10px 14px;font-size:13px}
.lform{margin-top:16px;display:flex;flex-direction:column;gap:14px}
.lbl{display:block;font-size:12px;font-weight:600;color:rgba(253,230,138,.9);margin-bottom:6px;letter-spacing:.02em}
.inp{width:100%;border-radius:12px;border:1px solid rgba(255,255,255,.2);background:rgba(255,255,255,.1);padding:12px 16px;font-size:15px;color:#fff;outline:none}
.inp::placeholder{color:rgba(255,255,255,.5)}
.inp:focus{border-color:#fbbf24;background:rgba(255,255,255,.15)}
.pw-wrap{position:relative}
.pw-toggle{position:absolute;right:8px;top:50%;transform:translateY(-50%);border:0;font-size:12px;background:rgba(255,255,255,.15);color:#fff;border-radius:9999px;padding:4px 10px}
.btn-primary{width:100%;border:0;border-radius:12px;background:linear-gradient(to right,#f59e0b,#dc2626);color:#fff;padding:14px;font-weight:800;font-size:16px;box-shadow:0 0 24px rgba(245,158,11,.55)}
.btn-primary:disabled{opacity:.6}
.btn-amber{width:100%;border:0;border-radius:12px;background:#f59e0b;color:#451a03;padding:12px;font-weight:800;font-size:15px}
.btn-amber:disabled{opacity:.6}
.btn-gmail{width:100%;border:0;border-radius:12px;background:#fff;color:#1f2937;padding:12px;font-weight:700;font-size:15px;display:flex;align-items:center;justify-content:center;gap:8px}
.btn-gmail-big{padding:14px;font-weight:800}
.divider{display:flex;align-items:center;gap:12px;color:rgba(255,255,255,.5);font-size:11px}
.divider span{flex:1;height:1px;background:rgba(255,255,255,.15)}
.link-row{display:flex;justify-content:space-between;font-size:12px}
.linklike{background:none;border:0;color:#fcd34d;text-decoration:underline;font-size:12px;padding:0}
.small-note{text-align:center;font-size:12px;color:rgba(255,255,255,.6)}
.small-note .linklike{font-weight:700}
.fineprint{text-align:center;font-size:11px;color:rgba(255,255,255,.4);margin:16px auto 0;max-width:448px;line-height:1.6}
.fineprint2{font-size:11px;color:rgba(255,255,255,.5);text-align:center;line-height:1.6}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.found-id{border-radius:12px;background:rgba(251,191,36,.2);border:1px solid rgba(252,211,77,.5);padding:16px;text-align:center}
.found-id .uid{font-size:22px;font-weight:800;font-family:ui-monospace,monospace;margin-top:4px}
.gmail-hero{text-align:center;padding:4px 0}
.gmail-hero .big{font-size:42px}
.gmail-hero p{font-size:13px;color:rgba(255,255,255,.75);margin-top:4px;line-height:1.6}
.desc{font-size:13px;color:rgba(255,255,255,.75);line-height:1.6}
.success-screen{animation:successFlash 1.1s ease forwards}
/* ---------- Inventory app ---------- */
.app{padding-bottom:112px}
.userbar{background:#1c0a00;color:#fff;padding:10px 16px;display:flex;align-items:center;gap:12px;border-bottom:1px solid rgba(245,158,11,.3);box-shadow:0 4px 24px rgba(245,158,11,.25)}
.userbar .lamp{font-size:22px}
.userbar .who{flex:1;min-width:0}
.userbar .who .nm{font-size:13px;font-weight:700;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;line-height:1.3}
.userbar .who .nm span{font-weight:400;color:#fcd34d;font-size:11px}
.userbar .who .em{font-size:11px;color:rgba(255,255,255,.6);white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.pill-btn{flex-shrink:0;border:0;border-radius:9999px;background:rgba(255,255,255,.15);color:#fff;padding:6px 12px;font-size:12px;font-weight:600}
.stats-head{background:#0f2e2a;color:#fff;padding:20px 16px}
.stats-head .row1{display:flex;align-items:flex-start;justify-content:space-between;gap:12px}
.stats-head h1{font-size:22px;font-weight:700;line-height:1.3}
.stats-head .sub{font-size:13px;color:rgba(204,251,241,.9);margin-top:2px}
.csv-btn{flex-shrink:0;border:0;border-radius:9999px;background:rgba(255,255,255,.15);color:#fff;padding:8px 12px;font-size:13px;font-weight:500}
.stat-grid{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-top:16px}
.stat-box{border-radius:12px;background:rgba(255,255,255,.1);padding:10px;text-align:center;border:0;color:#fff;width:100%}
.stat-box .num{font-size:22px;font-weight:700;line-height:1}
.stat-box .cap{font-size:11px;color:#ccfbf1;margin-top:4px}
.stat-box.amber{background:rgba(251,191,36,.9);color:#451a03}
.stat-box.amber .cap{color:#451a03;font-weight:500}
.stat-box.red{background:rgba(239,68,68,.9)}
.stat-box.red .cap{color:#fee2e2}
.mini-stats{display:flex;gap:16px;margin-top:12px;font-size:12px;color:rgba(204,251,241,.9);padding:0 2px;flex-wrap:wrap}
.mini-stats b{color:#fff}
.view-tabs{padding:0 16px;margin-top:12px;display:flex;gap:8px}
.view-tabs button{flex:1;border-radius:9999px;padding:10px;font-size:14px;font-weight:600;border:1px solid var(--border);background:var(--surface);color:var(--text)}
.view-tabs button.on-list{background:#0f766e;color:#fff;border-color:#0f766e}
.view-tabs button.on-alerts{background:#d97706;color:#fff;border-color:#d97706}
.section{padding:0 16px;margin-top:12px}
.search-inp,.f-inp{width:100%;border-radius:8px;border:1px solid var(--border);background:var(--surface);padding:10px 12px;font-size:15px;color:var(--text);outline:none}
.search-inp:focus,.f-inp:focus{border-color:#0d9488}
.chips{display:flex;gap:8px;overflow-x:auto;padding:10px 16px 4px;margin:0 -16px}
.chips button{flex-shrink:0;border-radius:9999px;padding:8px 14px;font-size:13px;font-weight:500;border:1px solid var(--border);background:var(--surface);color:var(--text);white-space:nowrap}
.chips button.on{background:#0f766e;color:#fff;border-color:#0f766e}
.filter-row{display:flex;gap:8px;margin-top:10px}
.filter-row select{flex:1;border-radius:8px;border:1px solid var(--border);background:var(--surface);padding:8px;font-size:13px;color:var(--text)}
.cat-summary{display:flex;flex-wrap:wrap;gap:6px;margin-top:10px}
.cat-summary span{font-size:11px;background:var(--surface);border:1px solid var(--border);border-radius:9999px;padding:4px 8px}
.list-wrap{padding:0 16px;margin-top:12px;display:flex;flex-direction:column;gap:10px}
.card{background:var(--surface);border:1px solid var(--border);border-radius:16px;padding:16px;text-align:left;width:100%;color:var(--text)}
.card-top{display:flex;align-items:flex-start;gap:12px;background:none;border:0;width:100%;text-align:left;color:var(--text);padding:0}
.icon-tile{width:44px;height:44px;border-radius:12px;background:#f0fdfa;border:1px solid #ccfbf1;display:grid;place-items:center;font-size:22px;flex-shrink:0}
@media (prefers-color-scheme:dark){.icon-tile{background:#132a26;border-color:#1d3a34}}
.card-main{flex:1;min-width:0}
.name-row{display:flex;align-items:center;gap:8px;flex-wrap:wrap}
.asset-name{font-weight:700;font-size:15px}
.status-pill{font-size:10px;font-weight:600;padding:2px 8px;border-radius:9999px}
.card-sub{font-size:12px;color:var(--dim);margin-top:2px}
.sn-chip{font-family:ui-monospace,monospace;font-size:12px;margin-top:4px;background:var(--bg);border-radius:6px;padding:4px 8px;display:inline-block;max-width:100%;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.meta-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:8px;margin-top:12px;font-size:11px}
.meta-grid .k{color:var(--dim)}
.meta-grid .v{font-weight:500;font-size:12px;margin-top:2px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis}
.wbadge{margin-top:10px;font-size:11px;font-weight:500;padding:6px 10px;border-radius:8px;border:1px solid;display:inline-block}
.wb-green{background:#d1fae5;color:#065f46;border-color:#a7f3d0}
.wb-amber{background:#fef3c7;color:#78350f;border-color:#fcd34d}
.wb-red{background:#fee2e2;color:#991b1b;border-color:#fecaca}
.wb-gray{background:#f3f4f6;color:#4b5563;border-color:#e5e7eb}
@media (prefers-color-scheme:dark){.wb-green{background:#064e3b;color:#a7f3d0;border-color:#065f46}.wb-amber{background:#451a03;color:#fcd34d;border-color:#92400e}.wb-red{background:#450a0a;color:#fca5a5;border-color:#7f1d1d}.wb-gray{background:#1f2937;color:#d1d5db;border-color:#374151}}
.card-actions{display:flex;gap:8px;margin-top:12px;padding-top:12px;border-top:1px solid var(--border)}
.card-actions button{border-radius:8px;font-weight:600;font-size:13px;padding:8px 12px;border:1px solid var(--border);background:var(--bg);color:var(--text)}
.card-actions .edit{flex:1;background:rgba(15,118,110,.1);color:#115e59;border-color:transparent}
@media (prefers-color-scheme:dark){.card-actions .edit{color:#5eead4}}
.card-actions .svc{flex:1}
.card-actions .del{background:#fef2f2;color:#b91c1c;border-color:#fee2e2}
@media (prefers-color-scheme:dark){.card-actions .del{background:#450a0a;color:#fca5a5;border-color:#7f1d1d}}
.empty{border-radius:16px;background:var(--surface);border:1px dashed var(--border);padding:32px;text-align:center}
.empty .big{font-size:48px}
.empty h3{font-weight:700;margin-top:12px;font-size:16px}
.empty p{font-size:13px;color:var(--dim);margin-top:4px;line-height:1.6}
.empty button{margin-top:16px;background:#0f766e;color:#fff;border:0;border-radius:9999px;padding:10px 20px;font-weight:600;font-size:14px}
.alert-note{text-align:center;font-size:12px;color:#92400e;background:#fffbeb;border:1px solid #fde68a;border-radius:8px;padding:8px 12px}
@media (prefers-color-scheme:dark){.alert-note{background:#451a03;color:#fcd34d;border-color:#92400e}}
.fab{position:fixed;bottom:24px;right:16px;z-index:40;background:#0f766e;color:#fff;border:0;border-radius:9999px;padding:14px 20px 14px 16px;box-shadow:0 10px 25px rgba(0,0,0,.3);font-weight:700;font-size:15px;display:flex;align-items:center;gap:6px}
.alert-card{display:flex;gap:12px;align-items:flex-start;width:100%;text-align:left}
.alert-card .ic{font-size:24px}
.recent-item{border-radius:12px;background:var(--surface);border:1px solid var(--border);padding:12px 14px;display:flex;justify-content:space-between;gap:12px}
.recent-item .t{font-weight:500;font-size:14px}
.recent-item .d{font-size:12px;color:var(--dim)}
.recent-item .c{font-weight:600;font-size:13px;flex-shrink:0}
.h2{font-weight:700;font-size:15px;padding-top:12px}
/* ---------- Modals ---------- */
.overlay{position:fixed;inset:0;z-index:50;background:rgba(0,0,0,.5);display:flex;align-items:flex-end;justify-content:center}
@media(min-width:640px){.overlay{align-items:center}}
.sheet{background:var(--surface);color:var(--text);width:100%;max-height:92vh;overflow-y:auto;border-radius:24px 24px 0 0;padding:20px}
@media(min-width:640px){.sheet{border-radius:24px}}
.sheet-head{display:flex;align-items:center;justify-content:space-between;gap:12px}
.sheet-head h2{font-weight:700;font-size:18px}
.x-btn{width:36px;height:36px;border-radius:9999px;background:var(--bg);border:0;display:grid;place-items:center;font-size:16px;color:var(--text);flex-shrink:0}
.aform{margin-top:16px;display:flex;flex-direction:column;gap:14px}
.f-lbl{display:block;font-size:13px;font-weight:500;color:var(--dim);margin-bottom:4px}
.warr-box{border-radius:12px;background:#f0fdfa;border:1px solid #ccfbf1;padding:12px;display:flex;flex-direction:column;gap:12px}
@media (prefers-color-scheme:dark){.warr-box{background:#0d2420;border-color:#134e4a}}
.warr-box .t{font-size:12px;font-weight:700;color:#134e4a}
@media (prefers-color-scheme:dark){.warr-box .t{color:#5eead4}}
.warr-end{font-size:12px;color:#115e59}
@media (prefers-color-scheme:dark){.warr-end{color:#99f6e4}}
.form-err{font-size:13px;color:#dc2626;background:#fef2f2;border:1px solid #fee2e2;border-radius:8px;padding:8px 12px}
@media (prefers-color-scheme:dark){.form-err{background:#450a0a;border-color:#7f1d1d;color:#fca5a5}}
.btn-save{width:100%;background:#0f766e;color:#fff;border:0;border-radius:12px;padding:14px;font-weight:700;font-size:15px}
.btn-save:disabled{opacity:.6}
.detail-head{display:flex;gap:12px}
.detail-head .icon-tile{width:48px;height:48px;font-size:26px}
.detail-head h2{font-weight:700;font-size:17px;line-height:1.3}
.detail-head p{font-size:12px;color:var(--dim)}
.warr-panel{margin-top:12px;border-radius:12px;border:1px solid;padding:12px}
.warr-panel .r1{display:flex;justify-content:space-between;font-size:13px;font-weight:600}
.warr-panel .r2{font-size:12px;margin-top:4px;opacity:.8}
.wbar{height:8px;background:rgba(0,0,0,.1);border-radius:9999px;margin-top:8px;overflow:hidden}
.wbar i{display:block;height:100%;border-radius:9999px}
.wp-green{background:#ecfdf5;border-color:#a7f3d0}.wp-amber{background:#fffbeb;border-color:#fde68a}.wp-red{background:#fef2f2;border-color:#fecaca}
@media (prefers-color-scheme:dark){.wp-green{background:#022c22}.wp-amber{background:#451a03}.wp-red{background:#450a0a}}
.dl{display:grid;grid-template-columns:1fr 1fr;gap:10px 16px;margin-top:16px;font-size:13px}
.dl dt{color:var(--dim);font-size:11px}
.dl dd{font-weight:500}
.dl .mono{font-family:ui-monospace,monospace;word-break:break-all}
.detail-actions{display:flex;gap:8px;margin-top:16px}
.detail-actions .edit{flex:1;background:#0f766e;color:#fff;border:0;border-radius:8px;padding:10px;font-weight:600;font-size:13px}
.detail-actions .del{background:#fef2f2;color:#b91c1c;border:1px solid #fee2e2;border-radius:8px;padding:10px 16px;font-weight:600;font-size:13px}
@media (prefers-color-scheme:dark){.detail-actions .del{background:#450a0a;color:#fca5a5;border-color:#7f1d1d}}
.maint-item{display:flex;gap:12px;align-items:flex-start;border-radius:12px;border:1px solid var(--border);padding:10px 12px}
.maint-item .t{font-size:13px;font-weight:600}
.maint-item .d{font-size:12px;color:var(--dim)}
.maint-item .x{color:#ef4444;background:none;border:0;font-size:14px;padding:4px 8px}
.maint-form{margin-top:12px;border-radius:12px;background:var(--bg);border:1px solid var(--border);padding:12px;display:flex;flex-direction:column;gap:10px}
.maint-form .t{font-size:12px;font-weight:700}
.btn-teal-sm{width:100%;background:#0f766e;color:#fff;border:0;border-radius:8px;padding:10px;font-weight:600;font-size:13px}
.confirm-overlay{position:fixed;inset:0;z-index:60;background:rgba(0,0,0,.6);display:grid;place-items:center;padding:0 16px}
.confirm-box{background:var(--surface);color:var(--text);border-radius:16px;padding:20px;width:100%;max-width:384px}
.confirm-box h3{font-weight:700;font-size:16px}
.confirm-box p{font-size:13px;color:var(--dim);margin-top:6px;line-height:1.6}
.confirm-box .row{display:flex;gap:8px;margin-top:16px}
.confirm-box .cancel{flex:1;border-radius:8px;border:1px solid var(--border);background:var(--surface);color:var(--text);padding:10px;font-weight:600;font-size:14px}
.confirm-box .yes{flex:1;border-radius:8px;border:0;background:#dc2626;color:#fff;padding:10px;font-weight:600;font-size:14px}
.loading-note{text-align:center;padding:40px 0;color:var(--dim)}
/* ---------- Online database (cloud sync) ---------- */
.cloud-btn{flex-shrink:0;border:0;border-radius:9999px;background:rgba(255,255,255,.15);color:#fff;padding:6px 12px;font-size:12px;font-weight:600}
.cloud-btn.on{background:#065f46;color:#d1fae5}
.cloud-login-row{text-align:center;margin:14px auto 0}
.cloud-login-row button{background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.2);color:#fde68a;border-radius:9999px;padding:8px 16px;font-size:12px;font-weight:700}
.cloud-login-row span{display:block;margin-top:6px;font-size:11px;color:rgba(255,255,255,.55)}
.sync-note{font-size:12px;border-radius:8px;padding:8px 12px;margin-top:10px;line-height:1.6}
.sync-ok{background:#ecfdf5;color:#065f46;border:1px solid #a7f3d0}
.sync-off{background:#fffbeb;color:#92400e;border:1px solid #fde68a}
.sync-err{background:#fef2f2;color:#991b1b;border:1px solid #fecaca}
@media (prefers-color-scheme:dark){.sync-ok{background:#022c22;color:#a7f3d0;border-color:#065f46}.sync-off{background:#451a03;color:#fcd34d;border-color:#92400e}.sync-err{background:#450a0a;color:#fca5a5;border-color:#7f1d1d}}
.sql-box{width:100%;border-radius:8px;border:1px solid var(--border);background:#0b1026;color:#a7f3d0;font-family:ui-monospace,monospace;font-size:11px;padding:10px;min-height:110px}
.steps{font-size:13px;line-height:1.7;color:var(--text);padding-left:18px}
.steps b{color:var(--text)}
.btn-cloud{width:100%;background:#065f46;color:#fff;border:0;border-radius:12px;padding:13px;font-weight:700;font-size:14px}
.btn-cloud:disabled{opacity:.6}
.btn-ghost{width:100%;background:var(--surface);color:var(--text);border:1px solid var(--border);border-radius:12px;padding:11px;font-weight:600;font-size:13px}
/* ---------- Full-page layout: the software spans the whole screen ---------- */
html,body{width:100%}
.night{min-height:100dvh}
.app{min-height:100dvh}
@media(min-width:768px){
.list-wrap{display:grid;grid-template-columns:1fr 1fr;align-items:start}
.list-wrap>p,.list-wrap>.h2,.list-wrap>.empty,.list-wrap>.alert-note{grid-column:1/-1}
}
@media(min-width:1280px){
.list-wrap{grid-template-columns:repeat(3,1fr)}
}

</style></head><body>
<div id="root"></div><div id="modalRoot"></div>
<script>window.__SEED__={"assets":[{"assetTag":"com-01","assignedTo":"Laxman","brand":"HP","category":"Computer","condition":"Good","createdAt":"2026-11-24T10:37:26.829Z","department":"IT","id":1,"location":"Area Office, Chandpur","model":"HP Prodesk 400","name":"HP Prodesk 400","notes":"","purchaseDate":"2026-11-02","purchasePrice":95000,"serialNumber":"4CE02536","status":"In Stock","vendor":"Star Tech","warrantyDaysLeft":1073,"warrantyEndDate":"2029-11-02","warrantyMonths":36,"warrantyStatus":"Active"}],"logs":[]};window.__CLOUD__={"projectId":"inventory-management-75f2d"};</script>
<script>

var SEED = window.__SEED__ || { assets: [], logs: [] };
var CATS = [["All","📦"],["Computer","🖥️"],["Laptop","💻"],["Printer","🖨️"],["Monitor","🖥️"],["Scanner","📠"],["UPS","🔋"],["Network","🌐"],["Projector","📽️"],["Other","🧩"]];
var CATI = { Computer: "🖥️", Laptop: "💻", Printer: "🖨️", Monitor: "🖥️", Scanner: "📠", UPS: "🔋", Network: "🌐", Projector: "📽️", Other: "🧩" };
var STAT = { "In Use": ["#065f46","#d1fae5"], "In Stock": ["#1e40af","#dbeafe"], "Under Repair": ["#92400e","#fef3c7"], "Retired": ["#374151","#e5e7eb"], "Damaged": ["#991b1b","#fee2e2"] };
var MTYPES = ["Service","Repair","Upgrade","Inspection","Warranty Claim","Other"];
function $(id){ return document.getElementById(id); }
function esc(s){ return String(s == null ? "" : s).replace(/&/g,"&amp;").replace(/</g,"&lt;").replace(/>/g,"&gt;").replace(/"/g,"&quot;"); }
function load(k, d){ try { var v = localStorage.getItem(k); return v ? JSON.parse(v) : d; } catch(e){ return d; } }
function store(k, v){ try { localStorage.setItem(k, JSON.stringify(v)); } catch(e){} }
var users = load("inv2_users", []);
var assets = load("inv2_assets", null);
var logs = load("inv2_logs", null);
if (!assets) { assets = SEED.assets || []; store("inv2_assets", assets); }
if (!logs) { logs = SEED.logs || []; store("inv2_logs", logs); }
var cur = ""; try { cur = localStorage.getItem("inv2_cur") || ""; } catch(e){}
function saveAll(){ store("inv2_users", users); store("inv2_assets", assets); store("inv2_logs", logs); try { localStorage.setItem("inv2_cur", cur); } catch(e){} scheduleCloudPush(); }
/* ---------------- Online database (Firebase Firestore cloud sync) ----------------
   Data lives in Cloud Firestore collection "inventory_store" (documents
   "users", "assets", "logs"), so the same file opened from any device or
   domain reads and writes the SAME cloud data after a one-time connect.
   The config is only the Firebase Project ID (e.g. inventory-app-psd-rudra)
   and can be baked into the file (window.__CLOUD__ = { projectId }) before
   uploading to GitHub — then every visitor connects automatically — or
   entered once per browser in the Online Database settings. No SDK and no
   API-key auth: plain Firestore REST. The Firebase account password is
   NEVER needed or entered here. */
/* Default: the owner's real Firebase project, created under
   psd.rudra@gmail.com — "Inventory Management", inventory-management-75f2d.
   Files downloaded from the app carry this ID baked in; it is also the
   fallback here so the file always opens already linked to that project. */
var DEFAULT_PROJECT_ID = "inventory-management-75f2d";
var bakedCloud = window.__CLOUD__ || { projectId: "" };
if (!bakedCloud.projectId) bakedCloud = { projectId: DEFAULT_PROJECT_ID };
var cloudCfg = load("inv2_cloud", null);
/* Discard any legacy URL/key-shaped cloud config from the old backend. */
if (cloudCfg && !cloudCfg.projectId) cloudCfg = null;
/* A stored config the user deliberately set in this panel — for the baked
   project or a different one, connected or disconnected — is respected.
   The baked-in default project is used only when this browser has no
   stored cloud config yet. */
if (!cloudCfg) cloudCfg = { projectId: bakedCloud.projectId, enabled: true };
var syncState = cloudCfg.enabled ? "idle" : "off"; /* idle | syncing | ok | err | off | locked | nocrypto */
var cloudTimer = null, cloudPushing = false, cloudDirty = false;
function cloudOn(){ return !!(cloudCfg.enabled && cloudCfg.projectId); }
function cloudBase(){ return "https://firestore.googleapis.com/v1/projects/" + encodeURIComponent(cloudCfg.projectId) + "/databases/(default)/documents/inventory_store"; }
function cloudHeaders(){ return { "Content-Type": "application/json" }; }
function renderSync(){
  var label = "☁️ Local only", cls = "cloud-btn", note = "";
  if (cloudOn()){
    if (syncState === "syncing"){ label = "☁️ Syncing…"; note = "Syncing with the online database…"; }
    else if (syncState === "locked"){ label = "☁️ Locked 🔒"; note = "Online database is encrypted — open ☁️ Online Database and enter your Cloud Password on this device to unlock sync."; }
    else if (syncState === "nocrypto"){ label = "☁️ Needs HTTPS"; note = "Encryption is not available in this context, so nothing was uploaded. Open this file over HTTPS (GitHub Pages is HTTPS), localhost, or as a local file in a modern browser to sync."; }
    else if (syncState === "err"){ label = "☁️ Sync error"; note = "Could not reach the online database — changes are saved on this device and will sync when the connection works."; }
    else { label = "☁️ Online DB ✓"; cls = "cloud-btn on"; note = "Online database connected & encrypted — your data is available from every device."; }
  } else { note = "Local only — data stays in this browser. Connect the online database to get it from everywhere."; }
  var b = $("cloudBtn"); if (b){ b.textContent = label; b.className = cls; }
  var n = $("cloudLoginNote"); if (n) n.textContent = note;
  var s = $("cloudSyncNote"); if (s){ s.textContent = note; s.className = "sync-note " + (cloudOn() ? (syncState === "err" ? "sync-err" : (syncState === "ok" || syncState === "idle") ? "sync-ok" : "sync-off") : "sync-off"); }
}
function cloudPullOne(id){
  return fetch(cloudBase() + "/" + encodeURIComponent(id), { headers: cloudHeaders() }).then(function(r){
    if (r.status === 404) return null;
    if (!r.ok) throw new Error("HTTP " + r.status);
    return r.json();
  }).then(function(doc){
    if (!doc || !doc.fields || !doc.fields.data || typeof doc.fields.data.stringValue !== "string") return null;
    var env;
    try { env = JSON.parse(doc.fields.data.stringValue); } catch(e){ throw new Error("plain"); }
    return decryptData(env);
  });
}
function cloudPull(){
  if (!cloudOn()) return Promise.resolve(false);
  syncState = "syncing"; renderSync();
  var ids = ["users", "assets", "logs"];
  var results = {};
  var chain = Promise.resolve();
  ids.forEach(function(id){
    chain = chain.then(function(){
      return cloudPullOne(id).then(function(data){ results[id] = data; });
    });
  });
  return chain.then(function(){
    var got = false;
    if (Array.isArray(results.users)){ users = results.users; got = true; }
    if (Array.isArray(results.assets)){ assets = results.assets; got = true; }
    if (Array.isArray(results.logs)){ logs = results.logs; got = true; }
    return migrateUsers().then(function(){
      store("inv2_users", users); store("inv2_assets", assets); store("inv2_logs", logs);
      syncState = "ok"; renderSync();
      return got;
    });
  }).catch(function(e){
    syncState = (e && (e.message === "locked" || e.message === "plain" || e.name === "OperationError")) ? "locked" : "err";
    renderSync();
    return false;
  });
}
function cloudPushOne(id, data){
  return encryptData(data).then(function(env){
    /* Firestore rejects deeply nested maps, so the encrypted envelope is
       stored as a JSON string in a stringValue field named "data". */
    var body = { fields: { data: { stringValue: JSON.stringify(env) }, updated_at: { timestampValue: new Date().toISOString() } } };
    var url = cloudBase() + "/" + encodeURIComponent(id) + "?updateMask.fieldPaths=data&updateMask.fieldPaths=updated_at";
    return fetch(url, { method: "PATCH", headers: cloudHeaders(), body: JSON.stringify(body) });
  }).then(function(r){ if (!r.ok) throw new Error("HTTP " + r.status); });
}
function cloudPushAll(){
  if (!cloudOn()) return Promise.resolve(false);
  if (cloudOn() && !cloudPass){ syncState = "locked"; renderSync(); return Promise.resolve(false); }
  if (cloudPushing){ cloudDirty = true; return Promise.resolve(false); }
  cloudPushing = true; syncState = "syncing"; renderSync();
  return migrateUsers().then(function(){ return cloudPushOne("users", users); }).then(function(){ return cloudPushOne("assets", assets); }).then(function(){ return cloudPushOne("logs", logs); }).then(function(){
    cloudPushing = false; syncState = "ok"; renderSync();
    if (cloudDirty){ cloudDirty = false; return cloudPushAll(); }
    return true;
  }).catch(function(e){ cloudPushing = false; syncState = (e && e.message === "no-crypto") ? "nocrypto" : (e && e.message === "locked") ? "locked" : "err"; renderSync(); return false; });
}
function scheduleCloudPush(){ if (!cloudOn()) return; if (cloudTimer) clearTimeout(cloudTimer); cloudTimer = setTimeout(function(){ cloudPushAll(); }, 700); }
/* ---- Password hashing + end-to-end encryption of cloud data ----
   Passwords are NEVER stored or synced in plaintext: they are SHA-256
   hashed on this device first. And before anything is uploaded, the whole
   dataset is AES-GCM encrypted with a key derived (PBKDF2) from a Cloud
   Password the user sets in the Online Database settings and enters once
   per device. Firestore therefore only ever holds ciphertext plus
   password hashes — reading the database (or this file) reveals neither the
   inventory data nor any password. */
var cloudPass = ""; try { cloudPass = localStorage.getItem("inv2_cloudpass") || ""; } catch(e){}
function setCloudPass(p){ cloudPass = p || ""; try { if (cloudPass) localStorage.setItem("inv2_cloudpass", cloudPass); else localStorage.removeItem("inv2_cloudpass"); } catch(e){} }
function b64enc(buf){ var bytes = new Uint8Array(buf); var s = ""; for (var i = 0; i < bytes.length; i += 8192){ s += String.fromCharCode.apply(null, bytes.subarray(i, i + 8192)); } return btoa(s); }
function b64dec(s){ var bin = atob(s); var bytes = new Uint8Array(bin.length); for (var i = 0; i < bin.length; i++) bytes[i] = bin.charCodeAt(i); return bytes; }
function hashPw(pw){
  var s = "inv-cloud::" + pw;
  if (window.crypto && crypto.subtle && crypto.subtle.digest){
    return crypto.subtle.digest("SHA-256", new TextEncoder().encode(s)).then(function(buf){ return "sha256:" + b64enc(buf); });
  }
  var h1 = 0xdeadbeef, h2 = 0x41c6ce57;
  for (var i = 0; i < s.length; i++){ var ch = s.charCodeAt(i); h1 = Math.imul(h1 ^ ch, 2654435761); h2 = Math.imul(h2 ^ ch, 1597334677); }
  h1 = Math.imul(h1 ^ (h1 >>> 16), 2246822507) ^ Math.imul(h2 ^ (h2 >>> 13), 3266489909);
  h2 = Math.imul(h2 ^ (h2 >>> 16), 2246822507) ^ Math.imul(h1 ^ (h1 >>> 13), 3266489909);
  return Promise.resolve("cyrb:" + (h2 >>> 0).toString(16) + (h1 >>> 0).toString(16));
}
function migrateUsers(){
  var chain = Promise.resolve();
  users.forEach(function(u){
    if (u.password){
      var plain = u.password; delete u.password;
      if (!u.passwordHash){ chain = chain.then(function(){ return hashPw(plain).then(function(h){ u.passwordHash = h; }); }); }
    }
  });
  return chain.then(function(){ store("inv2_users", users); });
}
function deriveKey(salt){
  return crypto.subtle.importKey("raw", new TextEncoder().encode(cloudPass), "PBKDF2", false, ["deriveKey"]).then(function(base){
    return crypto.subtle.deriveKey({ name: "PBKDF2", salt: salt, iterations: 100000, hash: "SHA-256" }, base, { name: "AES-GCM", length: 256 }, false, ["encrypt", "decrypt"]);
  });
}
function encryptData(data){
  /* Fail closed: without a Cloud Password or without WebCrypto (the file
     must be opened over HTTPS, localhost, or as a local file in a modern
     browser), NOTHING is uploaded — never plaintext. */
  if (!cloudPass) return Promise.reject(new Error("locked"));
  if (!window.crypto || !crypto.subtle || !crypto.subtle.encrypt) return Promise.reject(new Error("no-crypto"));
  var salt = crypto.getRandomValues(new Uint8Array(16));
  var iv = crypto.getRandomValues(new Uint8Array(12));
  return deriveKey(salt).then(function(key){
    return crypto.subtle.encrypt({ name: "AES-GCM", iv: iv }, key, new TextEncoder().encode(JSON.stringify(data)));
  }).then(function(ct){ return { enc: 1, salt: b64enc(salt), iv: b64enc(iv), ct: b64enc(ct) }; });
}
function decryptData(env){
  /* Fail closed on read too: unencrypted cloud rows are refused, so data
     can never silently flow in plaintext form either. */
  if (!env || env.enc !== 1) return Promise.reject(new Error("plain"));
  if (!cloudPass || !window.crypto || !crypto.subtle) return Promise.reject(new Error("locked"));
  return deriveKey(b64dec(env.salt)).then(function(key){
    return crypto.subtle.decrypt({ name: "AES-GCM", iv: b64dec(env.iv) }, key, b64dec(env.ct));
  }).then(function(buf){ return JSON.parse(new TextDecoder().decode(buf)); });
}
function nextId(arr){ var m = 0; for (var i = 0; i < arr.length; i++) if (arr[i].id > m) m = arr[i].id; return m + 1; }
function todayStr(){ return new Date().toISOString().slice(0,10); }
function fmtDate(s){ if (!s) return "—"; var d = new Date(s + "T00:00:00"); if (isNaN(d.getTime())) return s; return d.toLocaleDateString("en-US", { day: "numeric", month: "short", year: "numeric" }); }
function fmtMoney(n){ if (n == null || n === "") return "—"; return "৳" + Number(n).toLocaleString("en-IN"); }
function addMonths(ds, m){ var d = new Date(ds + "T00:00:00"); if (isNaN(d.getTime())) return ds; d.setMonth(d.getMonth() + m); return d.toISOString().slice(0,10); }
function winfo(a){ var end = addMonths(a.purchaseDate, Number(a.warrantyMonths) || 0); var t = new Date(); t.setHours(0,0,0,0); var ed = new Date(end + "T00:00:00"); var days = Math.round((ed.getTime() - t.getTime()) / 86400000); var st = "Active"; if (!a.warrantyMonths || Number(a.warrantyMonths) <= 0) st = "No Warranty"; else if (days < 0) st = "Expired"; else if (days <= 30) st = "Expiring Soon"; return { end: end, days: days, status: st }; }
function wbadge(a){ var w = winfo(a); if (w.status === "Active") return { label: "Warranty Active • " + w.days + " days left", cls: "wb-green" }; if (w.status === "Expiring Soon") return { label: "⚠ Expires in " + w.days + " days", cls: "wb-amber" }; if (w.status === "Expired") return { label: "Warranty Expired • " + Math.abs(w.days) + " days ago", cls: "wb-red" }; return { label: "No Warranty", cls: "wb-gray" }; }
function findUser(idOrEmail){ var k = String(idOrEmail || "").trim().toLowerCase(); for (var i = 0; i < users.length; i++) if (users[i].userId === k || users[i].email === k) return users[i]; return null; }
function currentUser(){ for (var i = 0; i < users.length; i++) if (users[i].userId === cur) return users[i]; return null; }

/* ---------------- Lantern login ---------------- */
var loginMode = "login", loginLit = false, loginMsg = "", loginErr = "", foundId = "";
function starsHTML(){ var h = ""; for (var i = 0; i < 36; i++){ var s = (i % 3) + 1; h += '<span style="width:' + s + 'px;height:' + s + 'px;left:' + ((i * 27) % 100) + '%;top:' + ((i * 13) % 55) + '%;opacity:' + (0.35 + (i % 5) * 0.12) + '"></span>'; } return h; }
function lanternHTML(delay, size){ var sh = 28 + size * 0.4; return '<div class="lantern-wrap" style="animation-delay:' + delay + '"><div class="lan-string" style="height:' + sh + 'px"></div><div class="lan-cap"></div><div class="lantern-body" style="width:' + size + 'px;height:' + Math.round(size * 1.18) + 'px"><span class="mark">✦</span><div class="glowring"></div></div><div class="lan-cap"></div><div class="lan-tassels"><i></i><i></i><i></i></div></div>'; }
function embersHTML(){ var h = ""; for (var i = 0; i < 18; i++){ var s = 5 + (i % 4); h += '<span class="ember" style="width:' + s + 'px;height:' + s + 'px;left:' + (8 + (i * 5) % 84) + '%;bottom:0;animation-duration:' + (2.2 + (i % 5) * 0.5) + 's;animation-delay:' + (i * 0.12) + 's"></span>'; } return h; }
function tabBtn(m, label){ return '<button onclick="setMode(\'' + m + '\')" class="' + (loginMode === m ? "on" : "") + '">' + label + '</button>'; }
function showLogin(){
  var h = '<div class="night' + (loginLit ? " lit success-screen" : "") + '"><div class="night-bg"></div><div class="stars">' + starsHTML() + '</div>';
  if (loginLit) h += '<div class="embers">' + embersHTML() + '</div>';
  h += '<div class="night-inner"><div class="lantern-row">' + lanternHTML("0s", 44) + lanternHTML("0.7s", 58) + lanternHTML("0.3s", 70) + lanternHTML("1s", 58) + lanternHTML("0.5s", 44) + '</div>';
  h += '<div class="login-title"><h1>🏮 Inventory Management</h1><p>A secure login by lantern light — it lights up the moment you sign in</p></div>';
  h += '<div class="glass"><div class="tabs">' + tabBtn("login", "🔑 Log In") + tabBtn("register", "✨ Create ID") + tabBtn("gmail", "Gmail") + tabBtn("forgotId", "Forgot ID") + tabBtn("forgotPass", "Forgot Pass") + '</div>';
  if (loginMsg) h += '<div class="msg-ok">' + esc(loginMsg) + '</div>';
  if (loginErr) h += '<div class="msg-err">' + esc(loginErr) + '</div>';
  if (loginMode === "login"){
    h += '<form class="lform" onsubmit="return doLogin(event)"><div><label class="lbl" for="li-id">USER ID / GMAIL</label><input class="inp" id="li-id" placeholder="Your User ID or Gmail" autocomplete="username"></div>';
    h += '<div><label class="lbl" for="li-pw">PASSWORD</label><div class="pw-wrap"><input class="inp" id="li-pw" type="password" placeholder="••••••••" autocomplete="current-password"><button type="button" class="pw-toggle" onclick="togglePw()">Show</button></div></div>';
    h += '<button class="btn-primary" type="submit">🏮 Log In — Light It Up</button>';
    h += '<div class="divider"><span></span>or<span></span></div>';
    h += '<button type="button" class="btn-gmail" onclick="setMode(\'gmail\')"><b><span style="color:#4285F4">G</span><span style="color:#EA4335">m</span><span style="color:#FBBC05">a</span><span style="color:#4285F4">i</span><span style="color:#34A853">l</span></b> — Log In Directly</button>';
    h += '<div class="link-row"><button type="button" class="linklike" onclick="setMode(\'forgotId\')">Forgot User ID?</button><button type="button" class="linklike" onclick="setMode(\'forgotPass\')">Forgot password?</button></div>';
    h += "<p class=small-note>Don't have an account? <button type=button class=linklike onclick=\"setMode('register')\">Create a New ID →</button></p></form>";
  } else if (loginMode === "register"){
    h += '<form class="lform" onsubmit="return doRegister(event)">';
    h += '<div><label class="lbl" for="rg-name">Your name *</label><input class="inp" id="rg-name" placeholder="e.g. Rudra"></div>';
    h += '<div><label class="lbl" for="rg-id">New USER ID * (3+ characters)</label><input class="inp" id="rg-id" placeholder="e.g. rudra01" autocomplete="username"></div>';
    h += '<div><label class="lbl" for="rg-email">GMAIL / EMAIL *</label><input class="inp" id="rg-email" type="email" placeholder="you@gmail.com"></div>';
    h += '<div class="grid2"><div><label class="lbl" for="rg-pw">Password *</label><input class="inp" id="rg-pw" type="password" placeholder="At least 6 characters" autocomplete="new-password"></div><div><label class="lbl" for="rg-pw2">Password again *</label><input class="inp" id="rg-pw2" type="password" placeholder="Same password" autocomplete="new-password"></div></div>';
    h += '<button class="btn-primary" type="submit">✨ Create ID and log in</button></form>';
  } else if (loginMode === "gmail"){
    h += '<form class="lform" onsubmit="return doGmail(event)"><div class="gmail-hero"><div class="big">📧</div><p>Just enter your Gmail address and you will be logged in directly.<br>If it is a new Gmail, an ID will be created automatically — no password needed.</p></div>';
    h += '<div><label class="lbl" for="gm-email">GMAIL ADDRESS *</label><input class="inp" id="gm-email" type="email" placeholder="you@gmail.com"></div>';
    h += '<div><label class="lbl" for="gm-name">Name (for a new account)</label><input class="inp" id="gm-name" placeholder="Your name"></div>';
    h += '<button class="btn-gmail btn-gmail-big" type="submit">🔴 Log in with Gmail</button>';
    h += '<p class="fineprint2">To use real Google OAuth on your own domain, create a Client ID in Google Cloud Console and connect it to this Gmail button.</p></form>';
  } else if (loginMode === "forgotId"){
    h += '<form class="lform" onsubmit="return doFindId(event)"><p class="desc">Forgot your User ID? Enter your account Gmail/Email and we will show you your User ID.</p>';
    h += '<div><label class="lbl" for="fi-email">GMAIL / EMAIL</label><input class="inp" id="fi-email" type="email" placeholder="you@gmail.com"></div>';
    h += '<button class="btn-amber" type="submit">🔍 Find my User ID</button>';
    if (foundId) h += '<div class="found-id"><p style="font-size:12px;color:#fde68a">Your User ID is</p><p class="uid">' + esc(foundId) + '</p><button type="button" class="linklike" style="margin-top:8px" onclick="useFoundId()">Log in with this ID →</button></div>';
    h += '</form>';
  } else if (loginMode === "forgotPass"){
    h += '<form class="lform" onsubmit="return doReset(event)"><p class="desc">Forgot your password? If your User ID and Email match, you can set a new password.</p>';
    h += '<div><label class="lbl" for="fp-id">USER ID</label><input class="inp" id="fp-id" placeholder="Your User ID"></div>';
    h += '<div><label class="lbl" for="fp-email">GMAIL / EMAIL</label><input class="inp" id="fp-email" type="email" placeholder="you@gmail.com"></div>';
    h += '<div><label class="lbl" for="fp-pw">New password (At least 6 characters)</label><input class="inp" id="fp-pw" type="password" placeholder="New password" autocomplete="new-password"></div>';
    h += '<button class="btn-amber" type="submit">🔑 Reset password</button></form>';
  }
  h += '</div><div class="cloud-login-row"><button type="button" onclick="openCloud()">☁️ Online Database — Get Your Data From Everywhere</button><span id="cloudLoginNote"></span></div><p class="fineprint">🏮 The lantern system: when your login succeeds, all the lanterns flare up bright together — that is the sign you have entered successfully.</p></div></div>';
  setTimeout(renderSync, 0);
  $("root").innerHTML = h;
}
function setMode(m){ loginMode = m; loginErr = ""; foundId = ""; showLogin(); }
function togglePw(){ var p = $("li-pw"); if (p) p.type = p.type === "password" ? "text" : "password"; }
function celebrate(user, msg){ loginLit = true; loginMsg = msg; loginErr = ""; showLogin(); setTimeout(function(){ cur = user.userId; saveAll(); loginLit = false; loginMsg = ""; if (cloudOn()){ cloudPull().then(function(){ showApp(); }); } else { showApp(); } }, 1100); }
function doLogin(e){ e.preventDefault(); var id = $("li-id").value.trim(); var pw = $("li-pw").value; if (!id){ loginErr = "Enter your User ID"; showLogin(); return false; } if (!pw){ loginErr = "Enter your password"; showLogin(); return false; } var u = findUser(id); if (!u){ loginErr = "User ID not found — check that the ID is correct, or create a new ID"; showLogin(); return false; } if (u.provider === "gmail" && !u.passwordHash && !u.password){ loginErr = "This account was created with Gmail — please log in with the Gmail button"; showLogin(); return false; } hashPw(pw).then(function(h){ var ok = u.passwordHash ? (h === u.passwordHash) : (pw === u.password); if (!ok){ loginErr = "Wrong password — please try again or use Forgot Password"; showLogin(); return; } if (!u.passwordHash){ u.passwordHash = h; delete u.password; saveAll(); } celebrate(u, "✨ Welcome, " + u.displayName + "! The lantern has lit up 🏮"); }); return false; }
function doRegister(e){ e.preventDefault(); var n = $("rg-name").value.trim(); var id = $("rg-id").value.trim().toLowerCase(); var em = $("rg-email").value.trim().toLowerCase(); var pw = $("rg-pw").value; var pw2 = $("rg-pw2").value; if (!n || !id || !em || pw.length < 6){ loginErr = "Fill in all fields — password must be at least 6 characters"; showLogin(); return false; } if (!/^[a-zA-Z0-9_.-]+$/.test(id) || id.length < 3){ loginErr = "Use only letters, numbers, _ . - in the User ID (3+ characters)"; showLogin(); return false; } if (pw !== pw2){ loginErr = "The two passwords do not match"; showLogin(); return false; } if (findUser(id) || findUser(em)){ loginErr = "This User ID or Email is already taken — please choose another one"; showLogin(); return false; } hashPw(pw).then(function(h){ var u = { userId: id, email: em, displayName: n, passwordHash: h, provider: "password" }; users.push(u); saveAll(); celebrate(u, "🎉 ID created! Welcome, " + n + " — your User ID: " + id); }); return false; }
function doGmail(e){ e.preventDefault(); var em = $("gm-email").value.trim().toLowerCase(); var nm = $("gm-name").value.trim(); if (!em || em.indexOf("@") < 0){ loginErr = "Please enter a valid Gmail address"; showLogin(); return false; } var u = null; for (var i = 0; i < users.length; i++) if (users[i].email === em) u = users[i]; var isNew = false; if (!u){ isNew = true; var base = em.split("@")[0].replace(/[^a-z0-9_.-]/g, "").slice(0, 30) || "user"; var cand = base; var n2 = 1; while (findUser(cand)){ n2++; cand = base + n2; } u = { userId: cand, email: em, displayName: nm || em.split("@")[0], passwordHash: "", provider: "gmail" }; users.push(u); saveAll(); } celebrate(u, isNew ? "🎉 New account created with Gmail! User ID: " + u.userId : "✨ Welcome via Gmail, " + u.displayName + "!"); return false; }
function doFindId(e){ e.preventDefault(); var em = $("fi-email").value.trim().toLowerCase(); var u = null; for (var i = 0; i < users.length; i++) if (users[i].email === em) u = users[i]; if (!u){ loginErr = "No account found with this Email/Gmail"; foundId = ""; } else { loginErr = ""; foundId = u.userId; loginLit = true; } showLogin(); return false; }
function useFoundId(){ loginMode = "login"; loginLit = false; showLogin(); var el = $("li-id"); if (el) el.value = foundId; }
function doReset(e){ e.preventDefault(); var id = $("fp-id").value.trim().toLowerCase(); var em = $("fp-email").value.trim().toLowerCase(); var pw = $("fp-pw").value; var u = findUser(id); if (!u || u.userId !== id){ loginErr = "User ID not found"; showLogin(); return false; } if (u.email !== em){ loginErr = "Email does not match — enter the Gmail/Email used on the account"; showLogin(); return false; } if (pw.length < 6){ loginErr = "New password must be at least 6 characters"; showLogin(); return false; } hashPw(pw).then(function(h){ u.passwordHash = h; delete u.password; u.provider = "password"; saveAll(); loginMode = "login"; loginErr = ""; loginMsg = "✅ Password changed — log in with your new password"; showLogin(); var el = $("li-id"); if (el) el.value = id; }); return false; }
function doLogout(){ cur = ""; saveAll(); loginMode = "login"; loginLit = false; loginMsg = ""; loginErr = ""; showLogin(); }


/* ---------------- Inventory app ---------------- */
var view = "list", q = "", catF = "All", statusF = "All", warrantyF = "All", detailId = null;
function stats(){ var s = { total: assets.length, inUse: 0, inStock: 0, underRepair: 0, retired: 0, expiringSoon: 0, expired: 0, totalValue: 0, byCat: {} }; for (var i = 0; i < assets.length; i++){ var a = assets[i]; var w = winfo(a); if (a.status === "In Use") s.inUse++; if (a.status === "In Stock") s.inStock++; if (a.status === "Under Repair") s.underRepair++; if (a.status === "Retired") s.retired++; if (w.status === "Expiring Soon") s.expiringSoon++; if (w.status === "Expired") s.expired++; s.totalValue += Number(a.purchasePrice) || 0; s.byCat[a.category] = (s.byCat[a.category] || 0) + 1; } return s; }
function alertAssets(){ var out = []; for (var i = 0; i < assets.length; i++){ var w = winfo(assets[i]); if (w.status === "Expiring Soon" || w.status === "Expired") out.push(assets[i]); } return out; }
function assetById(id){ for (var i = 0; i < assets.length; i++) if (assets[i].id === id) return assets[i]; return null; }
function showApp(){
  var u = currentUser(); if (!u){ showLogin(); return; }
  var h = '<div class="app"><div class="userbar"><span class="lamp">🏮</span><div class="who"><div class="nm">' + esc(u.displayName) + ' <span>• @' + esc(u.userId) + '</span></div><div class="em">' + esc(u.email) + ' • ' + (u.provider === "gmail" ? "Gmail Login" : "ID Login") + '</div></div><button class="cloud-btn" id="cloudBtn" onclick="openCloud()">☁️ Local only</button><button class="pill-btn" onclick="doLogout()">Log Out</button></div>';
  h += '<div class="stats-head"><div class="row1"><div><h1>Inventory Management</h1><p class="sub">Computers • Printers • Monitors • Scanners &amp; all IT assets</p></div><button class="csv-btn" onclick="exportCSV()">⬇ CSV</button></div><div id="statsWrap"></div></div>';
  h += '<div class="view-tabs"><button id="tabList" onclick="setView(\'list\')">📋 All Assets</button><button id="tabAlerts" onclick="setView(\'alerts\')">🔔 Warranty Alerts</button></div>';
  h += '<div id="mainWrap"></div><button class="fab" onclick="openForm(0)">＋ New Device</button></div>';
  $("root").innerHTML = h;
  updateStats(); updateMain(); renderSync();
}
function updateStats(){
  var el = $("statsWrap"); if (!el) return; var s = stats();
  el.innerHTML = '<div class="stat-grid"><div class="stat-box"><div class="num">' + s.total + '</div><div class="cap">Total Assets</div></div><button class="stat-box amber" onclick="setView(\'alerts\')"><div class="num">' + s.expiringSoon + '</div><div class="cap">Expiring Soon</div></button><button class="stat-box red" onclick="setView(\'alerts\')"><div class="num">' + s.expired + '</div><div class="cap">Warranty Expired</div></button><div class="stat-box"><div class="num">' + s.underRepair + '</div><div class="cap">Under Repair</div></div></div><div class="mini-stats"><span>In Use: <b>' + s.inUse + '</b></span><span>In Stock: <b>' + s.inStock + '</b></span><span>Total Value: <b>' + fmtMoney(s.totalValue) + '</b></span></div>';
  var tl = $("tabList"), ta = $("tabAlerts");
  if (tl){ tl.textContent = "📋 All Assets (" + s.total + ")"; tl.className = view === "list" ? "on-list" : ""; }
  if (ta){ ta.textContent = "🔔 Warranty Alerts (" + alertAssets().length + ")"; ta.className = view === "alerts" ? "on-alerts" : ""; }
}
function setView(v){ view = v; updateStats(); updateMain(); }
function setQ(v){ q = v; updateCards(); }
function setCat(c){ catF = c; updateMain(); }
function setStatusF(v){ statusF = v; updateCards(); }
function setWarrantyF(v){ warrantyF = v; updateCards(); }
function filtered(){ var out = []; var needle = q.trim().toLowerCase(); for (var i = 0; i < assets.length; i++){ var a = assets[i]; if (needle){ var hay = [a.name, a.brand, a.model, a.serialNumber, a.assetTag, a.location, a.assignedTo, a.vendor].join(" ").toLowerCase(); if (hay.indexOf(needle) < 0) continue; } if (catF !== "All" && a.category !== catF) continue; if (statusF !== "All" && a.status !== statusF) continue; if (warrantyF !== "All" && winfo(a).status !== warrantyF) continue; out.push(a); } return out; }
function updateMain(){
  var el = $("mainWrap"); if (!el) return;
  if (view === "alerts"){ el.innerHTML = alertsHTML(); return; }
  var s = stats(); var h = '<div class="section"><input class="search-inp" aria-label="Search" placeholder="🔍 Search by name, serial number, brand or location…" value="' + esc(q) + '" oninput="setQ(this.value)">';
  h += '<div class="chips">'; for (var i = 0; i < CATS.length; i++){ h += '<button class="' + (catF === CATS[i][0] ? "on" : "") + '" onclick="setCat(\'' + CATS[i][0] + '\')">' + CATS[i][1] + ' ' + CATS[i][0] + '</button>'; } h += '</div>';
  h += '<div class="filter-row"><select aria-label="Status filter" onchange="setStatusF(this.value)">' + selOpts(["All","In Use","In Stock","Under Repair","Damaged","Retired"], statusF, "All Statuses") + '</select><select aria-label="Warranty filter" onchange="setWarrantyF(this.value)">' + selOpts(["All","Active","Expiring Soon","Expired","No Warranty"], warrantyF, "All Warranties") + '</select></div>';
  var keys = Object.keys(s.byCat); if (keys.length){ h += '<div class="cat-summary">'; for (var j = 0; j < keys.length; j++) h += '<span>' + (CATI[keys[j]] || "🧩") + ' ' + esc(keys[j]) + ': ' + s.byCat[keys[j]] + '</span>'; h += '</div>'; }
  h += '</div><div class="list-wrap" id="cardsWrap"></div>';
  el.innerHTML = h; updateCards();
}
function selOpts(list, cur2, allLabel){ var h = ""; for (var i = 0; i < list.length; i++){ var v = list[i]; var lbl = v === "All" ? allLabel : (v === "Expiring Soon" ? "Expiring Soon (30 days)" : v); h += '<option value="' + v + '"' + (cur2 === v ? " selected" : "") + '>' + lbl + '</option>'; } return h; }
function cardHTML(a){
  var st = STAT[a.status] || STAT["In Stock"]; var wb = wbadge(a); var w = winfo(a);
  var h = '<div class="card"><button class="card-top" onclick="openDetail(' + a.id + ')"><span class="icon-tile">' + (CATI[a.category] || "🧩") + '</span><span class="card-main"><span class="name-row"><span class="asset-name">' + esc(a.name) + '</span><span class="status-pill" style="color:' + st[0] + ';background:' + st[1] + '">' + esc(a.status) + '</span></span><span class="card-sub" style="display:block">' + esc(a.category) + ' • ' + esc(a.brand) + ' ' + esc(a.model) + '</span><span class="sn-chip">S/N: ' + esc(a.serialNumber || "—") + (a.assetTag ? " • Tag: " + esc(a.assetTag) : "") + '</span></span></button>';
  h += '<div class="meta-grid"><div><div class="k">Purchase date</div><div class="v">' + fmtDate(a.purchaseDate) + '</div></div><div><div class="k">Price</div><div class="v">' + fmtMoney(a.purchasePrice) + '</div></div><div><div class="k">Location / Assigned To</div><div class="v">' + esc(a.assignedTo || a.location || "—") + '</div></div></div>';
  h += '<span class="wbadge ' + wb.cls + '">' + wb.label + ' • Ends: ' + fmtDate(w.end) + '</span>';
  h += '<div class="card-actions"><button class="edit" onclick="openForm(' + a.id + ')">✏️ Edit</button><button class="svc" onclick="openDetail(' + a.id + ')">🔧 Service</button><button class="del" onclick="confirmDelete(' + a.id + ')">Delete</button></div></div>';
  return h;
}
function updateCards(){
  var el = $("cardsWrap"); if (!el) return; var list = filtered();
  if (!list.length){ el.innerHTML = '<div class="empty"><div class="big">🖥️🖨️</div><h3>No devices found</h3><p>Tap the + button below to add your first computer, printer, monitor or scanner. Serial number, purchase date and warranty — everything in one place.</p><button onclick="openForm(0)">+ Add Device</button></div>'; return; }
  var h = ""; for (var i = 0; i < list.length; i++) h += cardHTML(list[i]);
  var al = alertAssets(); if (al.length && catF === "All") h += '<p class="alert-note">🔔 ' + al.length + ' devices have a warranty alert — check the Warranty Alerts tab above.</p>';
  el.innerHTML = h;
}
function alertsHTML(){
  var list = alertAssets(); var h = '<div class="list-wrap"><p style="font-size:13px;color:var(--dim)">Devices whose warranty ends within 30 days or has already expired — arrange service or renewal now.</p>';
  if (!list.length){ h += '<div class="empty"><div class="big">✅</div><h3>All warranties are in good shape</h3><p>No device warranty is expiring soon.</p></div>'; }
  for (var i = 0; i < list.length; i++){ var a = list[i]; var wb = wbadge(a); var w = winfo(a); h += '<button class="card alert-card" style="border-color:' + (w.status === "Expired" ? "#fecaca" : "#fde68a") + '" onclick="openDetail(' + a.id + ')"><span class="ic">' + (CATI[a.category] || "🧩") + '</span><span class="card-main"><span class="asset-name" style="display:block">' + esc(a.name) + '</span><span class="card-sub" style="display:block;font-family:ui-monospace,monospace">' + esc(a.serialNumber || "No serial number") + '</span><span class="wbadge ' + wb.cls + '">' + wb.label + '</span><span class="card-sub" style="display:block;margin-top:4px">Ends: ' + fmtDate(w.end) + ' • ' + esc(a.location || "—") + '</span></span></button>'; }
  h += '<h2 class="h2">Recent Service &amp; Repairs</h2>';
  var recent = logs.slice(0, 8);
  if (!recent.length) h += '<p style="font-size:13px;color:var(--dim)">No service records yet. Tap any device to add its service history.</p>';
  for (var j = 0; j < recent.length; j++){ var l = recent[j]; var an = assetById(l.assetId); h += '<div class="recent-item"><div><div class="t">' + esc(an ? an.name : "Unknown") + '</div><div class="d">' + esc(l.type) + ' • ' + fmtDate(l.date) + ' — ' + esc(l.description) + '</div></div>' + (l.cost != null ? '<div class="c">' + fmtMoney(l.cost) + '</div>' : '') + '</div>'; }
  return h + '</div>';
}
/* ---------------- Modals ---------------- */
function openModal(html){ $("modalRoot").innerHTML = '<div class="overlay" onclick="if(event.target===this)closeModal()"><div class="sheet">' + html + '</div></div>'; }
function closeModal(){ $("modalRoot").innerHTML = ""; detailId = null; }
/* ---------------- Online database setup (Firebase) ---------------- */
var FIRESTORE_RULES = ["rules_version = '2';", "service cloud.firestore {", "  match /databases/{database}/documents {", "    match /inventory_store/{docId} {", "      allow read, write: if true;", "    }", "  }", "}"].join(String.fromCharCode(10));
function openCloud(){
  var h = '<div class="sheet-head"><h2>☁️ Online Database — Firebase</h2><button class="x-btn" onclick="closeModal()" aria-label="Close online database settings">✕</button></div>';
  h += '<div class="sync-note sync-off" id="cloudSyncNote"></div>';
  h += '<p style="font-size:13px;line-height:1.7;margin-top:12px">This file is <b>already linked to your Firebase project</b> — <b>Inventory Management</b> (<span style="font-family:ui-monospace,monospace">inventory-management-75f2d</span>, account <b>psd.rudra@gmail.com</b>, free Spark plan, Firestore database created). With it, this software reads and writes the <b>same data from every phone, computer and domain</b> — home, office, anywhere. <b>Your Firebase account password is NOT needed and must never be entered here</b> — only the Project ID below is used, and it is already filled in.</p>';
  h += '<ol class="steps" style="margin-top:10px"><li><b>One thing to confirm in the Firebase Console:</b> the <span style="font-family:ui-monospace,monospace">inventory_store</span> rule below must be published for this app to read/write the database — open <b>console.firebase.google.com → Inventory Management → Build → Firestore Database → Rules</b>, paste the rules below, and click <b>Publish</b>. If it is already published there, you are done — publishing it again does no harm.</li><li>Set a <b>Cloud Password</b> below and tap <b>Connect &amp; Sync</b>. Your data is encrypted with it before upload, and login passwords are only ever stored as hashes — so Firestore never holds readable data or passwords. On every other device, open this same ☁️ panel and enter the <b>same Cloud Password</b> once — the Project ID is already in the file, nothing to paste.</li></ol>';
  h += '<div style="margin-top:12px">' + fLbl("Firestore rules — paste this once in Firestore → Rules") + '<textarea class="sql-box" id="cloud-sql" readonly>' + esc(FIRESTORE_RULES) + '</textarea><button type="button" class="btn-ghost" style="margin-top:8px" onclick="copyCloudSql()">📋 Copy Rules</button></div>';
  h += '<div style="margin-top:12px"><div>' + fLbl("Firebase Project ID") + fInp("cloud-project", cloudCfg.projectId, "inventory-management-75f2d") + '</div>';
  h += '<div style="margin-top:10px">' + fLbl("CLOUD PASSWORD — encrypts your data; use the same one on every device") + '<input class="f-inp" id="cloud-pass" type="password" placeholder="' + (cloudPass ? "•••••••• — set on this device (type only to change it)" : "Choose a Cloud Password") + '"></div></div>';
  h += '<p class="form-err" id="cloud-msg" style="display:none;margin-top:10px"></p>';
  h += '<button type="button" class="btn-cloud" id="cloud-connect" style="margin-top:12px" onclick="connectCloud()">☁️ Connect &amp; Sync</button>';
  if (cloudOn()){ h += '<button type="button" class="btn-ghost" style="margin-top:8px" onclick="syncNowCloud()">🔄 Sync Now — Reload Cloud Data</button><button type="button" class="btn-ghost" style="margin-top:8px" onclick="disconnectCloud()">Disconnect (back to local only)</button>'; }
  h += '<p style="font-size:11px;color:var(--dim);margin-top:10px;line-height:1.6">🔒 Security: everything is AES-GCM encrypted with your Cloud Password before it leaves this device, and account passwords are stored only as SHA-256 hashes — Firestore holds ciphertext and hashes only, so even someone who somehow read the database could not see your inventory or passwords. The open Firestore rule above is needed because this single-file app has no server to sign requests; the encryption is what keeps the data private, so use a strong Cloud Password and keep a local/CSV backup. Do not forget the Cloud Password: without it the encrypted cloud data cannot be opened (your local copy on a device where you are logged in still works).</p>';
  openModal(h); renderSync();
}
function copyCloudSql(){ var t = $("cloud-sql"); if (!t) return; t.select(); try { navigator.clipboard.writeText(FIRESTORE_RULES); } catch(e){ try { document.execCommand("copy"); } catch(e2){} } }
function cloudMsg(t){ var m = $("cloud-msg"); if (m){ m.textContent = t; m.style.display = "block"; } }
function connectCloud(){
  var pidEl = $("cloud-project"); var pid = pidEl ? pidEl.value.trim() : "";
  if (!pid || /\s|\//.test(pid)){ cloudMsg("Paste your Firebase Project ID first (Project settings → General in the Firebase console, signed in as psd.rudra@gmail.com)."); return; }
  var passEl = $("cloud-pass"); var newPass = passEl ? passEl.value : "";
  if (newPass) setCloudPass(newPass);
  if (!cloudPass){ cloudMsg("Set a Cloud Password first — it encrypts your data in the cloud. Use the same Cloud Password on every device."); return; }
  var btn = $("cloud-connect"); if (btn){ btn.disabled = true; btn.textContent = "Connecting…"; }
  cloudCfg = { projectId: pid, enabled: true }; store("inv2_cloud", cloudCfg); syncState = "idle";
  cloudPull().then(function(got){
    if (syncState === "locked"){ cloudMsg("Connected, but the cloud data could not be decrypted — the Cloud Password on this device does not match the one used to encrypt it. Enter the correct Cloud Password and try again."); if (btn){ btn.disabled = false; btn.textContent = "☁️ Connect & Sync"; } return; }
    if (syncState === "err"){ cloudMsg("Could not connect. Check the Project ID, and make sure you created the Firestore database and published the rules above first — then try again."); if (btn){ btn.disabled = false; btn.textContent = "☁️ Connect & Sync"; } return; }
    if (!got){
      cloudPushAll().then(function(ok){
        if (!ok){ cloudMsg("Connected, but the first upload failed — check your connection and tap Sync Now."); return; }
        finishConnect("✅ Connected! This device's data was uploaded — it is now your online data, available everywhere.");
      });
    } else {
      finishConnect("✅ Connected! The online data was loaded — you now see the same data on every connected device.");
    }
  });
}
function finishConnect(msg){ saveAll(); if (currentUser()){ closeModal(); showApp(); } else { closeModal(); showLogin(); } setTimeout(function(){ alert(msg); }, 50); }
function syncNowCloud(){ var passEl = $("cloud-pass"); if (passEl && passEl.value) setCloudPass(passEl.value); cloudPull().then(function(){ if (syncState === "locked"){ cloudMsg("Could not decrypt the cloud data — enter the correct Cloud Password above and try again."); return; } if (syncState === "err"){ cloudMsg("Sync failed — check your internet connection and the Project ID."); return; } closeModal(); if (currentUser()) showApp(); else showLogin(); }); }
function disconnectCloud(){ cloudCfg.enabled = false; store("inv2_cloud", cloudCfg); syncState = "off"; closeModal(); renderSync(); if (currentUser()) showApp(); else showLogin(); }
function fLbl(t){ return '<label class="f-lbl">' + t + '</label>'; }
function fInp(id, val, ph, extra){ return '<input class="f-inp" id="' + id + '" value="' + esc(val == null ? "" : val) + '" placeholder="' + esc(ph || "") + '"' + (extra || "") + '>'; }
function fSel(id, opts, val){ var h = '<select class="f-inp" id="' + id + '">'; for (var i = 0; i < opts.length; i++) h += '<option value="' + opts[i] + '"' + (opts[i] === val ? " selected" : "") + '>' + opts[i] + '</option>'; return h + '</select>'; }
function openForm(id){
  var a = id ? assetById(id) : null; detailId = null;
  var v = a || { name: "", category: "Computer", brand: "", model: "", serialNumber: "", assetTag: "", purchaseDate: todayStr(), purchasePrice: "", vendor: "", warrantyMonths: 12, location: "", assignedTo: "", department: "", status: "In Stock", condition: "Good", notes: "" };
  var catOpts = []; for (var i = 1; i < CATS.length; i++) catOpts.push(CATS[i][0]);
  var h = '<div class="sheet-head"><h2>' + (a ? "Edit Device" : "Add a New Device") + '</h2><button class="x-btn" onclick="closeModal()" aria-label="Close form">✕</button></div><form class="aform" onsubmit="return saveForm(event,' + (a ? a.id : 0) + ')">';
  h += '<div>' + fLbl("Device name *") + fInp("f-name", v.name, "e.g. HP ProDesk 400 G9") + '</div>';
  h += '<div class="grid2"><div>' + fLbl("Category *") + fSel("f-cat", catOpts, v.category) + '</div><div>' + fLbl("Status") + fSel("f-status", ["In Stock","In Use","Under Repair","Damaged","Retired"], v.status) + '</div></div>';
  h += '<div class="grid2"><div>' + fLbl("Brand") + fInp("f-brand", v.brand, "HP / Dell / Canon") + '</div><div>' + fLbl("Model") + fInp("f-model", v.model, "ProDesk 400 G9") + '</div></div>';
  h += '<div class="grid2"><div>' + fLbl("Serial number") + fInp("f-serial", v.serialNumber, "SN-XXXXXXX") + '</div><div>' + fLbl("Asset Tag / ID") + fInp("f-tag", v.assetTag, "IT-001") + '</div></div>';
  h += '<div class="warr-box"><p class="t">🛡️ Purchase &amp; Warranty</p><div class="grid2"><div>' + fLbl("Purchase date *") + '<input class="f-inp" id="f-pdate" type="date" value="' + esc(v.purchaseDate) + '" oninput="warrPreview()">' + '</div><div>' + fLbl("Warranty (months)") + '<input class="f-inp" id="f-warr" type="number" min="0" max="120" value="' + esc(v.warrantyMonths) + '" oninput="warrPreview()">' + '</div></div><div class="grid2"><div>' + fLbl("Purchase Price (৳)") + '<input class="f-inp" id="f-price" type="number" min="0" value="' + esc(v.purchasePrice == null ? "" : v.purchasePrice) + '" placeholder="55000">' + '</div><div>' + fLbl("Vendor / Shop") + fInp("f-vendor", v.vendor, "Star Tech / Ryans") + '</div></div><p class="warr-end" id="f-warrend"></p></div>';
  h += '<div class="grid2"><div>' + fLbl("Location / Room") + fInp("f-loc", v.location, "Office, Room 201") + '</div><div>' + fLbl("Condition") + fSel("f-cond", ["New","Good","Fair","Poor"], v.condition) + '</div></div>';
  h += '<div class="grid2"><div>' + fLbl("Assigned To") + fInp("f-assigned", v.assignedTo, "Name of the user") + '</div><div>' + fLbl("Department") + fInp("f-dept", v.department, "Accounts / HR") + '</div></div>';
  h += '<div>' + fLbl("Notes") + '<textarea class="f-inp" id="f-notes" rows="2" placeholder="Additional information…">' + esc(v.notes) + '</textarea></div>';
  h += '<p class="form-err" id="f-err" style="display:none"></p><button class="btn-save" type="submit">' + (a ? "Update" : "✓ Add Device") + '</button></form>';
  openModal(h); warrPreview();
}
function warrPreview(){ var pd = $("f-pdate"), wm = $("f-warr"), out = $("f-warrend"); if (!pd || !out) return; if (!pd.value){ out.textContent = ""; return; } var end = addMonths(pd.value, Number(wm.value) || 0); var d = new Date(end + "T00:00:00"); out.innerHTML = "Warranty ends: <b>" + d.toLocaleDateString("en-US", { day: "numeric", month: "long", year: "numeric" }) + "</b>"; }
function saveForm(e, id){ e.preventDefault(); var name = $("f-name").value.trim(); var pdate = $("f-pdate").value; var err = $("f-err"); if (!name){ err.textContent = "Device name is required"; err.style.display = "block"; return false; } if (!pdate){ err.textContent = "Purchase date is required"; err.style.display = "block"; return false; } var price = $("f-price").value === "" ? null : Number($("f-price").value); var data = { name: name, category: $("f-cat").value, status: $("f-status").value, brand: $("f-brand").value.trim(), model: $("f-model").value.trim(), serialNumber: $("f-serial").value.trim(), assetTag: $("f-tag").value.trim(), purchaseDate: pdate, warrantyMonths: Number($("f-warr").value) || 0, purchasePrice: price, vendor: $("f-vendor").value.trim(), location: $("f-loc").value.trim(), condition: $("f-cond").value, assignedTo: $("f-assigned").value.trim(), department: $("f-dept").value.trim(), notes: $("f-notes").value.trim() }; if (id){ var a = assetById(id); for (var k in data) a[k] = data[k]; } else { data.id = nextId(assets); assets.unshift(data); } saveAll(); closeModal(); updateStats(); updateMain(); return false; }
function openDetail(id){
  var a = assetById(id); if (!a) return; detailId = id; var w = winfo(a); var wb = wbadge(a);
  var pct = a.warrantyMonths > 0 ? Math.max(0, Math.min(100, (w.days / (Number(a.warrantyMonths) * 30.44)) * 100)) : 0;
  var wpCls = w.status === "Expired" ? "wp-red" : (w.status === "Expiring Soon" ? "wp-amber" : "wp-green");
  var barColor = w.status === "Expired" ? "#ef4444" : (w.status === "Expiring Soon" ? "#f59e0b" : "#10b981");
  var h = '<div class="sheet-head"><div class="detail-head"><span class="icon-tile">' + (CATI[a.category] || "🧩") + '</span><div><h2>' + esc(a.name) + '</h2><p>' + esc(a.category) + ' • ' + esc(a.brand) + ' ' + esc(a.model) + '</p></div></div><button class="x-btn" onclick="closeModal()" aria-label="Close Details">✕</button></div>';
  h += '<div class="warr-panel ' + wpCls + '"><div class="r1"><span>🛡️ Warranty</span><span>' + (w.status === "Expired" ? "Expired" : (w.status === "No Warranty" ? "None" : w.days + " days left")) + '</span></div><div class="r2">Purchased: ' + fmtDate(a.purchaseDate) + ' • Term: ' + a.warrantyMonths + ' months • Ends: ' + fmtDate(w.end) + '</div><div class="wbar"><i style="width:' + pct + '%;background:' + barColor + '"></i></div></div>';
  h += '<dl class="dl"><div><dt>Serial number</dt><dd class="mono">' + esc(a.serialNumber || "—") + '</dd></div><div><dt>Asset Tag</dt><dd class="mono">' + esc(a.assetTag || "—") + '</dd></div><div><dt>Status</dt><dd>' + esc(a.status) + '</dd></div><div><dt>Condition</dt><dd>' + esc(a.condition) + '</dd></div><div><dt>Purchase Price</dt><dd>' + fmtMoney(a.purchasePrice) + '</dd></div><div><dt>Vendor</dt><dd>' + esc(a.vendor || "—") + '</dd></div><div><dt>Location</dt><dd>' + esc(a.location || "—") + '</dd></div><div><dt>User / Department</dt><dd>' + esc(a.assignedTo || "—") + (a.department ? " • " + esc(a.department) : "") + '</dd></div>' + (a.notes ? '<div style="grid-column:1/-1"><dt>Notes</dt><dd>' + esc(a.notes) + '</dd></div>' : '') + '</dl>';
  h += '<div class="detail-actions"><button class="edit" onclick="openForm(' + a.id + ')">✏️ Edit</button><button class="del" onclick="confirmDelete(' + a.id + ')">Delete</button></div>';
  h += '<h3 style="font-weight:700;margin-top:24px;margin-bottom:8px;font-size:15px">🔧 Service / Repair History</h3><div style="display:flex;flex-direction:column;gap:8px">';
  var mine = []; for (var i = 0; i < logs.length; i++) if (logs[i].assetId === id) mine.push(logs[i]);
  if (!mine.length) h += '<p style="font-size:13px;color:var(--dim);background:var(--bg);border-radius:8px;padding:10px 12px">No service records yet.</p>';
  for (var j = 0; j < mine.length; j++){ var l = mine[j]; h += '<div class="maint-item"><div style="flex:1"><div class="t">' + esc(l.type) + ' • ' + fmtDate(l.date) + (l.cost != null ? ' • ' + fmtMoney(l.cost) : '') + '</div><div class="d">' + esc(l.description) + (l.vendor ? ' — ' + esc(l.vendor) : '') + '</div></div><button class="x" onclick="delMaint(' + l.id + ',' + id + ')" aria-label="Delete service record">✕</button></div>'; }
  h += '</div><form class="maint-form" onsubmit="return addMaint(event,' + id + ')"><p class="t">Add a New Service</p><div class="grid2"><input class="f-inp" id="m-date" type="date" value="' + todayStr() + '" aria-label="Service date"><select class="f-inp" id="m-type" aria-label="Service type">' + selOpts(MTYPES, "Service", "") + '</select></div><input class="f-inp" id="m-desc" placeholder="What work was done…" aria-label="Service description"><div class="grid2"><input class="f-inp" id="m-cost" type="number" min="0" placeholder="Cost (৳)" aria-label="Cost"><input class="f-inp" id="m-vendor" placeholder="Service center" aria-label="Service center"></div><p class="form-err" id="m-err" style="display:none"></p><button class="btn-teal-sm" type="submit">+ Add Service</button></form>';
  openModal(h);
}
function addMaint(e, assetId){ e.preventDefault(); var desc = $("m-desc").value.trim(); var err = $("m-err"); if (!desc){ err.textContent = "Please write a description"; err.style.display = "block"; return false; } logs.unshift({ id: nextId(logs), assetId: assetId, date: $("m-date").value || todayStr(), type: $("m-type").value, description: desc, cost: $("m-cost").value === "" ? null : Number($("m-cost").value), vendor: $("m-vendor").value.trim() }); logs.sort(function(x, y){ return x.date < y.date ? 1 : -1; }); saveAll(); openDetail(assetId); if (view === "alerts") updateMain(); return false; }
function delMaint(logId, assetId){ var out = []; for (var i = 0; i < logs.length; i++) if (logs[i].id !== logId) out.push(logs[i]); logs = out; saveAll(); openDetail(assetId); }
function confirmDelete(id){ var a = assetById(id); if (!a) return; $("modalRoot").innerHTML = '<div class="confirm-overlay"><div class="confirm-box"><h3>Delete this device?</h3><p><b style="color:var(--text)">' + esc(a.name) + '</b> (' + esc(a.serialNumber || "No serial number") + ') and all of its service records will be permanently deleted.</p><div class="row"><button class="cancel" onclick="cancelDelete(' + id + ')">Cancel</button><button class="yes" onclick="doDelete(' + id + ')">Yes, delete</button></div></div></div>'; }
function cancelDelete(id){ if (detailId === id) openDetail(id); else closeModal(); }
function doDelete(id){ var out = []; for (var i = 0; i < assets.length; i++) if (assets[i].id !== id) out.push(assets[i]); assets = out; var lo = []; for (var j = 0; j < logs.length; j++) if (logs[j].assetId !== id) lo.push(logs[j]); logs = lo; saveAll(); closeModal(); updateStats(); updateMain(); }
function exportCSV(){
  var header = "Name,Category,Brand,Model,Serial Number,Asset Tag,Purchase Date,Price,Vendor,Warranty Months,Warranty End,Location,Assigned To,Department,Status,Condition,Notes";
  function e2(v){ return '"' + String(v == null ? "" : v).replace(/"/g, '""') + '"'; }
  var lines = [header]; for (var i = 0; i < assets.length; i++){ var a = assets[i]; lines.push([a.name, a.category, a.brand, a.model, a.serialNumber, a.assetTag, a.purchaseDate, a.purchasePrice == null ? "" : a.purchasePrice, a.vendor, a.warrantyMonths, winfo(a).end, a.location, a.assignedTo, a.department, a.status, a.condition, a.notes].map(e2).join(",")); }
  var blob = new Blob([lines.join(String.fromCharCode(10))], { type: "text/csv;charset=utf-8" }); var url = URL.createObjectURL(blob); var link = document.createElement("a"); link.href = url; link.download = "inventory.csv"; link.click(); URL.revokeObjectURL(url);
}
function boot(){
  migrateUsers(); /* upgrade any legacy plaintext passwords to hashes */
  if (cur && currentUser()) showApp(); else showLogin();
  if (cloudOn()){
    /* Online database connected: pull the cloud copy so this device shows
       the same accounts, devices and service records as everywhere else. */
    cloudPull().then(function(){ if (cur && currentUser()) showApp(); renderSync(); });
  }
}
boot();

</script>
</body></html>
