---
title: "企业AI行业动态与常见问答 - 麦朴"
description: "麦朴新闻中心发布企业AI行业动态、产品更新、AI落地与AI提效洞察及活动预告，汇总AI培训、Agent定制、Token供应、WorkBuddy培训等领域客户最关心的常见问题与专业解答。"
keywords: "企业AI,AI落地,AI培训,AI提效,Agent定制,Token供应,WorkBuddy培训,麦朴"
nav: "news"
date: 2026-11-18
draft: false
---

<style>
:root{
--ink:#0a0e1a;
--ink-2:#1a2236;
--brand:#1d4ed8;
--brand-2:#1e4ca8;
--brand-glow:rgba(30,76,168,.12);
--accent:#d9480f;
--accent-soft:rgba(217,72,15,.08);
--text:#0a0e1a;
--text-2:#5a6577;
--text-3:#9aa4b8;
--bg:#fafbfd;
--bg-card:#ffffff;
--bg-soft:#f4f6fa;
--bg-deep:#0a0e1a;
--bg-deep-2:#141a2e;
--border:#ebedf3;
--border-soft:#f0f2f7;
--radius:12px;
--radius-lg:18px;
--radius-xl:24px;
--shadow-xs:0 1px 2px rgba(10,14,26,.03);
--shadow-sm:0 2px 8px rgba(10,14,26,.04);
--shadow:0 8px 32px rgba(10,14,26,.06);
--shadow-lg:0 24px 64px rgba(10,14,26,.08);
--maxw:1280px;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
font-family:"PingFang SC","HarmonyOS Sans SC","Microsoft YaHei",system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
color:var(--text);background:linear-gradient(135deg,#eaf2fc 0%,#ffffff 25%,#f0f6fc 50%,#ffffff 75%,#eaf2fc 100%);background-size:400% 400%;animation:bgFlow 22s ease-in-out infinite;line-height:1.7;font-size:15px;
-webkit-font-smoothing:antialiased;overflow-x:hidden;letter-spacing:.005em;
}
a{color:inherit;text-decoration:none}
img{display:block;max-width:100%}

/* ===== WebGL 流体背景 ===== */
#fluid-wrap{position:fixed;inset:0;z-index:1;pointer-events:none;overflow:hidden;mix-blend-mode:multiply;opacity:.7}
#fluid-wrap canvas{display:block;width:100%;height:100%}

/* ===== 容器 ===== */
.wrap{max-width:var(--maxw);margin:0 auto;padding:0 32px;position:relative;z-index:2}

/* ===== Hero ===== */
.hero{position:relative;padding:100px 0 56px;min-height:520px;overflow:hidden;background: #eaf2fc url(/assets/img/20260814/ban3.png) center / cover no-repeat;}
.hero-inner{max-width:960px}
.hero-eyebrow{display:inline-flex;align-items:center;gap:14px;font-size:11.5px;color:var(--brand);font-weight:600;margin-bottom:32px;letter-spacing:.18em;text-transform:uppercase}
.hero-eyebrow .line{width:40px;height:1px;background:linear-gradient(90deg,var(--brand),transparent)}
.hero h1{font-size:clamp(38px,5.5vw,46px);line-height:1.12;font-weight:800;letter-spacing:-.03em;margin-bottom:28px;color:var(--ink)}
.hero h1 .em{
background:linear-gradient(135deg,#1e4ca8 0%,#1d4ed8 100%);
-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;
}
.hero .sub{font-size:clamp(15px,1.2vw,17px);line-height:1.9;color:var(--text-2);max-width:620px;margin-bottom:40px;font-weight:400}
.hero-metrics{display:flex;align-items:center;gap:0;margin-bottom:44px;flex-wrap:wrap}
.hero-metric{padding:0 36px 0 0;margin-right:36px;border-right:1px solid var(--border)}
.hero-metric:last-child{border-right:none;margin-right:0;padding-right:0}
.hero-metric .num{font-size:32px;font-weight:800;color:var(--ink);letter-spacing:-.03em;line-height:1;font-variant-numeric:tabular-nums}
.hero-metric .num .unit{font-size:15px;font-weight:600;color:var(--text-2);margin-left:2px}
.hero-metric .label{font-size:12px;color:var(--text-3);margin-top:8px;letter-spacing:.04em}
.hero-cta{display:flex;gap:14px;flex-wrap:wrap}
.btn{display:inline-flex;align-items:center;gap:8px;padding:14px 30px;border-radius:10px;font-size:14.5px;font-weight:500;cursor:pointer;transition:all .3s cubic-bezier(.22,1,.36,1);border:1px solid transparent;font-family:inherit;white-space:nowrap;letter-spacing:.01em}
.btn svg{width:16px;height:16px;transition:transform .3s}
.btn-primary{background:var(--accent);color:#fff;box-shadow:0 4px 24px rgba(217,72,15,.3)}
.btn-primary:hover{background:#c2410c;transform:translateY(-2px);box-shadow:0 8px 32px rgba(217,72,15,.4)}
.btn-primary:hover svg{transform:translateY(2px)}
.btn-ghost{background:transparent;color:var(--ink);border-color:var(--border)}
.btn-ghost:hover{border-color:var(--accent);background:var(--accent);color:#fff;transform:translateY(-2px)}

/* ===== 区块标题通用 ===== */
.sec-head{margin-bottom:56px}
.sec-eyebrow{font-size:11.5px;font-weight:600;color:var(--brand);letter-spacing:.18em;text-transform:uppercase;margin-bottom:16px;display:flex;align-items:center;gap:12px}
.sec-eyebrow .dot{width:6px;height:6px;border-radius:50%;background:var(--brand)}
.sec-title{font-size:clamp(28px,3.2vw,40px);font-weight:800;color:var(--ink);letter-spacing:-.025em;line-height:1.25}
.sec-title .em{color:var(--brand)}
.sec-sub{font-size:15px;color:var(--text-2);max-width:520px;margin-top:16px;line-height:1.85}

/* ===== 置顶要闻 ===== */
.featured{padding:80px 0 100px}
.featured-card{
position:relative;background:var(--bg-card);border:1px solid var(--border-soft);border-radius:var(--radius-xl);
overflow:hidden;display:grid;grid-template-columns:1.05fr 1fr;
box-shadow:var(--shadow);transition:box-shadow .5s;
}
.featured-card:hover{box-shadow:var(--shadow-lg)}
.featured-visual{position:relative;overflow:hidden;background:linear-gradient(135deg,#0a0e1a,#141a2e);}
.featured-visual::before{
content:"";position:absolute;inset:0;
background:radial-gradient(circle at 30% 40%,rgba(30,76,168,.4),transparent 55%),radial-gradient(circle at 80% 80%,rgba(217,72,15,.15),transparent 50%);
}
.featured-visual::after{
content:"";position:absolute;inset:0;
background-image:
linear-gradient(rgba(255,255,255,.03) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.03) 1px,transparent 1px);
background-size:40px 40px;
}
.featured-badge{
position:absolute;top:32px;left:32px;z-index:2;display:flex;align-items:center;gap:10px;
padding:8px 16px;border-radius:100px;background:rgba(255,255,255,.08);backdrop-filter:blur(12px);
border:1px solid rgba(255,255,255,.12);font-size:11.5px;font-weight:600;color:rgba(255,255,255,.7);letter-spacing:.06em;text-transform:uppercase
}
.featured-badge .dot{width:6px;height:6px;border-radius:50%;background:var(--accent);box-shadow:0 0 12px var(--accent)}
.featured-visual .v-title{
position:absolute;bottom:32px;left:32px;right:32px;z-index:2;
font-size:clamp(24px,2.6vw,34px);font-weight:800;color:#fff;letter-spacing:-.02em;line-height:1.35;
}
.featured-visual .v-date{position:absolute;bottom:32px;right:32px;z-index:2;font-size:12px;color:rgba(255,255,255,.4);letter-spacing:.08em;font-variant-numeric:tabular-nums}
.featured-body{padding:18px 52px;display:flex;flex-direction:column;justify-content:center}
.featured-tag{font-size:11px;font-weight:700;color:var(--accent);letter-spacing:.14em;text-transform:uppercase;margin-bottom:20px}
.featured-body h3{font-size:clamp(22px,2.4vw,30px);font-weight:800;color:var(--ink);letter-spacing:-.02em;line-height:1.35;margin-bottom:20px}
.featured-body .excerpt{font-size:14.5px;color:var(--text-2);line-height:1.9;margin-bottom:28px}
.featured-meta{display:flex;align-items:center;gap:12px;margin-bottom:28px;flex-wrap:wrap}
.featured-meta .chip{font-size:12px;font-weight:600;padding:6px 14px;border-radius:8px;background:var(--bg-soft);border:1px solid var(--border);color:var(--text-2)}
.featured-read{display:inline-flex;align-items:center;gap:8px;font-size:14px;font-weight:600;color:var(--ink);padding-top:24px;border-top:1px solid var(--border-soft);transition:all .3s;align-self:flex-start}
.featured-read svg{width:15px;height:15px;transition:transform .3s}
.featured-card:hover .featured-read{color:var(--brand);gap:12px}
.featured-card:hover .featured-read svg{transform:translateX(3px)}

/* ===== 新闻列表 ===== */
.news-section{padding:100px 0 120px;background:var(--bg-card);border-top:1px solid var(--border)}
.news-head{display:flex;align-items:flex-end;justify-content:space-between;gap:32px;margin-bottom:56px;flex-wrap:wrap}
.news-filter{display:flex;gap:6px;flex-wrap:wrap;background:var(--bg-soft);border:1px solid var(--border);border-radius:12px;padding:5px}
.news-filter button{padding:9px 18px;font-size:13px;color:var(--text-2);background:transparent;border:none;border-radius:8px;cursor:pointer;transition:all .3s cubic-bezier(.22,1,.36,1);font-family:inherit;font-weight:500}
.news-filter button:hover{color:var(--ink)}
.news-filter button.active{background: #2563eb;color: #fff;font-weight: 600;}

.news-list{display:flex;flex-direction:column}
.news-item{
position:relative;display:grid;grid-template-columns:216px 128px 1fr auto;gap:36px;align-items:center;
padding:28px 8px;border-bottom:1px solid var(--border-soft);border-radius:12px;
transition:background .35s,padding .35s cubic-bezier(.22,1,.36,1),opacity .4s,transform .4s;
}
.news-item:first-child{border-top:1px solid var(--border-soft)}
.news-item::before{
content:"";position:absolute;left:0;top:20%;bottom:20%;width:3px;border-radius:3px;
background:linear-gradient(180deg,var(--c,var(--brand)),transparent);
transform:scaleY(0);transform-origin:center;transition:transform .4s cubic-bezier(.22,1,.36,1);
}
.news-item:hover{background:var(--bg-soft);padding-left:32px;padding-right:20px}
.news-item:hover::before{transform:scaleY(1)}

/* 新闻配图 */
.news-thumb{
position:relative;width:216px;aspect-ratio:16/10;border-radius:10px;overflow:hidden;
background:var(--bg-soft);flex-shrink:0;
box-shadow:var(--shadow-xs);transition:box-shadow .4s;
}
.news-thumb img{width:100%;height:100%;object-fit:cover;display:block;transition:transform .7s cubic-bezier(.22,1,.36,1),filter .5s}
.news-thumb::after{
content:"";position:absolute;inset:0;pointer-events:none;
background:linear-gradient(180deg,transparent 45%,color-mix(in srgb,var(--c,var(--brand)) 30%,transparent));
opacity:.5;transition:opacity .4s;
}
.news-item:hover .news-thumb{box-shadow:0 8px 24px -8px color-mix(in srgb,var(--c,var(--brand)) 40%,transparent)}
.news-item:hover .news-thumb img{transform:scale(1.07)}
.news-item:hover .news-thumb::after{opacity:.85}

.news-date{display:flex;flex-direction:column;gap:6px}
.news-date .d{font-size:30px;font-weight:800;color:var(--ink);letter-spacing:-.03em;line-height:1;font-variant-numeric:tabular-nums}
.news-date .m{font-size:12px;color:var(--text-3);letter-spacing:.1em;text-transform:uppercase;font-variant-numeric:tabular-nums}
.news-main{min-width:0}
.news-cat{display:inline-flex;align-items:center;gap:8px;font-size:11px;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--c,var(--brand));margin-bottom:10px}
.news-cat::before{content:"";width:16px;height:1px;background:var(--c,var(--brand))}
.news-main h3{
font-size:19px;font-weight:700;color:var(--ink);letter-spacing:-.015em;line-height:1.5;margin-bottom:8px;
transition:color .3s;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;
}
.news-item:hover .news-main h3{color:var(--c,var(--brand))}
.news-main p{font-size:13.5px;color:var(--text-2);line-height:1.75;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}
.news-arrow{
width:44px;height:44px;border-radius:50%;border:1px solid var(--border);display:flex;align-items:center;justify-content:center;
color:var(--text-3);transition:all .35s cubic-bezier(.22,1,.36,1);flex-shrink:0;
}
.news-arrow svg{width:16px;height:16px;transition:transform .35s}
.news-item:hover .news-arrow{background:var(--c,var(--brand));border-color:var(--c,var(--brand));color:#fff;transform:rotate(-45deg)}
.news-item.hide{opacity:0;transform:translateY(12px) scale(.985);pointer-events:none}

/* 新闻分类主题色 */
.n-company{--c:#1e4ca8}
.n-product{--c:#059669}
.n-insight{--c:#7c3aed}
.n-event{--c:#d9480f}

/* ===== FAQ ===== */
.faq-section{padding:120px 0;background:var(--bg);position:relative}
.faq-layout{display:grid;grid-template-columns:340px 1fr;gap:80px;align-items:start}
.faq-aside{position:sticky;top:40px}
.faq-aside .sec-head{margin-bottom:32px}
.faq-aside .help-card{
background:var(--bg-card);border:1px solid var(--border-soft);border-radius:var(--radius-lg);
padding:32px;box-shadow:var(--shadow-sm);
}
.faq-aside .help-card h4{font-size:16px;font-weight:700;color:var(--ink);margin-bottom:10px;letter-spacing:-.01em}
.faq-aside .help-card p{font-size:13px;color:var(--text-2);line-height:1.8;margin-bottom:20px}
.faq-aside .help-card a.btn{width:100%;justify-content:center;padding:12px 20px;font-size:13.5px}

.faq-list{display:flex;flex-direction:column;gap:14px}
.faq-item{
background:var(--bg-card);border:1px solid var(--border-soft);border-radius:var(--radius);
overflow:hidden;transition:border-color .35s,box-shadow .35s;
}
.faq-item:hover{border-color:var(--border)}
.faq-item.open{border-color:rgba(30,76,168,.3);box-shadow:var(--shadow)}
.faq-q{
width:100%;display:flex;align-items:center;gap:20px;padding:24px 28px;background:none;border:none;
cursor:pointer;text-align:left;font-family:inherit;font-size:15.5px;font-weight:600;color:var(--ink);
line-height:1.6;letter-spacing:-.01em;transition:color .3s;
}
.faq-item.open .faq-q{color:var(--brand)}
.faq-q .idx{
font-size:12px;font-weight:700;color:var(--text-3);font-variant-numeric:tabular-nums;letter-spacing:.05em;
width:28px;flex-shrink:0;transition:color .3s;
}
.faq-item.open .faq-q .idx{color:var(--brand)}
.faq-q .txt{flex:1}
.faq-q .icon{
position:relative;width:18px;height:18px;flex-shrink:0;transition:transform .4s cubic-bezier(.22,1,.36,1);
}
.faq-q .icon::before,.faq-q .icon::after{
content:"";position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);
background:currentColor;border-radius:2px;transition:all .35s;
}
.faq-q .icon::before{width:14px;height:1.5px}
.faq-q .icon::after{width:1.5px;height:14px}
.faq-item.open .faq-q .icon{transform:rotate(180deg);color:var(--brand)}
.faq-item.open .faq-q .icon::after{height:0;opacity:0}
.faq-a{
display:grid;grid-template-rows:0fr;transition:grid-template-rows .45s cubic-bezier(.22,1,.36,1);
}
.faq-item.open .faq-a{grid-template-rows:1fr}
.faq-a-inner{overflow:hidden}
.faq-a .content{
padding:0 28px 28px 76px;font-size:14px;color:var(--text-2);line-height:1.95;
}
.faq-a .content strong{color:var(--ink);font-weight:600}
.faq-a .content ul{list-style:none;margin-top:10px}
.faq-a .content li{position:relative;padding-left:18px;margin-bottom:4px}
.faq-a .content li::before{content:"";position:absolute;left:0;top:.75em;width:7px;height:7px;border-radius:2px;background:var(--brand);opacity:.5;transform:rotate(45deg)}
.faq-a .content a{color:var(--brand);font-weight:600;border-bottom:1px solid rgba(30,76,168,.25);transition:all .25s}
.faq-a .content a:hover{color:var(--accent);border-color:var(--accent)}

/* ===== CTA ===== */
.cta-section{padding:0 0 120px}
.cta-band{
position:relative;background:#eaf2fc url(banner-visual.png) center/cover no-repeat;border-radius:var(--radius-xl);
padding:72px 64px;overflow:hidden
}
.cta-band::before{
content:"";position:absolute;top:-50%;right:-20%;width:70%;height:200%;
background:radial-gradient(circle,rgba(30,76,168,.35),transparent 60%);pointer-events:none
}
.cta-band::after{
content:"";position:absolute;inset:0;
background-image:
linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);
background-size:48px 48px;pointer-events:none
}
.cta-inner{position:relative;z-index:2;display:flex;align-items:center;justify-content:space-between;gap:48px;flex-wrap:wrap}
.cta-text h2{font-size:clamp(24px,2.8vw,36px);font-weight:800;color:var(--ink);letter-spacing:-.025em;line-height:1.3;margin-bottom:20px;max-width:560px}
.cta-text p{font-size:14.5px;color:rgba(10,14,26,.6);line-height:1.85;max-width:480px}
.cta-actions{display:flex;gap:14px;flex-wrap:wrap;margin-top:32px}
.cta-actions .btn-primary{background:var(--accent);color:#fff;box-shadow:0 4px 24px rgba(217,72,15,.3)}
.cta-actions .btn-primary:hover{background:#c2410c;transform:translateY(-2px);box-shadow:0 8px 32px rgba(217,72,15,.4)}
.cta-actions .btn-accent{background:#fff;color:var(--ink);border:1px solid var(--border)}
.cta-actions .btn-accent:hover{background:var(--bg-soft);transform:translateY(-2px)}
.cta-contact{
background:rgba(255,255,255,.7);border:1px solid rgba(10,14,26,.08);border-radius:var(--radius-lg);
padding:32px;backdrop-filter:blur(12px);display:flex;flex-direction:column;gap:20px;min-width:300px
}
.cta-contact .row{display:flex;align-items:flex-start;gap:14px;color:var(--ink)}
.cta-contact .row svg{width:20px;height:20px;color:var(--text-3);flex-shrink:0;margin-top:2px}
.cta-contact .row .label{color:var(--text-3);font-size:11.5px;display:block;margin-bottom:4px;letter-spacing:.06em;text-transform:uppercase}
.cta-contact .row .val{font-size:14.5px;font-weight:500}

/* ===== 滚动渐入 ===== */
.reveal{opacity:0;transform:translateY(36px);transition:opacity .8s cubic-bezier(.22,1,.36,1),transform .8s cubic-bezier(.22,1,.36,1)}
.reveal.in{opacity:1;transform:none}
.reveal-d1{transition-delay:.1s}
.reveal-d2{transition-delay:.2s}
.reveal-d3{transition-delay:.3s}
.reveal-d4{transition-delay:.4s}
.reveal-d5{transition-delay:.5s}

@keyframes bgFlow{0%{background-position:0% 50%}50%{background-position:100% 50%}100%{background-position:0% 50%}}

/* ===== 响应式 ===== */
@media(max-width:1080px){
.featured-card{grid-template-columns:1fr}
.featured-visual{min-height:320px}
.featured-body{padding:40px 36px}
.faq-layout{grid-template-columns:1fr;gap:48px}
.faq-aside{position:static}
.news-item{grid-template-columns:150px 100px 1fr;gap:20px}
.news-thumb{width:150px;aspect-ratio:4/3}
.news-arrow{display:none}
}
@media(max-width:860px){
.hero{padding:80px 0 48px;min-height:460px}
.hero-metric{padding:0 24px 0 0;margin-right:24px}
.hero-metric .num{font-size:26px}
.featured,.news-section,.faq-section{padding:72px 0}
.cta-section{padding:0 0 80px}
.cta-band{padding:48px 36px}
.featured-body{padding:32px 28px}
.news-item{grid-template-columns:1fr;gap:16px;padding:26px 8px}
.news-item:hover{padding-left:24px}
.news-thumb{width:100%;aspect-ratio:16/7}
.news-main h3{white-space:normal}
.news-main p{white-space:normal}
.news-date{flex-direction:row;align-items:baseline;gap:10px}
.news-date .d{font-size:24px}
.faq-q{padding:20px 20px;font-size:14.5px;gap:12px}
.faq-a .content{padding:0 20px 24px 52px}
.faq-q .idx{width:20px}
}
@media(max-width:560px){
.hero{min-height:380px;padding:60px 0 40px}
.news-head{flex-direction:column;align-items:flex-start}
.cta-inner{flex-direction:column;align-items:flex-start}
.cta-band{padding:40px 24px;border-radius:var(--radius-lg)}
.cta-contact{width:100%}
.hero-metrics{flex-direction:column;align-items:flex-start;gap:24px}
.hero-metric{padding:0;margin-right:0;border-right:none;border-bottom:1px solid var(--border);padding-bottom:20px;margin-right:0}
.hero-metric:last-child{border-bottom:none;padding-bottom:0}
.faq-a .content{padding:0 20px 24px 20px}
}

/* ===== 无障碍 ===== */
@media (prefers-reduced-motion: reduce){
.reveal{opacity:1;transform:none;transition:none}
*{animation-duration:.01ms!important;transition-duration:.01ms!important}
}
</style>


<!-- WebGL 流体背景 -->
<div id="fluid-wrap"></div>

<!-- Hero -->
<header class="hero" id="top">
<div class="wrap">
<div class="hero-inner">
<div class="hero-eyebrow reveal"><span class="line"></span>NEWS CENTER · 新闻中心</div>
<h1 class="reveal reveal-d1">动态与思考，<br>都在 <span class="em">AI 落地的路上</span></h1>
<p class="sub reveal reveal-d2">这里有麦朴的最新动态、产品发布与行业洞察，也有客户最关心的常见问题。我们相信透明与专业，是企业级服务的起点。</p>
<div class="hero-metrics reveal reveal-d3">
<div class="hero-metric">
<div class="num">30<span class="unit">+ 篇/年</span></div>
<div class="label">动态与洞察持续更新</div>
</div>
<div class="hero-metric">
<div class="num">12<span class="unit"> 条</span></div>
<div class="label">高频问答即时解答</div>
</div>
<div class="hero-metric">
<div class="num">15<span class="unit">+ 场/年</span></div>
<div class="label">线上线下活动分享</div>
</div>
</div>
<div class="hero-cta reveal reveal-d4">
<a href="#news" class="btn btn-primary">浏览最新动态 <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M12 5v14M5 12l7 7 7-7"/></svg></a>
<a href="#faq" class="btn btn-ghost">查看常见问答</a>
</div>
</div>
</div>
</header>

<!-- 置顶要闻 -->
<section class="featured" id="headline">
<div class="wrap">
<div class="sec-head reveal">
<div class="sec-eyebrow"><span class="dot"></span>HEADLINE · 本月要闻</div>
<h2 class="sec-title">麦朴蝉联<span class="em">腾讯云华南殿堂级服务商</span></h2>
<p class="sec-sub">凭借企业级交付能力与客户口碑，麦朴再次通过腾讯云最高等级服务商认证，继续稳居华南最大代理商之列。</p>
</div>
<div class="featured-card reveal reveal-d1">
<div class="featured-visual">
<img src="/assets/img/article/20260804/20260804150518_947081.jpg" loading="lazy">
<div class="featured-badge"><span class="dot"></span>要闻头条</div>
<div class="v-title">以最高等级资质，<br>服务华南企业智能化升级</div>
<div class="v-date">2017-08-22</div>
</div>
<div class="featured-body">
<div class="featured-tag">公司动态 · 资质认证</div>
<h3>麦朴为克拉波互娱提供大模型Token聚合服务，AI调用成本降低42%</h3>
<p class="excerpt">近日，广州麦朴科技有限公司宣布，其为国内新锐游戏研发厂商——克拉波互娱游戏提供的大模型Token供应与AI工具服务取得突破性成果 ...</p>
<div class="featured-meta">
<span class="chip">殿堂级 · 最高等级</span>
<span class="chip">华南最大代理商</span>
<span class="chip">云 + AI 双引擎</span>
</div>
<a href="/news-kelabo-token.html" class="featured-read">阅读全文 <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M13 6l6 6-6 6"/></svg></a>
</div>
</div>
</div>
</section>

<!-- 新闻列表 -->
<section class="news-section" id="news">
<div class="wrap">
<div class="news-head reveal">
<div>
<div class="sec-eyebrow"><span class="dot"></span>LATEST · 企业动态</div>
<h2 class="sec-title">最新<span class="em">动态与洞察</span></h2>
</div>
<div class="news-filter">
<button class="active" data-filter="all">全部</button>
<button data-filter="company">公司动态</button>
<button data-filter="insight">行业新闻</button>
</div>
</div>

<div class="news-list" id="newsList">

<a href="/news-kelabo-token.html" class="news-item n-company reveal" data-cat="company">
<div class="news-thumb"><img src="/assets/img/article/20260804/20260804150518_947081.jpg"  loading="lazy"></div>
<div class="news-date"><span class="d">08-22</span><span class="m">2017</span></div>
<div class="news-main">
<span class="news-cat">公司动态</span>
<h3>麦朴为克拉波互娱提供大模型Token聚合服务，AI调用成本降低42%</h3>
<p>近日，广州麦朴科技有限公司宣布，其为国内新锐游戏研发厂商——克拉波互娱游戏提供的大模型Token供应与AI工具服务取得突破性成果。经过10个月的持续合作，麦朴的Token聚合供应方案帮助克拉波 ...</p>
</div>
<div class="news-arrow"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M13 6l6 6-6 6"/></svg></div>
</a><a href="/news-jinyi-agent.html" class="news-item n-company reveal" data-cat="company">
<div class="news-thumb"><img src="/assets/img/article/20260804/20260804150624_012056.png"  loading="lazy"></div>
<div class="news-date"><span class="d">08-16</span><span class="m">2017</span></div>
<div class="news-main">
<span class="news-cat">公司动态</span>
<h3>麦朴为广东金亿防护定制企业级AI Agent，售前接待响应时效缩短70%</h3>
<p>近日，广州麦朴科技有限公司宣布，其为华南安全防护用品领军企业——广东金亿防护定制的企业级AI智能体（Agent）项目成功落地并取得显著成效。经过8个月的深度合作，麦朴为金亿防护搭建的售前智能接 ...</p>
</div>
<div class="news-arrow"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M13 6l6 6-6 6"/></svg></div>
</a><a href="/news-banana-climbing.html" class="news-item n-company reveal" data-cat="company">
<div class="news-thumb"><img src="/assets/img/article/20260804/20260804150717_627442.jpg"  loading="lazy"></div>
<div class="news-date"><span class="d">08-16</span><span class="m">2017</span></div>
<div class="news-main">
<span class="news-cat">公司动态</span>
<h3>麦朴携手香蕉攀岩，AI运营工具与培训陪跑助力连锁品牌效率提升210%</h3>
<p>近日，广州麦朴科技有限公司宣布，其为国内攀岩连锁场馆TOP品牌——香蕉攀岩提供的AI运营工具与培训陪跑服务取得显著成效。经过6个月的深度合作，香蕉攀岩全员AI工具应用覆盖率达90%，门店内容产出效 ...</p>
</div>
<div class="news-arrow"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M13 6l6 6-6 6"/></svg></div>
</a><a href="/news-gac-cloud-cooperation.html" class="news-item n-company reveal" data-cat="company">
<div class="news-thumb"><img src="/assets/img/article/20260804/20260804150828_990105.jpg"  loading="lazy"></div>
<div class="news-date"><span class="d">08-16</span><span class="m">2017</span></div>
<div class="news-main">
<span class="news-cat">公司动态</span>
<h3>麦朴与广汽集团达成年度云计算与AI落地战略合作，助力世界500强企业数字化转型</h3>
<p>近日，广州麦朴科技有限公司与广汽集团正式签署年度云计算与AI落地战略合作协议。作为《财富》世界500强企业、中国汽车行业头部企业，广汽集团选择麦朴作为其云计算与AI落地的战略合作伙伴，标志着微 ...</p>
</div>
<div class="news-arrow"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M5 12h14M13 6l6 6-6 6"/></svg></div>
</a>   

<div class="pages">
<div class="qilin_pager">

</div>
</div> 




</div>
</div>
</section>

<!-- 常见问答 -->
<section class="faq-section" id="faq">
<div class="wrap">
<div class="faq-layout">

<aside class="faq-aside reveal">
<div class="sec-head">
<div class="sec-eyebrow"><span class="dot"></span>FAQ · 常见问答</div>
<h2 class="sec-title">您可能想<span class="em">先了解</span></h2>
<p class="sec-sub">采购前的高频问题，都在这里。没有找到答案？直接联系我们。</p>
</div>
<div class="help-card">
<h4>还有其他问题？</h4>
<p>商务团队工作日 9:00–18:00 在线，通常 2 小时内响应。也可以先预约一次免费场景诊断。</p>
<a href="tel:18926108189" class="btn btn-primary">电话咨询 <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.127.96.36 1.903.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.34 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg></a>
</div>
</aside>

<div class="faq-list" id="faqList">

<div class="faq-item open reveal">
<button class="faq-q" aria-expanded="true">
<span class="idx">01</span>
<span class="txt">麦朴具体提供哪些服务？分别解决什么问题？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
麦朴围绕企业 AI 能力建设提供<strong>七大产品、可独立采购也可组合交付</strong>：
<ul>
<li><strong>AI 提效</strong> —— 学·用·建·管一站式闭环，解决「不会用、用不好」的问题</li>
<li><strong>云计算服务</strong> —— 腾讯云华南殿堂级服务商，架构咨询、迁移部署、运维托管、成本优化</li>
<li><strong>AI 落地</strong> —— 五步法交付，让具体业务场景真正用上 AI</li>
<li><strong>AI 转型</strong> —— 战略与场景咨询、知识库建设咨询、内化体系咨询</li>
<li><strong>Agent 定制</strong> —— FDE 现场共创，知识问答、客服、销售辅助等七类 Agent</li>
<li><strong>Token 供应</strong> —— GPT、Gemini 等主流模型用量，成本约官网 45 折</li>
<li><strong>WorkBuddy 培训</strong> —— 线上 + 线下七大模块，50 席起购</li>
</ul>
</div></div></div>
</div>

<div class="faq-item reveal reveal-d1">
<button class="faq-q" aria-expanded="false">
<span class="idx">02</span>
<span class="txt">我们是传统行业，员工 AI 基础薄弱，从哪里开始？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
大多数客户的起点是<strong>WorkBuddy 培训 + 场景诊断</strong>：先用标准化课程建立全员 AI 通识与工具使用能力（方案 B 标准化课程包，50 席起），同时由顾问完成业务场景盘点，识别 3–5 个高价值场景；再通过<strong>方案 A 诊断式定制训练营</strong>针对重点部门做场景化训练。跑通「培训 → 场景 → 落地」的第一段闭环后，再决定是否进入 Agent 定制或深度咨询。
</div></div></div>
</div>

<div class="faq-item reveal reveal-d1">
<button class="faq-q" aria-expanded="false">
<span class="idx">03</span>
<span class="txt">Token 成本「约官网 45 折」是怎么回事？有没有隐性限制？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
麦朴以<strong>企业级代理规模</strong>向模型方统一采购用量，再按企业实际消耗结算，因此单价显著低于个人官网充值（约 45 折）。采购 WorkBuddy 50 席以上的客户另获 <strong>2000 元模型兑换券</strong>。没有隐藏条款：支持的模型（GPT、Gemini 等）、计量方式、结算周期均在合同中明确，并配套<strong>用量看板与预算告警</strong>，成本透明可控。
</div></div></div>
</div>

<div class="faq-item reveal reveal-d2">
<button class="faq-q" aria-expanded="false">
<span class="idx">04</span>
<span class="txt">Agent 定制的交付流程是怎样的？需要我们投入多少人力？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
我们采用 <strong>FDE（现场解决方案工程）五步法</strong>：
<ul>
<li><strong>场景定义</strong> —— 与业务方共同圈定高价值场景</li>
<li><strong>知识流程</strong> —— 梳理知识来源与业务流程</li>
<li><strong>原型</strong> —— 快速构建可试用 Agent 原型</li>
<li><strong>测试试点</strong> —— 小范围真实业务验证</li>
<li><strong>推广交接</strong> —— 全面推广并完成能力交接</li>
</ul>
客户侧通常只需<strong>1 名业务对接人 + 若干场景专家按需参与</strong>（累计约 5–8 个工作日），重活由我们的 FDE 工程师承担。
</div></div></div>
</div>

<div class="faq-item reveal reveal-d2">
<button class="faq-q" aria-expanded="false">
<span class="idx">05</span>
<span class="txt">企业数据安全吗？知识库和模型调用会不会造成数据外泄？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
数据安全是企业级服务的底线。方案基于<strong>腾讯云企业级基础设施</strong>部署（麦朴为腾讯云华南殿堂级服务商），支持私有化/专有云形态；知识库数据<strong>存储在客户自有空间</strong>，模型调用支持企业独立密钥与审计日志；敏感行业可配置数据脱敏与访问权限分级。所有数据处理条款写入合同，绝不将客户数据用于任何二次用途。
</div></div></div>
</div>

<div class="faq-item reveal reveal-d3">
<button class="faq-q" aria-expanded="false">
<span class="idx">06</span>
<span class="txt">培训是线上还是线下？课程可以按我们行业定制吗？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
两种形态都支持。<strong>线上</strong>：WorkBuddy 平台使用与 Prompt 工程课程；<strong>线下</strong>：七大模块（AI 通识 / AI 思维 / AI Cost Optimization / Vibe Coding / 业务场景训练营 / 个人知识库等）。两种采购模式：
<ul>
<li><strong>方案 A · 诊断式定制训练营</strong> —— 先诊断业务痛点，课程案例全部替换为贵司真实场景</li>
<li><strong>方案 B · 标准化课程包</strong> —— 成熟课程直接开班，快速覆盖全员</li>
</ul>
</div></div></div>
</div>

<div class="faq-item reveal reveal-d3">
<button class="faq-q" aria-expanded="false">
<span class="idx">07</span>
<span class="txt">云计算服务只面向已经在用腾讯云的企业吗？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
不是。我们服务三类客户：<strong>计划上云</strong>的企业（架构选型与规划）、<strong>已在用腾讯云</strong>的企业（架构优化、运维托管、成本优化，通常能找到 10%–30% 的降本空间）、以及<strong>多云环境</strong>中希望统一治理的企业。作为华南最大代理商，我们还能提供官方渠道的商务政策支持。
</div></div></div>
</div>

<div class="faq-item reveal reveal-d4">
<button class="faq-q" aria-expanded="false">
<span class="idx">08</span>
<span class="txt">一项 AI 落地项目通常周期多长？怎么衡量效果？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
单场景 Agent 原型通常 <strong>2–4 周</strong>可试用，试点验证 4–8 周，随后进入推广交接。效果衡量在项目启动前就与客户共同定义，常见指标包括：任务耗时下降、人工工时节省、Token 成本优化幅度、培训后 AI 使用率等。我们坚持<strong>「先定义指标，再开始项目」</strong>，避免交付无法量化的「演示级 AI」。
</div></div></div>
</div>

<div class="faq-item reveal reveal-d4">
<button class="faq-q" aria-expanded="false">
<span class="idx">09</span>
<span class="txt">采购门槛高吗？中小企业是否适合？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
七大产品均可<strong>独立采购、小步启动</strong>：WorkBuddy 培训 50 席起购；Token 供应按实际用量结算；Agent 定制可从单个最小场景开始。不少客户从「一次培训 + 一个 Agent」起步，验证价值后再扩展。我们的客户从数千人的制造集团到几十人的专业服务机构都有覆盖。
</div></div></div>
</div>

<div class="faq-item reveal reveal-d5">
<button class="faq-q" aria-expanded="false">
<span class="idx">10</span>
<span class="txt">如何开始合作？第一步需要做什么准备？</span>
<span class="icon"></span>
</button>
<div class="faq-a"><div class="faq-a-inner"><div class="content">
最简单的方式是<strong>预约一次免费场景诊断</strong>（约 1 小时，线上或线下）：带上您当前最耗人力的 2–3 个业务环节即可，我们会输出一份初步的 AI 落地优先级建议。确定合作意向后签订框架协议，按里程碑分阶段推进。联系电话见页面底部，或发邮件至 sales@xomaps.com。
</div></div></div>
</div>

</div>
</div>
</div>
</section>

<!-- CTA -->
<section class="cta-section" id="contact">
<div class="wrap">
<div class="cta-band reveal">
<div class="cta-inner">
<div class="cta-text">
<h2>想了解更适合您的<br>AI 落地路径？</h2>
<p>预约一次免费场景诊断，或直接与商务团队沟通。工作日 9:00–18:00，通常 2 小时内响应。</p>
<div class="cta-actions">
<a href="tel:18926108189" class="btn btn-accent">立即拨打商务电话 <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.127.96.36 1.903.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.34 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg></a>
</div>
</div>
<div class="cta-contact">
<div class="row">
<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72c.127.96.36 1.903.7 2.81a2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45c.907.34 1.85.573 2.81.7A2 2 0 0 1 22 16.92z"/></svg>
<div><span class="label">商务咨询</span><div class="val">冯小姐 · 18926108189</div></div>
</div>
<div class="row">
<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
<div><span class="label">总部地址</span><div class="val">广州市天河区科韵路16号信息港A栋1510</div></div>
</div>
<div class="row">
<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 7l9 6 9-6M3 7v10a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V7M3 7l2-2h14l2 2"/></svg>
<div><span class="label">企业邮箱</span><div class="val">sales@xomaps.com</div></div>
</div>
</div>
</div>
</div>
</div>
</section>

<script>
// ===== 滚动渐入 =====
var io = new IntersectionObserver(function(entries){
entries.forEach(function(e){ if(e.isIntersecting){ e.target.classList.add('in'); io.unobserve(e.target); }});
}, { threshold: 0.06, rootMargin: '0px 0px -40px 0px' });
document.querySelectorAll('.reveal').forEach(function(el){ io.observe(el); });

// ===== 新闻筛选（带交错过渡动画） =====
var filterBtns = document.querySelectorAll('.news-filter button');
var newsItems = document.querySelectorAll('.news-item');
filterBtns.forEach(function(btn){
btn.addEventListener('click', function(){
filterBtns.forEach(function(b){ b.classList.remove('active'); });
btn.classList.add('active');
var f = btn.dataset.filter;
var shown = 0;
newsItems.forEach(function(p){
var show = f === 'all' || p.dataset.cat === f;
if(show){
p.style.display = '';
var delay = shown * 55;
shown++;
requestAnimationFrame(function(){ requestAnimationFrame(function(){
p.style.transitionDelay = delay + 'ms';
p.classList.remove('hide');
setTimeout(function(){ p.style.transitionDelay = ''; }, delay + 450);
}); });
} else {
p.style.transitionDelay = '';
p.classList.add('hide');
setTimeout(function(){ if(p.classList.contains('hide')) p.style.display = 'none'; }, 400);
}
});
});
});

// ===== FAQ 手风琴（单开模式） =====
var faqItems = document.querySelectorAll('.faq-item');
faqItems.forEach(function(item){
var q = item.querySelector('.faq-q');
q.addEventListener('click', function(){
var isOpen = item.classList.contains('open');
faqItems.forEach(function(i){
i.classList.remove('open');
i.querySelector('.faq-q').setAttribute('aria-expanded','false');
});
if(!isOpen){
item.classList.add('open');
q.setAttribute('aria-expanded','true');
}
});
});
</script>

<!-- ══════════ WebGL 流体特效（Three.js） ══════════ -->
<script src="/assets/js/vendor/three.min.js"></script>
<script>
(function(){
if(window.matchMedia('(prefers-reduced-motion: reduce)').matches) return;
if(window.innerWidth < 768 || window.matchMedia('(pointer: coarse)').matches) return;
if(typeof THREE === 'undefined') return;

var wrap = document.getElementById('fluid-wrap');
if(!wrap) return;

var testCanvas = document.createElement('canvas');
var gl = testCanvas.getContext('webgl2') || testCanvas.getContext('webgl');
if(!gl) return;

var CFG = {
dt: 0.014, viscous: 30, pressureIter: 12,
cursorSize: 100, mouseForce: 20, simScale: 0.4,
palette: ['#1d4ed8', '#93c5fd'],
};

var VERT = [
'attribute vec3 position;','uniform vec2 px;','uniform vec2 boundarySpace;','varying vec2 uv;',
'void main(){','  vec3 pos = position;','  vec2 scale = 1.0 - boundarySpace * 2.0;','  pos.xy = pos.xy * scale;',
'  uv = vec2(0.5) + (pos.xy) * 0.5;','  gl_Position = vec4(pos, 1.0);','}'
].join('\n');

var ADVECT = [
'precision highp float;','uniform sampler2D velocity;','uniform float dt;','uniform vec2 fboSize;','uniform vec2 px;','varying vec2 uv;',
'void main(){','  vec2 ratio = max(fboSize.x, fboSize.y) / fboSize;','  vec2 spot_new = uv;',
'  vec2 vel_old = texture2D(velocity, uv).xy;','  vec2 spot_old = spot_new - vel_old * dt * ratio;',
'  vec2 vel_new1 = texture2D(velocity, spot_old).xy;','  vec2 spot_new2 = spot_old + vel_new1 * dt * ratio;',
'  vec2 error = spot_new2 - spot_new;','  vec2 spot_new3 = spot_new - error / 2.0;',
'  vec2 vel_2 = texture2D(velocity, spot_new3).xy;','  vec2 spot_old2 = spot_new3 - vel_2 * dt * ratio;',
'  gl_FragColor = vec4(texture2D(velocity, spot_old2).xy, 0.0, 1.0);','}'
].join('\n');

var MOUSE_V = [
'precision highp float;','attribute vec3 position;','attribute vec2 uv;','uniform vec2 center, scale, px;','varying vec2 vUv;',
'void main(){','  vec2 pos = position.xy * scale * 2.0 * px + center;','  vUv = uv;','  gl_Position = vec4(pos, 0.0, 1.0);','}'
].join('\n');

var MOUSE_F = [
'precision highp float;','uniform vec2 force;','varying vec2 vUv;',
'void main(){','  vec2 circle = (vUv - 0.5) * 2.0;','  float d = 1.0 - min(length(circle), 1.0);','  d *= d;',
'  gl_FragColor = vec4(force * d, 0.0, 1.0);','}'
].join('\n');

var VISCOUS = [
'precision highp float;','uniform sampler2D velocity;','uniform sampler2D velocity_new;','uniform float v, dt;','uniform vec2 px;','varying vec2 uv;',
'void main(){','  vec2 old = texture2D(velocity, uv).xy;',
'  vec2 n0 = texture2D(velocity_new, uv + vec2(px.x*2.0, 0.0)).xy;',
'  vec2 n1 = texture2D(velocity_new, uv - vec2(px.x*2.0, 0.0)).xy;',
'  vec2 n2 = texture2D(velocity_new, uv + vec2(0.0, px.y*2.0)).xy;',
'  vec2 n3 = texture2D(velocity_new, uv - vec2(0.0, px.y*2.0)).xy;',
'  vec2 newv = (4.0 * old + v * dt * (n0 + n1 + n2 + n3)) / (4.0 * (1.0 + v * dt));',
'  gl_FragColor = vec4(newv, 0.0, 1.0);','}'
].join('\n');

var DIVERGENCE = [
'precision highp float;','uniform sampler2D velocity;','uniform float dt;','uniform vec2 px;','varying vec2 uv;',
'void main(){','  float x0 = texture2D(velocity, uv - vec2(px.x, 0.0)).x;',
'  float x1 = texture2D(velocity, uv + vec2(px.x, 0.0)).x;',
'  float y0 = texture2D(velocity, uv - vec2(0.0, px.y)).y;',
'  float y1 = texture2D(velocity, uv + vec2(0.0, px.y)).y;',
'  gl_FragColor = vec4((x1 - x0 + y1 - y0) / 2.0 / dt, 0.0, 0.0, 1.0);','}'
].join('\n');

var PRESSURE = [
'precision highp float;','uniform sampler2D pressure;','uniform sampler2D divergence;','uniform vec2 px;','varying vec2 uv;',
'void main(){','  float p0 = texture2D(pressure, uv + vec2(px.x*2.0, 0.0)).r;',
'  float p1 = texture2D(pressure, uv - vec2(px.x*2.0, 0.0)).r;',
'  float p2 = texture2D(pressure, uv + vec2(0.0, px.y*2.0)).r;',
'  float p3 = texture2D(pressure, uv - vec2(0.0, px.y*2.0)).r;',
'  float div = texture2D(divergence, uv).r;',
'  gl_FragColor = vec4((p0 + p1 + p2 + p3) / 4.0 - div, 0.0, 0.0, 1.0);','}'
].join('\n');

var GRAD_SUB = [
'precision highp float;','uniform sampler2D pressure;','uniform sampler2D velocity;','uniform vec2 px;','uniform float dt;','varying vec2 uv;',
'void main(){','  float p0 = texture2D(pressure, uv + vec2(px.x, 0.0)).r;',
'  float p1 = texture2D(pressure, uv - vec2(px.x, 0.0)).r;',
'  float p2 = texture2D(pressure, uv + vec2(0.0, px.y)).r;',
'  float p3 = texture2D(pressure, uv - vec2(0.0, px.y)).r;',
'  vec2 v = texture2D(velocity, uv).xy;','  v = v - vec2(p0 - p1, p2 - p3) * 0.5 * dt;',
'  gl_FragColor = vec4(v, 0.0, 1.0);','}'
].join('\n');

var DISPLAY = [
'precision highp float;','uniform sampler2D velocity;','uniform sampler2D palette;','uniform vec4 bgColor;','varying vec2 uv;',
'void main(){','  vec2 vel = texture2D(velocity, uv).xy;','  float lenv = clamp(length(vel), 0.0, 1.0) * 0.5;',
'  vec3 c = texture2D(palette, vec2(lenv, 0.5)).rgb;',
'  gl_FragColor = vec4(mix(bgColor.rgb, c, lenv), mix(bgColor.a, 1.0, lenv));','}'
].join('\n');

var renderer = new THREE.WebGLRenderer({ antialias: true, alpha: true });
renderer.autoClear = false;
renderer.setClearColor(0xffffff, 1);
renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2));
wrap.appendChild(renderer.domElement);

var colors = CFG.palette;
var palData = new Uint8Array(colors.length * 4);
colors.forEach(function(hex, i){
var c = new THREE.Color(hex);
palData[4*i] = Math.round(255 * c.r);
palData[4*i+1] = Math.round(255 * c.g);
palData[4*i+2] = Math.round(255 * c.b);
palData[4*i+3] = 255;
});
var palette = new THREE.DataTexture(palData, colors.length, 1, THREE.RGBAFormat);
palette.magFilter = THREE.LinearFilter; palette.minFilter = THREE.LinearFilter;
palette.wrapS = THREE.ClampToEdgeWrapping; palette.wrapT = THREE.ClampToEdgeWrapping;
palette.needsUpdate = true;

var simW = 1, simH = 1;
var cellScale = new THREE.Vector2(1, 1);
var fboSize = new THREE.Vector2(1, 1);
var boundarySpace = new THREE.Vector2(1, 1);
var mouse = { coords: new THREE.Vector2(0, 0), coords_old: new THREE.Vector2(0, 0), diff: new THREE.Vector2(0, 0) };

var isIOS = /iPad|iPhone|iPod/.test(navigator.userAgent);
var rtOpts = { type: isIOS ? THREE.HalfFloatType : THREE.FloatType, depthBuffer: false, stencilBuffer: false, minFilter: THREE.LinearFilter, magFilter: THREE.LinearFilter, wrapS: THREE.ClampToEdgeWrapping, wrapT: THREE.ClampToEdgeWrapping };
var RT = {};
['vel_0','vel_1','vel_visc0','vel_visc1','div','press_0','press_1'].forEach(function(name){ RT[name] = new THREE.WebGLRenderTarget(1, 1, rtOpts); });

var camera = new THREE.Camera();
var quadGeo = new THREE.PlaneGeometry(2, 2);

function makePass(fragShader, uniforms){
var mat = new THREE.RawShaderMaterial({ vertexShader: VERT, fragmentShader: fragShader, uniforms: uniforms });
var mesh = new THREE.Mesh(quadGeo, mat);
var scene = new THREE.Scene(); scene.add(mesh);
return { scene: scene, mesh: mesh, uniforms: uniforms };
}
function renderPass(pass, output){
pass.mesh.material.uniforms = pass.uniforms;
renderer.setRenderTarget(output || null);
renderer.render(pass.scene, camera);
}

var advect = makePass(ADVECT, { boundarySpace:{value:cellScale}, px:{value:cellScale}, fboSize:{value:fboSize}, velocity:{value:RT.vel_0.texture}, dt:{value:CFG.dt} });
var viscous = makePass(VISCOUS, { boundarySpace:{value:boundarySpace}, px:{value:cellScale}, velocity:{value:RT.vel_1.texture}, velocity_new:{value:RT.vel_visc0.texture}, v:{value:CFG.viscous}, dt:{value:CFG.dt} });
var divPass = makePass(DIVERGENCE, { boundarySpace:{value:boundarySpace}, px:{value:cellScale}, velocity:{value:RT.vel_visc0.texture}, dt:{value:CFG.dt} });
var pressPass = makePass(PRESSURE, { boundarySpace:{value:boundarySpace}, px:{value:cellScale}, pressure:{value:RT.press_0.texture}, divergence:{value:RT.div.texture} });
var gradPass = makePass(GRAD_SUB, { boundarySpace:{value:boundarySpace}, px:{value:cellScale}, pressure:{value:RT.press_0.texture}, velocity:{value:RT.vel_visc0.texture}, dt:{value:CFG.dt} });

var mouseMat = new THREE.RawShaderMaterial({ vertexShader: MOUSE_V, fragmentShader: MOUSE_F, blending: THREE.AdditiveBlending, depthWrite: false, uniforms: { px:{value:cellScale}, force:{value:new THREE.Vector2(0,0)}, center:{value:new THREE.Vector2(0,0)}, scale:{value:new THREE.Vector2(CFG.cursorSize, CFG.cursorSize)} } });
var mouseMesh = new THREE.Mesh(new THREE.PlaneGeometry(1, 1), mouseMat);
var mouseScene = new THREE.Scene(); mouseScene.add(mouseMesh);

var displayMat = new THREE.RawShaderMaterial({ vertexShader: VERT, fragmentShader: DISPLAY, transparent: false, depthWrite: false, depthTest: false, uniforms: { velocity:{value:RT.vel_0.texture}, palette:{value:palette}, bgColor:{value:new THREE.Vector4(1,1,1,1)} } });
var displayScene = new THREE.Scene(); displayScene.add(new THREE.Mesh(quadGeo, displayMat));

function resize(){
var w = Math.max(1, window.innerWidth); var h = Math.max(1, window.innerHeight);
renderer.setSize(w, h, false);
simW = Math.max(1, Math.round(w * CFG.simScale)); simH = Math.max(1, Math.round(h * CFG.simScale));
fboSize.set(simW, simH); cellScale.set(1/simW, 1/simH);
for(var k in RT) RT[k].setSize(simW, simH);
}
window.addEventListener('resize', resize); resize();

function updateMouse(cx, cy){
var nx = cx / window.innerWidth; var ny = cy / window.innerHeight;
mouse.coords.set(2 * nx - 1, -(2 * ny - 1));
}
window.addEventListener('mousemove', function(e){ updateMouse(e.clientX, e.clientY); });

var visible = !document.hidden;
document.addEventListener('visibilitychange', function(){ visible = !document.hidden; if(visible && !rafId) rafId = requestAnimationFrame(frame); });

var rafId = null;
function frame(){
if(!visible){ rafId = null; return; }
mouse.diff.subVectors(mouse.coords, mouse.coords_old);
mouse.coords_old.copy(mouse.coords);
boundarySpace.copy(cellScale);

advect.uniforms.velocity.value = RT.vel_0.texture;
advect.uniforms.fboSize.value = fboSize;
renderPass(advect, RT.vel_1);

var fx = (mouse.diff.x / 2) * CFG.mouseForce;
var fy = (mouse.diff.y / 2) * CFG.mouseForce;
var cs = CFG.cursorSize * cellScale.x;
var sy = CFG.cursorSize * cellScale.y;
mouseMat.uniforms.force.value.set(fx, fy);
mouseMat.uniforms.center.value.set(Math.min(Math.max(mouse.coords.x, -1 + cs + 2*cellScale.x), 1 - cs - 2*cellScale.x), Math.min(Math.max(mouse.coords.y, -1 + sy + 2*cellScale.y), 1 - sy - 2*cellScale.y));
mouseMat.uniforms.px.value = cellScale;
renderer.setRenderTarget(RT.vel_1);
renderer.render(mouseScene, camera);

viscous.uniforms.velocity.value = RT.vel_1.texture;
viscous.uniforms.velocity_new.value = RT.vel_1.texture;
renderPass(viscous, RT.vel_visc0);

divPass.uniforms.velocity.value = RT.vel_visc0.texture;
renderPass(divPass, RT.div);

renderer.setRenderTarget(RT.press_0);
renderer.clear();
var pIn = RT.press_0, pOut = RT.press_1;
for(var i = 0; i < CFG.pressureIter; i++){
pressPass.uniforms.pressure.value = pIn.texture;
renderPass(pressPass, pOut);
var tmp = pIn; pIn = pOut; pOut = tmp;
}

gradPass.uniforms.velocity.value = RT.vel_visc0.texture;
gradPass.uniforms.pressure.value = pIn.texture;
renderPass(gradPass, RT.vel_0);

displayMat.uniforms.velocity.value = RT.vel_0.texture;
renderer.setRenderTarget(null);
renderer.clear();
renderer.render(displayScene, camera);

rafId = requestAnimationFrame(frame);
}
rafId = requestAnimationFrame(frame);
})();
</script>



<style>
:root{
--brand:#2563eb;
--brand-2:#3b82f6;
--brand-text:#0f2c5e;
--text:#1f2937;
--text-2:#4b5563;
--bg:#ffffff;
--border:#e2e8f0;

/* 底部导航条专属（淡蓝白浅色版） */
--ft-bg:#ffffff;
--ft-bg-2:#e0f2fe;
--ft-text:#1f2937;
--ft-text-2:#4b5563;
--ft-text-3:#6b7280;
--ft-line:#dbe7f5;
--ft-hover:#2563eb;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
font-family:"PingFang SC","Microsoft YaHei",system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;
color:var(--text);background:#f8fafc;line-height:1.7;font-size:15px;
-webkit-font-smoothing:antialiased;
}
a{color:inherit;text-decoration:none}
ul{list-style:none}

/* ===== 占位内容，用于演示 ===== */
.demo-page{min-height:120vh;background:linear-gradient(180deg,#f0f9ff 0%,#ffffff 40%,#f1f5f9 100%);padding:80px 24px 120px}
.demo-section{max-width:1200px;margin:0 auto}
.demo-section h1{font-size:34px;font-weight:800;color:var(--brand-text);margin-bottom:14px}
.demo-section p{font-size:16px;color:var(--text-2);max-width:640px;line-height:1.8}

/* ══════════════════════════════════════
底部导航条 Footer
══════════════════════════════════════ */
.footer{
background:linear-gradient(135deg,#ffffff 0%,#eff6ff 40%,#e0f2fe 75%,#ffffff 100%);
color:var(--ft-text-2);
position:relative;
overflow:hidden;
border-top:1px solid var(--ft-line);
}
/* 顶部品牌光带 */
.footer::before{
content:"";
position:absolute;top:0;left:0;right:0;height:3px;
background:linear-gradient(90deg,#2563eb 0%,#3b82f6 30%,#7fb0ff 60%,#2563eb 100%);
}
/* 背景装饰光晕 */
.footer::after{
content:"";
position:absolute;top:-180px;right:-120px;width:480px;height:480px;border-radius:50%;
background:radial-gradient(circle,rgba(37,99,235,0.07) 0%,transparent 65%);
pointer-events:none;
}

.footer-inner{
max-width:1200px;margin:0 auto;padding:56px 24px 0;
position:relative;z-index:1;text-align: left;
}

/* ===== 主体四栏 ===== */
.footer-grid{
display:grid;
grid-template-columns:1.35fr 0.85fr 1.05fr 1.15fr;
gap:48px 40px;
padding-bottom:44px;
}

.ft-title{
font-size:15px;font-weight:700;color:var(--brand-text);
letter-spacing:.05em;margin-bottom:18px;
display:flex;align-items:center;gap:8px;
}
.ft-title::before{
content:"";width:3px;height:14px;border-radius:2px;
background:linear-gradient(180deg,var(--brand-2),#7fb0ff);
}

/* —— 第 1 栏：品牌 + 简介 —— */
.ft-brand .logo-row{display:flex;align-items:center;gap:10px;margin-bottom:16px}
.ft-brand .logo-row img{height:34px}
.ft-brand .logo-name{font-size:18px;font-weight:800;color:var(--brand-text);letter-spacing:.02em}
.ft-brand p{font-size:13.5px;line-height:1.9;color:var(--ft-text-2)}
.ft-badges{display:flex;flex-wrap:wrap;gap:8px;margin-top:16px}
.ft-badges span{
font-size:12px;color:var(--ft-text-2);
border:1px solid var(--ft-line);border-radius:999px;
padding:3px 12px;background:rgba(37,99,235,0.05);
}

/* —— 第 2 栏：服务项目（7 项） —— */
.ft-links li{margin-bottom:4px}
.ft-links a{
display:inline-flex;align-items:center;gap:8px;
font-size:13.5px;color:var(--ft-text-2);padding:5px 0;
transition:color .2s,transform .2s;
}
.ft-links a::before{
content:"";width:5px;height:5px;border-radius:50%;
background:var(--ft-text-3);transition:background .2s;
}
.ft-links a:hover{color:var(--brand);transform:translateX(3px)}
.ft-links a:hover::before{background:var(--ft-hover)}

/* —— 第 3 栏：联系方式 —— */
.ft-contact li{
display:flex;gap:10px;margin-bottom:14px;
font-size:13.5px;line-height:1.7;
}
.ft-contact svg{width:16px;height:16px;flex:none;margin-top:4px;color:var(--ft-hover)}
.ft-contact .k{color:var(--ft-text-3);font-size:12px;display:block}
.ft-contact .v{color:var(--ft-text)}
.ft-contact a.v:hover{color:var(--ft-hover)}
.ft-contact .v-strong{
font-size:19px;font-weight:800;color:var(--brand-text);letter-spacing:.02em;
font-variant-numeric:tabular-nums;
}

/* —— 第 4 栏：二维码 + 公众号 + 留言入口 —— */
.ft-qrcode{
display:flex;gap:16px;align-items:flex-start;
}
.qr-box{
width:104px;height:104px;flex:none;
background:#fff;border-radius:10px;padding:8px;
border:1px solid var(--ft-line);
box-shadow:0 4px 14px rgba(30,58,138,0.10);
}
.qr-box svg{width:100%;height:100%;display:block}
.qr-info{padding-top:4px}
.qr-info .gzh-name{
font-size:14px;font-weight:700;color:var(--brand-text);margin-bottom:6px;
display:flex;align-items:center;gap:6px;
}
.qr-info .gzh-name svg{width:15px;height:15px;color:#6bdb8b}
.qr-info p{font-size:12.5px;color:var(--ft-text-3);line-height:1.8}

/* 留言入口按钮 */
.ft-message{
margin-top:18px;display:flex;flex-direction:column;gap:10px;
}
.ft-msg-btn{
display:flex;align-items:center;justify-content:center;gap:8px;
padding:11px 18px;border-radius:10px;
font-size:14px;font-weight:600;
transition:all .25s;
}
.ft-msg-btn svg{width:16px;height:16px}
.ft-msg-primary{
background:linear-gradient(135deg,var(--brand) 0%,var(--brand-2) 100%);
color:#fff;box-shadow:0 4px 16px rgba(37,99,235,0.4);
}
.ft-msg-primary:hover{transform:translateY(-2px);box-shadow:0 8px 22px rgba(37,99,235,0.5)}
.ft-msg-ghost{
border:1px solid var(--ft-line);color:var(--ft-text);
background:rgba(255,255,255,0.65);
}
.ft-msg-ghost:hover{border-color:var(--brand);color:var(--brand);background:#fff}

/* ===== 分隔线 + 底部信息栏（备案号） ===== */
.footer-bottom{
border-top:1px solid var(--ft-line);
padding:20px 0 24px;
display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap;
}
.fb-left{font-size:12.5px;color:var(--ft-text-3)}
.fb-left a:hover{color:var(--ft-hover)}
.fb-right{display:flex;align-items:center;gap:20px;flex-wrap:wrap}
.fb-right a,.fb-right span{
font-size:12.5px;color:var(--ft-text-3);transition:color .2s;
display:inline-flex;align-items:center;gap:6px;
}
.fb-right a:hover{color:var(--ft-hover)}
.fb-right svg{width:13px;height:13px;opacity:.7}

/* ===== 响应式 ===== */
@media (max-width:1024px){
.footer-grid{grid-template-columns:1fr 1fr;gap:40px 32px}
}
@media (max-width:640px){
.footer-inner{padding:44px 20px 0}
.footer-grid{grid-template-columns:1fr;gap:36px}
.footer-bottom{flex-direction:column;text-align:center}
.fb-right{justify-content:center}
}
</style>

<style>
/* ===== 配色变量（改这里即可整体换肤） ===== */
.side-tools{
--st-brand:#2563eb;       /* ★ 品牌主色 */
--st-brand-2:#3b82f6;     /* ★ 品牌辅色（渐变末端） */
--st-brand-text:#0f2c5e;  /* 标题/二维码说明文字色 */
--st-text:#1f2937;        /* 气泡文字色 */
--st-text-3:#6b7280;      /* 次要文字色 */
--st-line:#dbe7f5;        /* 边框色 */
--st-white:#ffffff;
}

/* ===== 工具栏容器 ===== */
.side-tools{
position:fixed;right:18px;top:50%;transform:translateY(-50%);
z-index:9999;display:flex;flex-direction:column;gap:10px;
font-family:"PingFang SC","Microsoft YaHei",system-ui,-apple-system,sans-serif;
}
.side-tool{
position:relative;width:48px;height:48px;border-radius:13px;
background:var(--st-white);border:1px solid var(--st-line);
box-shadow:0 4px 14px rgba(30,58,138,0.10);
display:flex;align-items:center;justify-content:center;
cursor:pointer;transition:all .25s;color:var(--st-brand);
text-decoration:none;
}
.side-tool:hover{
background:linear-gradient(135deg,var(--st-brand) 0%,var(--st-brand-2) 100%);
color:#fff;border-color:transparent;
transform:translateX(-4px);box-shadow:0 8px 20px rgba(37,99,235,0.35);
}
.side-tool svg{width:22px;height:22px}

/* ===== 文字提示气泡 ===== */
.side-tool .tip{
position:absolute;right:58px;top:50%;
transform:translateY(-50%) translateX(8px);
white-space:nowrap;background:#fff;color:var(--st-text);
font-size:13px;padding:7px 13px;border-radius:9px;
border:1px solid var(--st-line);box-shadow:0 4px 14px rgba(30,58,138,0.12);
opacity:0;visibility:hidden;pointer-events:none;transition:all .25s;
}
.side-tool .tip::after{
content:"";position:absolute;right:-6px;top:50%;transform:translateY(-50%);
border:6px solid transparent;border-left-color:#fff;
}
.side-tool:hover .tip{opacity:1;visibility:visible;transform:translateY(-50%) translateX(0)}

/* ===== 微信二维码弹窗 ===== */
.side-tool .qr-popup{
position:absolute;right:58px;top:50%;
transform:translateY(-50%) translateX(8px) scale(.92);
background:#fff;border:1px solid var(--st-line);border-radius:14px;padding:12px;
box-shadow:0 8px 28px rgba(30,58,138,0.18);
opacity:0;visibility:hidden;pointer-events:none;
transition:all .3s;text-align:center;width:168px;
}
.side-tool .qr-popup .qr-img{
width:144px;height:144px;border:1px solid var(--st-line);border-radius:8px;
overflow:hidden;background:#fff;margin:0 auto;
}
.side-tool .qr-popup .qr-img img{width:100%;height:100%;display:block;object-fit:cover}
.side-tool .qr-popup .qr-label{
font-size:12.5px;color:var(--st-brand-text);font-weight:600;margin-top:8px;
}
.side-tool .qr-popup .qr-sub{font-size:11.5px;color:var(--st-text-3);margin-top:2px}
.side-tool:hover .qr-popup{opacity:1;visibility:visible;transform:translateY(-50%) translateX(0) scale(1)}
.side-tool.qr-open .qr-popup{opacity:1;visibility:visible;transform:translateY(-50%) translateX(0) scale(1)}

/* ===== 在线咨询按钮：主行动召唤，常驻品牌色 + 脉冲提示 ===== */
.side-tool.consult-btn{
background:linear-gradient(135deg,var(--st-brand) 0%,var(--st-brand-2) 100%);
color:#fff;border-color:transparent;
box-shadow:0 6px 18px rgba(37,99,235,0.40);
}
.side-tool.consult-btn:hover{
transform:translateX(-4px) scale(1.05);box-shadow:0 10px 26px rgba(37,99,235,0.55);
}
.side-tool.consult-btn .tip{background:var(--st-brand);color:#fff;border-color:transparent}
.side-tool.consult-btn .tip::after{border-left-color:var(--st-brand)}
.side-tool.consult-btn .ring{
position:absolute;inset:0;border-radius:13px;border:2px solid var(--st-brand-2);
pointer-events:none;animation:sidePulse 2.2s ease-out infinite;
}
@keyframes sidePulse{
0%{transform:scale(1);opacity:.6}
70%{transform:scale(1.4);opacity:0}
100%{transform:scale(1.4);opacity:0}
}

/* ===== 回到顶部按钮：默认隐藏，滚动后出现 ===== */
.side-tool.top-btn{opacity:0;visibility:hidden;transform:translateX(20px);transition:all .3s}
.side-tool.top-btn.show{opacity:1;visibility:visible;transform:translateX(0)}

/* ===== 移动端适配 ===== */
@media (max-width:640px){
.side-tools{right:10px;gap:8px}
.side-tool{width:42px;height:42px;border-radius:11px}
.side-tool svg{width:19px;height:19px}
.side-tool .tip{display:none}
}
</style>
