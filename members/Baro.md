## name: 김바로(Kim, Ba-ro/金把路)
image: images/Baro.jpg # 기존 \_members/Baro.md에 지정된 이미지 경로를 그대로 유지하세요
role: pi
affiliation: 한국학중앙연구원/The Academy of Korean Studies/韓國學中央硏究院
links:
home-page: https://www.ddokbaro.com/
email: ddokbaro@gmail.com
orcid: 0000-0002-4456-9616

<style>
.baro-cv {
\--bg: #FAF9F6;
\--surface: #FFFFFF;
\--surface-alt: #F4F1EA;
\--ink: #181A1F;
\--ink-muted: #555B66;
\--border: #E5E0D8;
\--accent: #1D3557;
\--accent-soft: #EBF0F7;
\--seal: #9E3A2B;
\--seal-soft: #FDF1EE;
\--radius: 12px;
\--shadow: 0 1px 3px rgba(24,26,31,0.05), 0 4px 16px rgba(24,26,31,0.04);
font-family: "Pretendard", "Noto Sans KR", "Inter", -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
color: var(--ink);
background: var(--bg);
line-height: 1.68;
max-width: 1020px;
margin: 0 auto;
padding: 28px 20px 64px;
box-sizing: border-box;
text-align: left;
}
.baro-cv \*, .baro-cv \*::before, .baro-cv \*::after { box-sizing: border-box; }
.baro-cv button, .baro-cv input { font-family: inherit; line-height: 1.4; }
.baro-cv h1, .baro-cv h2, .baro-cv h3 { text-align: left; letter-spacing: normal; text-transform: none; }
.baro-cv section { display: block; text-align: left; }
.baro-cv a { color: var(--accent); text-decoration: none; }
.baro-cv a:hover { text-decoration: underline; }
.baro-cv .cv-topbar {
display: flex;
flex-wrap: wrap;
align-items: center;
justify-content: space-between;
gap: 12px;
padding: 12px 16px;
background: rgba(255,255,255,0.92);
backdrop-filter: blur(8px);
border: 1px solid var(--border);
border-radius: var(--radius);
position: sticky;
top: 12px;
z-index: 40;
margin-bottom: 24px;
box-shadow: var(--shadow);
}
.baro-cv .cv-nav {
display: flex;
flex-wrap: wrap;
gap: 6px;
}
.baro-cv .cv-nav a {
font-size: 0.84rem;
font-weight: 600;
color: var(--ink-muted);
padding: 5px 10px;
border-radius: 999px;
transition: all 0.16s ease;
}
.baro-cv .cv-nav a:hover, .baro-cv .cv-nav a.active {
background: var(--accent-soft);
color: var(--accent);
text-decoration: none;
}
.baro-cv .cv-controls {
display: flex;
align-items: center;
gap: 8px;
}
.baro-cv .lang-switch {
display: inline-flex;
background: var(--surface-alt);
border: 1px solid var(--border);
border-radius: 999px;
padding: 3px;
}
.baro-cv .lang-btn {
border: none;
background: transparent;
color: var(--ink-muted);
font-size: 0.82rem;
font-weight: 600;
padding: 5px 12px;
border-radius: 999px;
cursor: pointer;
transition: all 0.16s ease;
}
.baro-cv .lang-btn.active {
background: var(--accent);
color: #FFFFFF;
}
.baro-cv .btn-print {
border: 1px solid var(--border);
background: var(--surface);
color: var(--ink);
font-size: 0.82rem;
font-weight: 600;
padding: 6px 12px;
border-radius: 999px;
cursor: pointer;
transition: all 0.16s ease;
}
.baro-cv .btn-print:hover {
border-color: var(--accent);
color: var(--accent);
}
.baro-cv .cv-hero {
background: var(--surface);
border: 1px solid var(--border);
border-radius: 16px;
padding: 32px 32px 28px;
box-shadow: var(--shadow);
margin-bottom: 24px;
position: relative;
overflow: hidden;
}
.baro-cv .cv-hero::before {
content: "";
position: absolute;
top: 0;
left: 0;
right: 0;
height: 4px;
background: linear-gradient(90deg, var(--accent) 0%, var(--seal) 100%);
}
.baro-cv .hero-header {
display: flex;
flex-wrap: wrap;
justify-content: space-between;
align-items: flex-start;
gap: 20px;
margin-bottom: 20px;
}
.baro-cv .hero-name {
font-family: "Noto Serif KR", Georgia, serif;
font-size: 2rem;
font-weight: 700;
margin: 0 0 6px;
letter-spacing: -0.02em;
color: var(--ink);
line-height: 1.25;
}
.baro-cv .hero-name-sub {
font-family: "Pretendard", "Inter", sans-serif;
font-size: 1rem;
font-weight: 500;
color: var(--ink-muted);
margin-left: 8px;
}
.baro-cv .hero-role {
font-size: 1.02rem;
font-weight: 600;
color: var(--accent);
margin: 0 0 4px;
}
.baro-cv .hero-affil {
font-size: 0.94rem;
color: var(--ink-muted);
margin: 0;
}
.baro-cv .id-grid {
display: flex;
flex-wrap: wrap;
gap: 8px;
margin-top: 14px;
}
.baro-cv .id-chip {
display: inline-flex;
align-items: center;
gap: 6px;
background: var(--surface-alt);
border: 1px solid var(--border);
border-radius: 8px;
padding: 5px 10px;
font-size: 0.8rem;
color: var(--ink);
cursor: pointer;
transition: border-color 0.15s ease, background 0.15s ease;
}
.baro-cv .id-chip:hover {
border-color: var(--accent);
background: var(--accent-soft);
text-decoration: none;
}
.baro-cv .id-label {
font-weight: 700;
color: var(--accent);
font-size: 0.74rem;
text-transform: uppercase;
letter-spacing: 0.03em;
}
.baro-cv .bio-box {
background: var(--surface-alt);
border-left: 3px solid var(--seal);
border-radius: 0 10px 10px 0;
padding: 16px 20px;
margin: 18px 0 20px;
}
.baro-cv .bio-tabs {
display: flex;
gap: 6px;
margin-bottom: 10px;
}
.baro-cv .bio-tab {
border: 1px solid var(--border);
background: var(--surface);
color: var(--ink-muted);
font-size: 0.76rem;
font-weight: 600;
padding: 3px 10px;
border-radius: 999px;
cursor: pointer;
}
.baro-cv .bio-tab.active {
background: var(--ink);
color: #FFFFFF;
border-color: var(--ink);
}
.baro-cv .bio-text {
margin: 0;
font-size: 0.95rem;
color: var(--ink);
}
.baro-cv .kpi-strip {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
gap: 12px;
margin-top: 20px;
}
.baro-cv .kpi-card {
background: var(--bg);
border: 1px solid var(--border);
border-radius: 10px;
padding: 14px 16px;
}
.baro-cv .kpi-num {
font-family: "Noto Serif KR", Georgia, serif;
font-size: 1.55rem;
font-weight: 700;
color: var(--accent);
line-height: 1.15;
}
.baro-cv .kpi-label {
font-size: 0.79rem;
color: var(--ink-muted);
margin-top: 4px;
font-weight: 500;
}
.baro-cv .cv-section {
background: var(--surface);
border: 1px solid var(--border);
border-radius: 16px;
padding: 28px 30px;
box-shadow: var(--shadow);
margin-bottom: 22px;
scroll-margin-top: 84px;
}
.baro-cv .sec-head {
display: flex;
flex-wrap: wrap;
align-items: baseline;
justify-content: space-between;
gap: 10px;
border-bottom: 1px solid var(--border);
padding-bottom: 12px;
margin-bottom: 20px;
}
.baro-cv .sec-title {
font-family: "Noto Serif KR", Georgia, serif;
font-size: 1.28rem;
font-weight: 700;
margin: 0;
color: var(--ink);
display: flex;
align-items: center;
gap: 10px;
}
.baro-cv .sec-count {
font-family: "Pretendard", "Inter", sans-serif;
font-size: 0.78rem;
font-weight: 700;
background: var(--accent-soft);
color: var(--accent);
padding: 2px 9px;
border-radius: 999px;
}
.baro-cv .two-col {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
gap: 20px;
}
.baro-cv .info-panel {
background: var(--bg);
border: 1px solid var(--border);
border-radius: 12px;
padding: 18px 20px;
}
.baro-cv .info-panel h3 {
font-size: 0.94rem;
font-weight: 700;
color: var(--accent);
margin: 0 0 10px;
}
.baro-cv .pill-list {
display: flex;
flex-wrap: wrap;
gap: 7px;
margin-top: 12px;
}
.baro-cv .pill {
font-size: 0.8rem;
font-weight: 500;
background: var(--surface);
border: 1px solid var(--border);
color: var(--ink);
padding: 4px 10px;
border-radius: 999px;
}
.baro-cv .guidance-list {
list-style: none;
padding: 0;
margin: 0;
display: flex;
flex-direction: column;
gap: 8px;
}
.baro-cv .guidance-list li {
display: flex;
align-items: center;
gap: 10px;
font-size: 0.92rem;
font-weight: 500;
}
.baro-cv .guidance-num {
width: 22px;
height: 22px;
border-radius: 50%;
background: var(--accent);
color: #FFFFFF;
font-size: 0.74rem;
font-weight: 700;
display: inline-flex;
align-items: center;
justify-content: center;
flex-shrink: 0;
}
.baro-cv .timeline {
list-style: none;
padding: 0;
margin: 0;
display: flex;
flex-direction: column;
gap: 12px;
}
.baro-cv .tl-item {
display: grid;
grid-template-columns: 165px 1fr;
gap: 14px;
padding-bottom: 12px;
border-bottom: 1px dashed var(--border);
align-items: baseline;
}
.baro-cv .tl-item:last-child { border-bottom: none; padding-bottom: 0; }
.baro-cv .tl-date {
font-size: 0.83rem;
font-weight: 600;
color: var(--ink-muted);
font-variant-numeric: tabular-nums;
}
.baro-cv .tl-body {
font-size: 0.94rem;
color: var(--ink);
}
.baro-cv .tl-sub {
font-size: 0.84rem;
color: var(--ink-muted);
margin-top: 3px;
}
.baro-cv .badge {
display: inline-block;
font-size: 0.72rem;
font-weight: 700;
padding: 2px 8px;
border-radius: 999px;
margin-right: 6px;
vertical-align: middle;
}
.baro-cv .badge-now { background: var(--seal-soft); color: var(--seal); }
.baro-cv .badge-pi { background: var(--accent-soft); color: var(--accent); }
.baro-cv .badge-solo { background: #E9F5EE; color: #1B6A40; }
.baro-cv .badge-co { background: var(--surface-alt); color: var(--ink-muted); }
.baro-cv .filter-bar {
display: flex;
flex-wrap: wrap;
align-items: center;
justify-content: space-between;
gap: 10px;
margin-bottom: 16px;
}
.baro-cv .filter-pills {
display: flex;
flex-wrap: wrap;
gap: 6px;
}
.baro-cv .filter-btn {
border: 1px solid var(--border);
background: var(--bg);
color: var(--ink-muted);
font-size: 0.8rem;
font-weight: 600;
padding: 5px 12px;
border-radius: 999px;
cursor: pointer;
transition: all 0.15s ease;
}
.baro-cv .filter-btn.active {
background: var(--accent);
color: #FFFFFF;
border-color: var(--accent);
}
.baro-cv .search-input {
border: 1px solid var(--border);
background: var(--bg);
color: var(--ink);
font-size: 0.85rem;
padding: 7px 13px;
border-radius: 999px;
min-width: 220px;
outline: none;
}
.baro-cv .search-input:focus {
border-color: var(--accent);
background: var(--surface);
}
.baro-cv .book-grid {
display: grid;
grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
gap: 14px;
}
.baro-cv .book-card {
background: var(--bg);
border: 1px solid var(--border);
border-radius: 12px;
padding: 16px 18px;
display: flex;
flex-direction: column;
justify-content: space-between;
gap: 8px;
}
.baro-cv .book-title {
font-weight: 700;
font-size: 0.94rem;
color: var(--ink);
line-height: 1.45;
}
.baro-cv .book-meta {
font-size: 0.81rem;
color: var(--ink-muted);
display: flex;
justify-content: space-between;
align-items: center;
gap: 8px;
}
.baro-cv .pub-item {
display: grid;
grid-template-columns: 78px 1fr;
gap: 12px;
padding: 11px 0;
border-bottom: 1px solid var(--surface-alt);
align-items: baseline;
}
.baro-cv .pub-item:last-child { border-bottom: none; }
.baro-cv .pub-date {
font-size: 0.82rem;
font-weight: 600;
color: var(--ink-muted);
font-variant-numeric: tabular-nums;
}
.baro-cv .pub-title {
font-size: 0.93rem;
font-weight: 500;
color: var(--ink);
}
.baro-cv .pub-journal {
font-size: 0.83rem;
color: var(--accent);
font-weight: 600;
margin-top: 2px;
}
.baro-cv .proj-card {
padding: 14px 16px;
border: 1px solid var(--border);
border-radius: 10px;
background: var(--bg);
margin-bottom: 10px;
}
.baro-cv .proj-top {
display: flex;
flex-wrap: wrap;
justify-content: space-between;
align-items: center;
gap: 6px;
margin-bottom: 6px;
}
.baro-cv .proj-period {
font-size: 0.81rem;
font-weight: 600;
color: var(--ink-muted);
font-variant-numeric: tabular-nums;
}
.baro-cv .proj-budget {
font-size: 0.79rem;
font-weight: 600;
color: var(--ink-muted);
}
.baro-cv .proj-title {
font-size: 0.95rem;
font-weight: 700;
color: var(--ink);
margin-bottom: 4px;
}
.baro-cv .proj-meta {
font-size: 0.83rem;
color: var(--ink-muted);
}
.baro-cv .btn-more {
display: block;
width: 100%;
margin-top: 14px;
padding: 10px;
background: var(--surface-alt);
border: 1px solid var(--border);
border-radius: 10px;
color: var(--accent);
font-size: 0.86rem;
font-weight: 700;
cursor: pointer;
transition: background 0.15s ease;
}
.baro-cv .btn-more:hover { background: var(--accent-soft); }
.baro-cv .sub-heading {
font-size: 0.98rem;
font-weight: 700;
color: var(--accent);
margin: 22px 0 12px;
padding-left: 10px;
border-left: 3px solid var(--accent);
}
.baro-cv .sub-heading:first-of-type { margin-top: 4px; }
.baro-cv .empty-state {
text-align: center;
padding: 28px 16px;
color: var(--ink-muted);
font-size: 0.9rem;
}
.baro-cv .cv-toast {
position: fixed;
bottom: 24px;
right: 24px;
background: var(--ink);
color: #FFFFFF;
padding: 10px 16px;
border-radius: 10px;
font-size: 0.84rem;
font-weight: 600;
opacity: 0;
pointer-events: none;
transform: translateY(8px);
transition: all 0.2s ease;
z-index: 99;
}
.baro-cv .cv-toast.show {
opacity: 1;
transform: translateY(0);
}
@media (max-width: 680px) {
.baro-cv { padding: 16px 12px 48px; }
.baro-cv .cv-hero, .baro-cv .cv-section { padding: 20px 18px; }
.baro-cv .hero-name { font-size: 1.55rem; }
.baro-cv .tl-item { grid-template-columns: 1fr; gap: 3px; }
.baro-cv .pub-item { grid-template-columns: 1fr; gap: 2px; }
.baro-cv .search-input { width: 100%; }
}
@media print {
.baro-cv { background: #FFFFFF; padding: 0; max-width: 100%; }
.baro-cv .cv-topbar, .baro-cv .filter-bar, .baro-cv .btn-more, .baro-cv .bio-tabs, .baro-cv .cv-toast { display: none !important; }
.baro-cv .cv-hero, .baro-cv .cv-section { box-shadow: none; border: none; border-bottom: 1px solid #DDD; border-radius: 0; padding: 14px 0; }
}
</style>
<div class="baro-cv" id="baro-cv-root">
<nav class="cv-topbar" aria-label="CV Navigation">
<div class="cv-nav" id="cv-nav-links"></div>
<div class="cv-controls">
<div class="lang-switch" role="group" aria-label="Language Switcher">
<button type="button" class="lang-btn active" data-lang="kr">한국어</button>
<button type="button" class="lang-btn" data-lang="en">English</button>
</div>
<button type="button" class="btn-print" id="cv-print-btn">Print / PDF</button>
</div>
</nav>
<header class="cv-hero" id="sec-overview">
<div class="hero-header">
<div>
<h1 class="hero-name" id="cv-name">김바로 <span class="hero-name-sub">Kim, Ba-ro · 金把路</span></h1>
<p class="hero-role" id="cv-role">부교수 · 인문정보학</p>
<p class="hero-affil" id="cv-affil">한국학중앙연구원 한국학대학원 / 디지털인문학연구소</p>
<div class="id-grid" id="cv-ids"></div>
</div>
</div>
<div class="bio-box">
<div class="bio-tabs" id="cv-bio-tabs">
<button type="button" class="bio-tab active" data-bio="kr">한국어</button>
<button type="button" class="bio-tab" data-bio="en">English</button>
<button type="button" class="bio-tab" data-bio="zh">中文</button>
</div>
<p class="bio-text" id="cv-bio-text"></p>
</div>
<div class="kpi-strip" id="cv-kpi-strip"></div>
</header>
<section class="cv-section" id="sec-research">
<div class="sec-head"><h2 class="sec-title" id="t-research"></h2></div>
<div class="two-col" id="cv-research-body"></div>
</section>
<section class="cv-section" id="sec-edu-career">
<div class="sec-head"><h2 class="sec-title" id="t-edu-career"></h2></div>
<div id="cv-edu-career-body"></div>
</section>
<section class="cv-section" id="sec-service">
<div class="sec-head"><h2 class="sec-title" id="t-service"></h2></div>
<div id="cv-service-body"></div>
</section>
<section class="cv-section" id="sec-books">
<div class="sec-head"><h2 class="sec-title" id="t-books"></h2></div>
<div class="book-grid" id="cv-books-body"></div>
</section>
<section class="cv-section" id="sec-papers">
<div class="sec-head"><h2 class="sec-title" id="t-papers"></h2></div>
<div class="filter-bar">
<div class="filter-pills" id="cv-paper-years"></div>
<input type="search" class="search-input" id="cv-paper-search" placeholder="논문 제목·학술지 검색..." aria-label="Search papers" />
</div>
<div id="cv-papers-body"></div>
<button type="button" class="btn-more" id="cv-papers-more"></button>
</section>
<section class="cv-section" id="sec-projects">
<div class="sec-head"><h2 class="sec-title" id="t-projects"></h2></div>
<div class="filter-bar">
<div class="filter-pills" id="cv-proj-filters"></div>
<input type="search" class="search-input" id="cv-proj-search" placeholder="과제명·지원기관 검색..." aria-label="Search projects" />
</div>
<div id="cv-projects-body"></div>
<button type="button" class="btn-more" id="cv-projects-more"></button>
</section>
<section class="cv-section" id="sec-more">
<div class="sec-head"><h2 class="sec-title" id="t-more"></h2></div>
<div id="cv-more-body"></div>
</section>
<div class="cv-toast" id="cv-toast" role="status" aria-live="polite"></div>
</div>
<script>
(function() {
const CV_DATA = {"meta":{"name_kr":"김바로","name_en":"Kim, Ba-ro","name_zh":"金把路","role_kr":"부교수 · 인문정보학","role_en":"Associate Professor · Humanities and Information Science","affiliation_kr":"한국학중앙연구원 한국학대학원 / 디지털인문학연구소","affiliation_en":"The Academy of Korean Studies (AKS) / Center for Digital Humanities","homepage":"https://www.ddokbaro.com/","email":"ddokbaro@gmail.com","orcid":"0000-0002-4456-9616","isni":"0000000468148634","iris":"11365082","bio":{"kr":"디지털 인문학이라는 캔버스 위에 인문학의 깊이와 디지털 기술의 혁신을 담아내는 작업을 하고 있습니다. 모두가 같이 하는 데이터 기반의 한국학 연구를 통해 과거와 현재를 잇고, 미래 사회에 기여하고자 합니다. “知其不可而爲之(지기불가이위지: 불가능하다는 것을 알면서도 행한다)”라는 말처럼, 늘 도전하는 자세로 연구에 임하고 있습니다.","en":"I am working to integrate the depth of the humanities with the innovation of digital technology on the canvas of digital humanities. Through collaborative, data-driven Korean Studies research, I aim to connect the past and present, and contribute to the future society. Like the saying, “知其不可而爲之 (zhī qí bù kě ér wéi zhī: to do what one knows to be impossible),” I always approach research with a challenging spirit.","zh":"我致力于在数字人文这一广阔的画布上，将人文学科的深厚内涵与数字技术的创新精神融为一体。通过大家共同参与的、以数据为基础的韩国学研究，我们希望连接过去与现在，并为未来社会做出贡献。正如“知其不可而爲之”，此言常在心中，激励我以无畏之姿，砥砺前行。"},"interests":{"kr":"인문학을 토대로 하는 디지털 기술과의 융합 전반","en":"Overall convergence of digital technology based on the humanities"},"guidance":{"kr":\["튼튼한 인문학 뿌리","디지털 기술에 대한 용감한 도전","융합을 위한 자유로운 정신"\],"en":\["Solid foundation in the humanities","Bold challenge to digital technology","Free spirit for convergence"\]},"keywords":{"kr":\["디지털 인문학","시맨틱 데이터 (LOD/RDF)","지식 그래프 (KAG)","역사인물 온톨로지","텍스트 마이닝 · 계량 문체론","고문헌 AI"\],"en":\["Digital Humanities","Semantic Data (LOD/RDF)","Knowledge Graph (KAG)","Historical Figure Ontology","Text Mining & Stylometry","AI for Classical Texts"\]}},"education":\[{"period":"2013.03.\~2017.08.","degree_kr":"철학박사 (박사)","degree_en":"Ph.D. in Philosophy","inst_kr":"한국학중앙연구원 한국학대학원 인문정보학","inst_en":"Graduate School of Korean Studies, The Academy of Korean Studies (Humanities and Information Science)","thesis_kr":"제도와 인사의 관계성 데이터 아카이브 구축과 활용 - 근대 학교 자료(1895\~1910)를 중심으로 -","thesis_en":"Construction and Utilization of Relationship Data Archives between Institutions and Personnel - Focusing on Modern School Data (1895\~1910) -","advisor_kr":"김현","advisor_en":"Kim Hyun"},{"period":"2007.09.\~2011.01.","degree_kr":"역사학석사 (석사)","degree_en":"M.A. in History","inst_kr":"北京大學 역사학과","inst_en":"Department of History, Peking University","thesis_kr":"试论粟特人在韩半岛 (On The Sogdians in Korean Peninsula)","thesis_en":"On The Sogdians in Korean Peninsula (试论粟特人在韩半岛)","advisor_kr":"罗新","advisor_en":"Luo Xin"},{"period":"2003.09.\~2007.07.","degree_kr":"역사학학사 (학사)","degree_en":"B.A. in History","inst_kr":"北京大學 역사학과","inst_en":"Department of History, Peking University","thesis_kr":"神竿淺談:北亞和中原以及韓半島地區的神竿比較","thesis_en":"Introduction of Holy-stick: Comparison of Holy-stick in North Asia, Central China and Korean Peninsula Regions (神竿淺談)","advisor_kr":"王小甫","advisor_en":"Wang Xiaofu"}\],"career":\[{"period":"2025.10.\~현재","period_en":"2025.10.\~Present","current":true,"kr":"한국학중앙연구원(The Academy of Korean Studies) 부교수(Associate Professor)","en":"Associate Professor, The Academy of Korean Studies"},{"period":"2021.09.\~2025.09.","period_en":"2021.09.\~2025.09.","current":false,"kr":"한국학중앙연구원 조교수","en":"Assistant Professor, The Academy of Korean Studies"},{"period":"2015.03.\~2022.03.","period_en":"2015.03.\~2022.03.","current":false,"kr":"한국외국어대학교 객원강의교수(시간강사)","en":"Visiting Lecturer, Hankuk University of Foreign Studies"},{"period":"2021.03.\~2021.08.","period_en":"2021.03.\~2021.08.","current":false,"kr":"경희대학교 시간강사","en":"Lecturer, Kyung Hee University"},{"period":"2020.07.\~2021.08.","period_en":"2020.07.\~2021.08.","current":false,"kr":"한국학중앙연구원 디지털인문학연구소 한국연구재단 학술연구교수(A유형)","en":"NRF Academic Research Professor (Type A), Center for Digital Humanities, The Academy of Korean Studies"},{"period":"2018.01.\~2020.06.","period_en":"2018.01.\~2020.06.","current":false,"kr":"중앙대학교 HK+인공지능인문학사업단 HK연구교수","en":"HK Research Professor, HK+ Artificial Intelligence Humanities Project Group, Chung-Ang University"},{"period":"2015.03.\~2017.08.","period_en":"2015.03.\~2017.08.","current":false,"kr":"아주대학교 시간강사","en":"Lecturer, Ajou University"},{"period":"2015.03.\~2015.12.","period_en":"2015.03.\~2015.12.","current":false,"kr":"서울기독대학교 시간강사","en":"Lecturer, Seoul Christian University"}\],"activities":\[{"period":"2026.05.\~2028.04.","current":true,"kr":"한국유교문화진흥자문위원회 국학진흥분과 위원","en":"Committee Member, Korean Studies Promotion Subcommittee, Korea Confucian Culture Promotion Advisory Committee"},{"period":"2023.02.\~2027.12.","current":true,"kr":"한국디지털인문학협의회 총무이사","en":"Managing Director, Korean Association for Digital Humanities (KADH)"},{"period":"2026.01.\~2027.12.","current":true,"kr":"글로벌문화콘텐츠학회 연구이사","en":"Research Director, Global Cultural Contents Society"},{"period":"2024.01.\~2027.12.","current":true,"kr":"글로벌문화콘텐츠학회 편집위원","en":"Editorial Board Member, Global Cultural Contents Society"},{"period":"2024.01.\~2027.12.","current":true,"kr":"국제어문학회 지역이사","en":"Regional Director, International Language and Literature Association"},{"period":"2025.03.\~2027.02.","current":true,"kr":"청계사학회 연구이사","en":"Research Director, Cheonggye Historical Society"},{"period":"2023.01.\~2026.12.","current":true,"kr":"인문콘텐츠학회 연구이사","en":"Research Director, Humanities Contents Society"},{"period":"2024.05.\~2026.04.","current":false,"kr":"한국유교문화진흥자문위원회 국학자료 보존·계승분과위원회 위원","en":"Committee Member, National Classical Archives Preservation and Inheritance Subcommittee, Korea Confucian Culture Promotion Advisory Committee"},{"period":"2023.01.\~2024.12.","current":false,"kr":"청계사학회 상임이사","en":"Standing Director, Cheonggye Historical Society"},{"period":"2023.01.\~2024.12.","current":false,"kr":"한국기록관리학회 대외협력이사","en":"Director of External Cooperation, Korean Society of Archival Studies"},{"period":"2022.12.\~2024.10.","current":false,"kr":"한국연구재단 선도연구센터(CRC) 전담 평가위원","en":"Dedicated Evaluation Committee Member, NRF Leading Research Center (CRC)"},{"period":"2022.01.\~2023.12.","current":false,"kr":"글로벌문화콘텐츠학회 정보이사","en":"Information Director, Global Cultural Contents Society"},{"period":"2021.01.\~2022.12.","current":false,"kr":"인문콘텐츠학회 정보이사","en":"Information Director, Humanities Contents Society"}\],"intramural":\[{"period":"2025.10.\~2027.10.","current":true,"kr":"<한국학> 연구윤리위원회 위원","en":"Committee Member, Research Ethics Committee of Korean Studies (Hangukhak)"},{"period":"2024.02.\~2027.02.","current":true,"kr":"기숙사 사감","en":"Dormitory Superintendent (Residence Hall Director), AKS"},{"period":"2024.02.\~2026.02.","current":false,"kr":"한국학자료통합플랫폼 사업 운영위원회 위원","en":"Steering Committee Member, Integrated Korean Studies Data Platform Project"},{"period":"2025.01.\~2025.12.","current":false,"kr":"장학생선발위원회 위원","en":"Committee Member, Scholarship Selection Committee"},{"period":"2023.07.\~2025.07.","current":false,"kr":"한국학정보화사업위원회 위원","en":"Committee Member, Korean Studies Informatization Project Committee"},{"period":"2023.05.\~2025.05.","current":false,"kr":"국제교류위원회 위원","en":"Committee Member, International Exchange Committee"},{"period":"2023.03.\~2024.03.","current":false,"kr":"교수협의회 총무","en":"Secretary-General, Faculty Council"}\],"books":\[{"date":"2026.02.","type":"co","kr_title":"K-인문2.0 디지털 인문학과 '전통'의 문턱","kr_pub":"(주식회사)드림디자인","en_title":"K-Humanities 2.0: Digital Humanities and the Threshold of 'Tradition'","en_pub":"Dream Design Co., Ltd."},{"date":"2025.10.","type":"co","kr_title":"문학 감정 읽는 AI","kr_pub":"커뮤니케이션북스","en_title":"AI that Reads Literary Emotions","en_pub":"Communication Books"},{"date":"2023.03.","type":"co","kr_title":"한국과 중국의 디지털인문학 연구 1","kr_pub":"문예원","en_title":"Digital Humanities Research in Korea and China 1","en_pub":"MunyeWon"},{"date":"2023.02.","type":"co","kr_title":"디지털로 읽고 데이터로 쓰다: 디지털 한국어문학의 모색","kr_pub":"박문사","en_title":"Reading with Digital, Writing with Data: In Search of Digital Korean Literature","en_pub":"Bakmunsa"},{"date":"2022.03.","type":"co","kr_title":"AI가 내려온다 - 인공 지능 시대의 고전 문학 연구","kr_pub":"사이언스북스","en_title":"AI Comes Down - Classical Literature Research in the Age of Artificial Intelligence","en_pub":"ScienceBooks"},{"date":"2022.02.","type":"co","kr_title":"디지털 인문학과 사전","kr_pub":"단국대학교출판부","en_title":"Dictionary of Digital Humanities","en_pub":"Dankook University Press"},{"date":"2021.12.","type":"co","kr_title":"금속활자인쇄술과 역사발전Ⅱ - 활자에서 디지털문명으로","kr_pub":"청주고인쇄박물관","en_title":"Metal Type Printing and Historical Development II - From Type to Digital Civilization","en_pub":"Cheongju Ancient Printing Museum"},{"date":"2021.04.","type":"co","kr_title":"인공지능, 문학과 예술을 만나다","kr_pub":"연경문화사","en_title":"Artificial Intelligence Meets Literature and Art","en_pub":"Yeongyeong Munhwasa"},{"date":"2020.12.","type":"co","kr_title":"미래는 AI의 것일까? : 인공 지능과 미래 사회","kr_pub":"사이언스북스","en_title":"Will the Future Belong to AI? : Artificial Intelligence and the Future Society","en_pub":"ScienceBooks"},{"date":"2018.12.","type":"solo","kr_title":"시맨틱 데이터 아카이브의 구축과 활용 : 제도와 인사의 관계에 대한 근대(1895\~1910) 학교 자료를 중심으로","kr_pub":"보고사","en_title":"Construction and Utilization of Semantic Data Archives: Focusing on Modern (1895\~1910) School Data on the Relationship Between Institutions and Personnel","en_pub":"Bogosa"},{"date":"2016.05.","type":"co","kr_title":"디지털 인문학 입문","kr_pub":"HUEBOOKs : 한국외국어대학교지식출판원","en_title":"Introduction to Digital Humanities","en_pub":"HUEBOOKs: Hankuk University of Foreign Studies Knowledge Publishing Center"}\],"papers":\[{"date":"2025.06.","kr_title":"디지털 시대의 역사 서술 ― 디지털 독본과 디지털 사관 ―","kr_journal":"관악사론","en_title":"Historical Narration in the Digital Age ― Digital Readers and Digital Historiography ―","en_journal":"Gwanak Saron"},{"date":"2025.01.","kr_title":"조선총독부박물관 문서 XML 데이터 설계 및 활용 시론 －XML 기반 다중 분류 체계 및 내⋅외부 데이터 연결을 중심으로－","kr_journal":"인문과학","en_title":"A Study on the XML Data Design and Utilization of the Museum Documents of the Japanese Government-General of Korea - Focusing on XML-based Multiple Classification System and Connection of Internal and External Data -","en_journal":"Humanities Science"},{"date":"2024.12.","kr_title":"국문장편소설의 감정에 대한 정성적·정량적 연구 시론–<창선감의록>과 <소현성록>을 중심으로–","kr_journal":"고소설연구","en_title":"A Qualitative and Quantitative Study on the Emotion of Korean Long Novels - Focusing on <Changseongamuirok> and <Sohyeonseongrok> -","en_journal":"Classical Novel Research"},{"date":"2024.05.","kr_title":"국사편찬위원회 한국근현대잡지자료 데이터(2024.03.27.)","kr_journal":"디지털인문학","en_title":"National Institute of Korean History Data on Modern and Contemporary Korean Magazines (2024.03.27.)","en_journal":"Digital Humanities"},{"date":"2023.09.","kr_title":"한국역사인물데이터베이스 설계 시론: 홍문록(弘文錄)을 예시로 하여","kr_journal":"한국학","en_title":"A Study on the Design of Korean Historical Figures Database: Using Hongmunrok as an Example","en_journal":"Korean Studies"},{"date":"2023.02.","kr_title":"텍스트 마이닝을 통한 한중 웹소설 플랫폼 비교 분석","kr_journal":"인문사회과학연구","en_title":"A Comparative Analysis of Korean and Chinese Web Novel Platforms through Text Mining","en_journal":"Humanities and Social Science Research"},{"date":"2022.12.","kr_title":"한국 대중 서사 기반 감정 데이터 구축과 활용 - 감정 딥러닝 모델 구현을 통한 문학 연구의 활용 가능성 탐색을 중심으로 -","kr_journal":"인공지능인문학연구","en_title":"Construction and Utilization of Emotion Data Based on Korean Popular Narrative - Focusing on the Exploration of the Applicability of Literary Research through the Implementation of Emotion Deep Learning Model -","en_journal":"Artificial Intelligence Humanities Research"},{"date":"2022.08.","kr_title":"조선시대 중국어 역학서 어휘 및 어음 정보의 시맨틱 데이터 구축 연구","kr_journal":"중국학보","en_title":"A Study on the Construction of Semantic Data for Vocabulary and Phonetic Information in Joseon Dynasty Chinese Language Textbooks (Yeokhakseo)","en_journal":"Chinese Studies Review"},{"date":"2022.05.","kr_title":"<공공데이터법>과 인문데이터 －공공기관 보유 인문데이터 공개 신청 사례를 중심으로","kr_journal":"한국고전연구","en_title":"<Public Data Act> and Humanities Data －Focusing on Cases of Applying for Disclosure of Humanities Data Held by Public Institutions","en_journal":"Korean Classical Studies"},{"date":"2022.03.","kr_title":"조선시대 중국어 역학서 데이터베이스 구축 연구","kr_journal":"중국학","en_title":"A Study on the Construction of a Database for Joseon Dynasty Chinese Language Textbooks (Yeokhakseo)","en_journal":"Chinese Studies"},{"date":"2022.02.","kr_title":"사회 네트워크 분석을 활용한 1930년대 후반 동인시지(詩誌)와 시인","kr_journal":"인문논총","en_title":"Donginsi and Poets of the Late 1930s Using Social Network Analysis","en_journal":"Humanities Review"},{"date":"2022.02.","kr_title":"18세기 일본 문인 시사의 디지털 아카이브 설계 및 구축 시론","kr_journal":"日本學報","en_title":"A Study on the Design and Construction of a Digital Archive of Japanese Literary Poetry in the 18th Century","en_journal":"Journal of Japanese Studies"},{"date":"2021.08.","kr_title":"딥러닝을 활용한 시조의 유형 고찰 - 영남가단과 호남가단의 시조를 중심으로","kr_journal":"문화와 융합","en_title":"A Study on the Types of Sijo Using Deep Learning - Focusing on Sijo of Yeongnam and Honam Poetry Circles","en_journal":"Culture and Convergence"},{"date":"2021.07.","kr_title":"인공지능 시대의 사전과 데이터 - 한국역사인물사전(데이터)을 위한 탐색 -","kr_journal":"동양학","en_title":"Dictionaries and Data in the Age of Artificial Intelligence - In Search of the Korean Historical Figures Dictionary (Data) -","en_journal":"Oriental Studies"},{"date":"2020.09.","kr_title":"우리는 서발턴의 목소리를 들을 준비가 되었는가? : 텍스트 마이닝을 통한 영화 <82년생 김지영> 리뷰 분석","kr_journal":"인문콘텐츠","en_title":"Are We Ready to Hear the Voice of the Subaltern? : Review Analysis of the Movie <Kim Ji-young, Born 1982> through Text Mining","en_journal":"Humanities Contents"},{"date":"2020.08.","kr_title":"디지털 분석 기법을 활용한 시조 연구 방법 탐색- <한국시조대사전> 수록 단형시조를 중심으로-","kr_journal":"다문화콘텐츠연구","en_title":"Exploration of Sijo Research Methods Using Digital Analysis Techniques - Focusing on Short Sijo in the <Grand Dictionary of Korean Sijo> -","en_journal":"Multicultural Contents Research"},{"date":"2020.08.","kr_title":"자율주행 자동차 논의에 있어서 인간의 자리: 자율주행 자동차에 대한 논의의 특징과 한계","kr_journal":"인문사회 21","en_title":"Human's Place in Autonomous Driving Car Discussions: Characteristics and Limitations of Discussions on Autonomous Driving Cars","en_journal":"Humanities and Society 21"},{"date":"2020.06.","kr_title":"빅데이터를 활용한 도덕기반 텍스트분석: 입시 기사를 중심으로","kr_journal":"디지털콘텐츠학회논문지","en_title":"Moral-Based Text Analysis Using Big Data: Focusing on Entrance Examination Articles","en_journal":"Journal of Digital Contents Society"},{"date":"2020.06.","kr_title":"한국어 감정 디지털 온톨로지 구축에 관한 연구","kr_journal":"한국어 의미학","en_title":"A Study on the Construction of Korean Emotion Digital Ontology","en_journal":"Korean Semantics"},{"date":"2020.03.","kr_title":"딥러닝을 활용한 경판 방각본 소설의 유형 고찰 -영웅소설과 애정소설 유형을 중심으로-","kr_journal":"국제어문","en_title":"A Study on the Types of Gyeongpan Woodblock Printed Novels Using Deep Learning - Focusing on Heroic Novels and Love Novels -","en_journal":"International Language and Literature"},{"date":"2019.12.","kr_title":"고전소설에 대한 디지털 감정 분석방법론 탐색－<구운몽>을 대상으로－","kr_journal":"동아시아고대학","en_title":"Exploration of Digital Emotion Analysis Methodology for Classical Novels －Focused on <Nine Cloud Dream>－","en_journal":"East Asian Ancient Studies"},{"date":"2019.10.","kr_title":"디지털 맵핑(Mapping)을 통한 <구운몽> 연구 및 교육적 활용","kr_journal":"열상고전연구","en_title":"Research and Educational Utilization of <Nine Cloud Dream> through Digital Mapping","en_journal":"Yeolsang Classical Studies Research"},{"date":"2019.10.","kr_title":"디지털 분석 기법을 활용한 시조문학 연구 - 인공지능(AI) 제재 창작 시조를 중심으로 -","kr_journal":"문화와 융합","en_title":"Sijo Literature Research Using Digital Analysis Techniques - Focusing on Creative Sijo with Artificial Intelligence (AI) Themes -","en_journal":"Culture and Convergence"},{"date":"2019.06.","kr_title":"빅데이터와 고전문학 연구방법론","kr_journal":"어문론집","en_title":"Big Data and Classical Literature Research Methodology","en_journal":"Journal of Language and Literature"},{"date":"2019.06.","kr_title":"딥러닝으로 불경 읽기 - Word2Vec으로 CBETA 불경 데이터 읽기","kr_journal":"원불교사상과 종교문화","en_title":"Reading Buddhist Scriptures with Deep Learning - Reading CBETA Buddhist Scripture Data with Word2Vec","en_journal":"Won Buddhism Thought and Religious Culture"},{"date":"2019.05.","kr_title":"人工智能时代的“新子学”试探","kr_journal":"名作欣赏 (Masterpieces Review)","en_title":"A Trial of “New Studies of the Masters” in the Age of Artificial Intelligence","en_journal":"Masterpieces Review (名作欣赏)"},{"date":"2019.04.","kr_title":"인공지능 시대를 위한 인문데이터의 역사와 과제","kr_journal":"인공지능인문학연구","en_title":"The History and Tasks of Humanities Data for the Artificial Intelligence Era","en_journal":"Artificial Intelligence Humanities Research"},{"date":"2019.03.","kr_title":"디지털 인문학의 관점에서 본 디지털 불교학","kr_journal":"불교학보","en_title":"Digital Buddhist Studies from the Perspective of Digital Humanities","en_journal":"Journal of Buddhist Studies"},{"date":"2019.03.","kr_title":"계량적 문체 분석을 통한 <소현성록> 연작의 변이양상 고찰 - 이대15권본과 규장각21권본을 중심으로 -","kr_journal":"국제어문","en_title":"A Study on the Variation of <Sohyeonseongrok> Series through Quantitative Style Analysis - Focusing on Ewha 15 Volume Edition and Kyujanggak 21 Volume Edition -","en_journal":"International Language and Literature"},{"date":"2018.12.","kr_title":"소현성록 연작의 문체론적 고찰 －컴퓨터를 활용한 계층분석을 바탕으로","kr_journal":"인문과학연구","en_title":"A Stylistic Study on the <Sohyeonseongrok> Series －Based on Computer-Aided Layer Analysis","en_journal":"Humanities Science Research"},{"date":"2018.12.","kr_title":"인공지능에 대한 인간의 감정 고찰 -알파고 VS 이세돌 대국에 관한 신문기사 분석을 중심으로","kr_journal":"윤리연구","en_title":"A Study on Human Emotion toward Artificial Intelligence - Focusing on Newspaper Article Analysis on the AlphaGo VS Lee Se-dol Match","en_journal":"Ethics Studies"},{"date":"2018.09.","kr_title":"부끄러움/창피함/쑥스러움/수치스러움/수줍음간의 관계 고찰: 공기 명사 및 네트워크 분석을 통한 문맥 분석","kr_journal":"언어","en_title":"A Study on the Relationship among Shame/Embarrassment/Awkwardness/Humiliation/Shyness: Context Analysis through Co-occurrence Nouns and Network Analysis","en_journal":"Language"},{"date":"2018.08.","kr_title":"인공지능을 활용한 <소현성록> 연작의 감정 연구","kr_journal":"문화와 융합","en_title":"Emotion Research of <Sohyeonseongrok> Series Using Artificial Intelligence","en_journal":"Culture and Convergence"},{"date":"2018.07.","kr_title":"<소현성록> 연작에 나타난 감정의 출현 빈도와 의미— 컴퓨터를 활용한 통계학적 분석을 바탕으로 —","kr_journal":"온지논총","en_title":"Frequency and Meaning of Emotion Appearance in the <Sohyeonseongrok> Series—Based on Statistical Analysis Using Computers—","en_journal":"Onji Review"},{"date":"2018.04.","kr_title":"동양 시간LOD 시론","kr_journal":"인공지능인문학연구","en_title":"A Study on the LOD of Oriental Time","en_journal":"Artificial Intelligence Humanities Research"},{"date":"2017.06.","kr_title":"영화 수용과 지배욕망: 트위터, 영화리뷰에 대한 정신분석적 텍스트마이닝을 통한 <명량> 수용 분석","kr_journal":"비평과이론","en_title":"Film Acceptance and Dominance Desire: Twitter, Acceptance Analysis of <Roaring Currents> through Psychoanalytic Text Mining of Film Reviews","en_journal":"Criticism and Theory"},{"date":"2016.06.","kr_title":"역사기록의 전자문서 편찬방법 탐구 - 역사요소를 중심으로 -","kr_journal":"열상고전연구","en_title":"Exploration of Electronic Document Compilation Methods for Historical Records - Focusing on Historical Elements -","en_journal":"Yeolsang Classical Studies Research"},{"date":"2016.02.","kr_title":"韓國數位人文教育現狀與課題","kr_journal":"漢學研究通訊 (Newsletter for Research in Chinese Studies)","en_title":"Current Status and Tasks of Korean Digital Humanities Education","en_journal":"Newsletter for Research in Chinese Studies (漢學研究通訊)"},{"date":"2014.09.","kr_title":"미국 인문학재단(NEH)의 디지털인문학 육성 사업","kr_journal":"인문콘텐츠","en_title":"Digital Humanities Promotion Project of the National Endowment for the Humanities (NEH) in the United States","en_journal":"Humanities Contents"},{"date":"2014.06.","kr_title":"해외 디지털인문학 동향","kr_journal":"인문콘텐츠","en_title":"Trends in Overseas Digital Humanities","en_journal":"Humanities Contents"}\],"projects":\[{"period":"2026.11.11.\~2026.12.11.","ongoing":true,"role":"pi","budget":"4,000,000","kr_funder":"한국전통문화대학교(HI Lab)","kr_title":"자동 생성 스토리텔링 콘텐츠 만족도 조사(CSAT) 학술용역","kr_role":"연구책임자","en_funder":"Korea National University of Heritage (HI Lab)","en_title":"Customer Satisfaction Survey (CSAT) on Automatically Generated Storytelling Content","en_role":"Principal Investigator"},{"period":"2026.09.01.\~2027.02.28.","ongoing":true,"role":"pi","budget":"16,000,000","kr_funder":"한국학중앙연구원 연구·교육 연계과제 (D26050 / AKSR2026-RE09)","kr_title":"조선시대 흉배(胸背) 연구의 디지털 전환: 시맨틱 데이터 편찬과 정량 분석·AI 분류 방법론","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (D26050 / AKSR2026-RE09)","en_title":"Digital Transformation of Joseon Dynasty Hyungbae (Rank Badges) Research: Semantic Data Compilation, Quantitative Analysis, and AI Classification Methodology","en_role":"Principal Investigator"},{"period":"2026.07.01.\~2032.06.30.","ongoing":true,"role":"co","budget":"1,800,000,000","kr_funder":"한국학진흥사업단 한국학기초자료사업 (AKS-2026-CDM-1260001)","kr_title":"한국학 기초자료 통합 DB구축 및 서비스 고도화","kr_role":"공동연구원 (연구책임자: 김동건)","en_funder":"Korean Studies Promotion Service (AKS-2026-CDM-1260001)","en_title":"Integrated Database Construction and Service Advancement for Foundational Korean Studies Materials","en_role":"Co-Researcher (PI: Kim Dong-geon)"},{"period":"2026.07.01.\~2026.12.중순","period_en":"2026.07.01.\~2026.12.","ongoing":true,"role":"pi","budget":"476,788,000","kr_funder":"국가유산청 (26국가유산진흥원-KBR)","kr_title":"2026년 국가유산 안내판 문안 정비 학술 용역","kr_role":"연구책임자","en_funder":"Korea Heritage Service (26KHA-KBR)","en_title":"2026 Academic Research Service for Refining National Heritage Signboard Texts","en_role":"Principal Investigator"},{"period":"2026.06.01.\~2029.05.31.","ongoing":true,"role":"pi","budget":"60,000,000","kr_funder":"한국연구재단 2026년도 신진연구지원사업 (2026S1A5A8005210)","kr_title":"지식 그래프 기반 근대 인물 LOD 구축 및 LLM 연계를 위한 지식 보충 생성(KAG) 모델 연구","kr_role":"연구책임자","en_funder":"National Research Foundation of Korea (2026S1A5A8005210)","en_title":"Knowledge Graph-Based Modern Historical Figure LOD Construction and Knowledge-Augmented Generation (KAG) Model Research for LLM Integration","en_role":"Principal Investigator"},{"period":"2026.03.01.\~2027.02.28.","ongoing":true,"role":"co","budget":"20,000,000","kr_funder":"한국연구재단 (국제) 한-독 R&D 네트워크프로그램 (RS-2026-16362981)","kr_title":"문학적 횡단의 지식 그래프: 링크드 오픈 데이터를 활용한 유럽-한국 문학 번역사 모델링","kr_role":"공동연구원 (연구책임자: 김병준)","en_funder":"National Research Foundation of Korea (RS-2026-16362981, Korea-Germany R&D Network)","en_title":"Knowledge Graph of Literary Crossings: Modeling the History of European-Korean Literary Translation Using Linked Open Data","en_role":"Co-Researcher (PI: Kim Byung-jun)"},{"period":"2024.09.01.\~2030.08.31.","ongoing":true,"role":"co","budget":"1,560,000,000","kr_funder":"한국연구재단 인문사회연구소지원사업 (2024S1A5C2A02046358)","kr_title":"훈민정음으로 기록된 근세시기 동아시아 언어 자료 DB 구축","kr_role":"공동연구원 (연구책임자: 심소희)","en_funder":"National Research Foundation of Korea (2024S1A5C2A02046358)","en_title":"Establishment of a DB for Early Modern East Asian Language Materials Recorded in Hunminjeongeum","en_role":"Co-Researcher (PI: Sim So-hee)"},{"period":"2026.05.19.\~2026.09.15.","ongoing":false,"role":"pi","budget":"19,800,000","kr_funder":"국립중앙도서관 고문헌과 (26국립중앙도서관-김바로)","kr_title":"AI 신기술 활용 고문헌 업무지원을 위한 기초연구 용역","kr_role":"연구책임자","en_funder":"National Library of Korea (Rare Books Division)","en_title":"Foundational Research on Supporting Classical Document Operations Using Emerging AI Technologies","en_role":"Principal Investigator"},{"period":"2026.03.03.\~2026.08.31.","ongoing":false,"role":"pi","budget":"16,000,000","kr_funder":"한국학중앙연구원 연구·교육 연계과제 (D26028 / AKSR2026-RE03)","kr_title":"인공지능(AI) 기반 디지털 한국학 데이터 구축 매뉴얼 편찬 및 교육 콘텐츠 개발","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (D26028 / AKSR2026-RE03)","en_title":"Compilation of an AI-Based Digital Korean Studies Data Construction Manual and Development of Educational Content","en_role":"Principal Investigator"},{"period":"2025.09.01.\~2026.02.28.","ongoing":false,"role":"pi","budget":"16,000,000","kr_funder":"한국학중앙연구원 연구·교육 연계과제 (D25037 / AKSR2025-RE08)","kr_title":"AI 스마트 도슨트 구현을 위한 다국어·다층적 문화유산 안내문 생성 플랫폼 구축 연구: 조선시대 불교회화를 중심으로","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (D25037 / AKSR2025-RE08)","en_title":"A Study on the Establishment of a Platform for Generating Multilingual and Multilayered Cultural Heritage Descriptions for AI Smart Docent Implementation: Focusing on Joseon Dynasty Buddhist Paintings","en_role":"Principal Investigator"},{"period":"2025.09.25.\~2025.10.10.","ongoing":false,"role":"pi","budget":"1,590,000","kr_funder":"충북역사문화연구원 (25충북역사문화연구원-김바로)","kr_title":"2025년 청주시 문화유산 안내판 영문 해설문 집필 및 감수","kr_role":"연구책임자","en_funder":"Chungbuk Institute of History and Culture","en_title":"Writing and Supervising English Explanatory Texts for Cheongju City Cultural Heritage Signboards in 2025","en_role":"Principal Investigator"},{"period":"2025.04.25.\~2025.11.20.","ongoing":false,"role":"pi","budget":"106,272,000","kr_funder":"재단법인 한국학호남진흥원 (25호남진흥원-김바로)","kr_title":"시맨틱데이터 및 서버관리 용역","kr_role":"연구책임자","en_funder":"Honam Academy of Korean Studies Foundation","en_title":"Semantic Data and Server Management Services","en_role":"Principal Investigator"},{"period":"2025.02.10.\~2025.02.24.","ongoing":false,"role":"pi","budget":"2,457,000","kr_funder":"(주)삼진건축사사무소 (25삼진건축사사무소-김바로)","kr_title":"화순군 문화유산 안내판 영문 해설문 집필 및 감수","kr_role":"연구책임자","en_funder":"Samjin Architects Co., Ltd.","en_title":"Writing and Supervising English Explanatory Texts for Hwasun County Cultural Heritage Signboards","en_role":"Principal Investigator"},{"period":"2025.01.02.\~2025.12.16.","ongoing":false,"role":"pi","budget":"35,000,000","kr_funder":"한국학중앙연구원 공동연구과제 (D25006 / AKSR2025-C06)","kr_title":"조선시대 종묘 배향공신 연구","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (D25006 / AKSR2025-C06)","en_title":"A Study on the Meritorious Retainers Enshrined in the Jongmyo Shrine during the Joseon Dynasty","en_role":"Principal Investigator"},{"period":"2024.09.02.\~2025.02.28.","ongoing":false,"role":"pi","budget":"16,000,000","kr_funder":"한국학중앙연구원 연구교육\_연계과제 (AKSR2024-RE08)","kr_title":"正祖命撰《人物考》 온톨로지 설계 및 LOD(Linked Open Data) 시스템 구축","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (AKSR2024-RE08)","en_title":"Ontology Design and Linked Open Data (LOD) System Construction for “Inmulgo” (人物考) Compiled by King Jeongjo's Order","en_role":"Principal Investigator"},{"period":"2024.03.04.\~2024.08.30.","ongoing":false,"role":"pi","budget":"16,000,000","kr_funder":"한국학중앙연구원 연구교육\_연계과제 (AKSR2024-RE02)","kr_title":"고문헌 데이터 설계를 위한 선행 모델 분석 및 교육 콘텐츠 구축","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (AKSR2024-RE02)","en_title":"Analysis of Preceding Models and Development of Educational Content for Old Document Data Design","en_role":"Principal Investigator"},{"period":"2023.09.01.\~2024.02.29.","ongoing":false,"role":"pi","budget":"16,000,000","kr_funder":"한국학중앙연구원 연구교육\_연계과제 (AKSR2023-RE07)","kr_title":"한국학 시맨틱 웹 구축을 위한 선행 온톨로지 모델의 탐색과 교육","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (AKSR2023-RE07)","en_title":"Exploration of Preceding Ontology Models and Education for Building a Korean Studies Semantic Web","en_role":"Principal Investigator"},{"period":"2023.05.25.\~2023.12.16.","ongoing":false,"role":"co","budget":"20,000,000","kr_funder":"한국학중앙연구원 정책연구과제 (AKSR2023-P01)","kr_title":"중국의 한국학 현황 연구 Ⅱ : 저서와 박사학위논문을 중심으로","kr_role":"공동연구원 (연구책임자: 서승희)","en_funder":"The Academy of Korean Studies (AKSR2023-P01)","en_title":"Research on the Current Status of Korean Studies in China Ⅱ: Focusing on Books and Doctoral Dissertations","en_role":"Co-Researcher (PI: Seo Seung-hee)"},{"period":"2023.03.28.\~2023.11.30.","ongoing":false,"role":"pi","budget":"71,363,630","kr_funder":"국립문화재연구원 (23국립문화재연구원-김바로)","kr_title":"한국고고학사전 정보 메타데이터 설계 연구용역","kr_role":"연구책임자","en_funder":"National Research Institute of Cultural Heritage","en_title":"Research Service for Information Metadata Design of the Korean Archaeological Dictionary","en_role":"Principal Investigator"},{"period":"2023.03.02.\~2023.08.31.","ongoing":false,"role":"pi","budget":"16,000,000","kr_funder":"한국학중앙연구원 연구교육\_연계과제 (AKSR2023-RE01)","kr_title":"인문학도를 위한 데이터 분석 교육 콘텐츠 편찬 - 한국학 데이터를 중심으로","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (AKSR2023-RE01)","en_title":"Compilation of Data Analysis Educational Content for Humanities Students - Focusing on Korean Studies Data","en_role":"Principal Investigator"},{"period":"2023.01.01.\~2023.12.16.","ongoing":false,"role":"pi","budget":"35,000,000","kr_funder":"한국학중앙연구원 공동연구과제 (AKSR2023-C06)","kr_title":"조선후기 『정록(政錄)』의 자료적 가치와 음관(蔭官)의 인사 실태에 관한 연구","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (AKSR2023-C06)","en_title":"Research on the Data Value of “Jeongrok” (政錄) and the Personnel Status of “Eumgwan” (蔭官) in the Late Joseon Dynasty","en_role":"Principal Investigator"},{"period":"2022.10.06.\~2022.12.29.","ongoing":false,"role":"co","budget":"6,000,000","kr_funder":"전통문화연구회","kr_title":"동양고전 메타버스 구축을 위한 기획 연구 - 曲阜 孔子博物館과 長崎 孔子廟 中国歴代博物館을 중심으로","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Institute of Traditional Culture and Studies","en_title":"Planning Research for Building an Oriental Classics Metaverse - Focusing on the Confucius Museum in Qufu and the Confucius Temple in Nagasaki","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2022.09.01.\~2023.02.28.","ongoing":false,"role":"pi","budget":"16,000,000","kr_funder":"한국학중앙연구원 연구교육\_연계과제 (AKSR2022-RE08)","kr_title":"강릉 12향현(江陵 十二鄕賢) 멀티미디어콘텐츠 편찬 및 교육 동영상 제작","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (AKSR2022-RE08)","en_title":"Compilation of Multimedia Content and Production of Educational Videos for the Twelve Sages of Gangneung (江陵 十二鄕賢)","en_role":"Principal Investigator"},{"period":"2022.07.01.\~2025.06.30.","ongoing":false,"role":"co","budget":"450,000,000","kr_funder":"한국연구재단 글로벌인문사회융합연구지원사업 (2022S1A5A2A03052880)","kr_title":"인간과 협업하는 딥러닝 기반 AI 소설 생성 융합 연구","kr_role":"공동연구원 (연구책임자: 윤미선)","en_funder":"National Research Foundation of Korea (2022S1A5A2A03052880)","en_title":"Convergence Research on Deep Learning-based AI Novel Generation in Collaboration with Humans","en_role":"Co-Researcher (PI: Yoon Mi-sun)"},{"period":"2022.06.10.\~2022.12.09.","ongoing":false,"role":"co","budget":"430,000,000","kr_funder":"문화재청, (주)PCN","kr_title":"2022 한양도성 타임머신 사업 빅데이터 아카이브 구축","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Cultural Heritage Administration, PCN Co., Ltd.","en_title":"2022 Hanyangdoseong Time Machine Project Big Data Archive Construction","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2022.05.27.\~2022.12.16.","ongoing":false,"role":"co","budget":"20,000,000","kr_funder":"한국학중앙연구원 정책연구과제 (AKSR2022-P02)","kr_title":"중국의 한국학 현황 연구 : 저서와 박사학위논문을 중심으로","kr_role":"공동연구원 (연구책임자: 서승희)","en_funder":"The Academy of Korean Studies (AKSR2022-P02)","en_title":"Research on the Current Status of Korean Studies in China: Focusing on Books and Doctoral Dissertations","en_role":"Co-Researcher (PI: Seo Seung-hee)"},{"period":"2022.02.25.\~2022.07.25.","ongoing":false,"role":"co","budget":"","kr_funder":"육군본부","kr_title":"군사용 인공지능의 안전성 확보를 위한 단계별 윤리적 평가 및 검증요소(기준) 마련 연구","kr_role":"공동연구원 (연구책임자: 최명진)","en_funder":"Republic of Korea Army Headquarters","en_title":"Research on Step-by-Step Ethical Evaluation and Verification Elements (Standards) for Ensuring the Safety of Military Artificial Intelligence","en_role":"Co-Researcher (PI: Choi Myung-jin)"},{"period":"2022.01.01.\~2022.12.16.","ongoing":false,"role":"pi","budget":"35,000,000","kr_funder":"한국학중앙연구원 공동연구과제 (AKSR2022-C14)","kr_title":"조선시대 『홍문록(弘文錄)』과 집권세력의 네트워크","kr_role":"연구책임자","en_funder":"The Academy of Korean Studies (AKSR2022-C14)","en_title":"“Hongmunrok” (弘文錄) and the Network of the Ruling Elite in the Joseon Dynasty","en_role":"Principal Investigator"},{"period":"2021.10.26.\~2021.12.29.","ongoing":false,"role":"co","budget":"6,000,000","kr_funder":"전통문화연구회","kr_title":"동양고전 AI 의미 기반 정보화 및 활용 방안 고도화 - 古宮 懸板과 柱聯의 典故 지식 데이터베이스 구축 및 활용 방안을 중심으로 -","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Institute of Traditional Culture and Studies","en_title":"Advancement of AI Meaning-Based Information and Utilization of Oriental Classics - Focusing on the Construction and Utilization of a Knowledge Database of Allusions on Old Palace Signboards and Couplets","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2021.09.01.\~2022.01.31.","ongoing":false,"role":"co","budget":"750,000,000","kr_funder":"한국연구재단","kr_title":"학술연구교수 성과확산센터 모듈개발과 운영 (전체 \~2026.08.31.)","kr_role":"공동연구원 (연구책임자: 박정원)","en_funder":"National Research Foundation of Korea","en_title":"Development and Operation of a Module for the Academic Research Professor Performance Diffusion Center","en_role":"Co-Researcher (PI: Park Jeong-won)"},{"period":"2021.06.11.\~2021.12.10.","ongoing":false,"role":"co","budget":"430,000,000","kr_funder":"문화재청, (주)PCN","kr_title":"2021 한양도성 타임머신 사업 빅데이터 아카이브 구축","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Cultural Heritage Administration, PCN Co., Ltd.","en_title":"2021 Hanyangdoseong Time Machine Project Big Data Archive Construction","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2021.05.04.\~2022.01.15.","ongoing":false,"role":"co","budget":"50,000,000","kr_funder":"규장각한국학연구원 21세기 신규장각 자료구축 사업","kr_title":"규장각 소장 조선시대 중국어 역학서의 언어 정보 시멘틱 데이터 구축","kr_role":"공동연구원 (연구책임자: 구현아)","en_funder":"Kyujanggak Institute for Korean Studies","en_title":"Construction of Semantic Data for Linguistic Information in Joseon Dynasty Chinese Language Textbooks (Yeokhakseo) in the Kyujanggak Collection","en_role":"Co-Researcher (PI: Koo Hyun-ah)"},{"period":"2020.10.26.\~2021.12.29.","ongoing":false,"role":"co","budget":"6,000,000","kr_funder":"전통문화연구회","kr_title":"동양고전 AI 의미 기반 정보화 및 활용 방안 연구 - 古宮 懸板의 典故 지식 데이터베이스 구축 및 활용 방안을 중심으로 -","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Institute of Traditional Culture and Studies","en_title":"Research on AI Meaning-Based Information and Utilization of Oriental Classics - Focusing on the Construction and Utilization of a Knowledge Database of Allusions on Old Palace Signboards","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2020.09.01.\~2020.12.18.","ongoing":false,"role":"co","budget":"45,330,000","kr_funder":"청주시문화산업진흥재단","kr_title":"코로나19 문화예술 현장 기록 및 연구","kr_role":"공동연구원 (연구책임자: 안태호)","en_funder":"Cheongju City Cultural Industry Promotion Foundation","en_title":"Recording and Research on the COVID-19 Cultural Arts Scene","en_role":"Co-Researcher (PI: Ahn Tae-ho)"},{"period":"2020.08.14.\~2020.12.18.","ongoing":false,"role":"co","budget":"18,000,000","kr_funder":"경기도박물관","kr_title":"경기도 공공박물관 메타아카이브 구축 연구","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Gyeonggi Provincial Museum","en_title":"Research on the Construction of a Meta-Archive for Public Museums in Gyeonggi Province","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2020.08.01.\~2020.12.31.","ongoing":false,"role":"co","budget":"30,000,000","kr_funder":"경제·인문사회연구회 2020년도 인문정책연구사업","kr_title":"감염병 시대의 도덕판단유형 분석: 딥러닝을 활용한 텍스트분석","kr_role":"공동연구원 (연구책임자: 김효은)","en_funder":"National Research Council for Economics, Humanities and Social Sciences","en_title":"Analysis of Moral Judgment Types in the Era of Infectious Diseases: Text Analysis Using Deep Learning","en_role":"Co-Researcher (PI: Kim Hyo-eun)"},{"period":"2020.07.\~2021.08.","ongoing":false,"role":"pi","budget":"40,000,000","kr_funder":"한국연구재단 (A유형) 인문사회학술연구교수 (2020S1A5B5A16082267)","kr_title":"한국 역사 인물 온톨로지 설계와 LOD(Linked Open Data) 서비스 구축 및 운용","kr_role":"연구책임자","en_funder":"National Research Foundation of Korea (2020S1A5B5A16082267)","en_title":"Academic Research Professor (Type A): Korean Historical Figure Ontology Design and LOD (Linked Open Data) Service Construction and Operation","en_role":"Principal Investigator"},{"period":"2020.06.24.\~2020.12.11.","ongoing":false,"role":"co","budget":"380,270,000","kr_funder":"문화재청, (주)PCN","kr_title":"2020 한양도성 타임머신 사업 빅데이터 아카이브 구축","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Cultural Heritage Administration, PCN Co., Ltd.","en_title":"2020 Hanyangdoseong Time Machine Project Big Data Archive Construction","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2019.12.\~2020.03.","ongoing":false,"role":"co","budget":"20,000,000","kr_funder":"경제·인문사회연구회 2019년도 인문정책연구사업","kr_title":"디지털 빅데이터의 시대 인문학의 새로운 역할에 대한 고찰","kr_role":"공동연구원 (연구책임자: 이주영)","en_funder":"National Research Council for Economics, Humanities and Social Sciences","en_title":"A Study on the New Role of Humanities in the Age of Digital Big Data","en_role":"Co-Researcher (PI: Lee Ju-young)"},{"period":"2019.11.11.\~2019.12.29.","ongoing":false,"role":"co","budget":"6,000,000","kr_funder":"전통문화연구회","kr_title":"東洋古典DB 서비스를 위한 딥러닝(深層學習) 기술 활용 방안 연구","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Institute of Traditional Culture and Studies","en_title":"Research on the Utilization of Deep Learning Technology for Oriental Classics DB Service","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2019.09.\~2020.01.","ongoing":false,"role":"co","budget":"","kr_funder":"충남대학교","kr_title":"인문콘텐츠 교재개발 사업","kr_role":"공동연구원 (연구책임자: 서경숙)","en_funder":"Chungnam National University","en_title":"Humanities Content Textbook Development Project","en_role":"Co-Researcher (PI: Seo Kyeong-suk)"},{"period":"2019.05.\~2020.01.","ongoing":false,"role":"co","budget":"","kr_funder":"중앙대학교","kr_title":"텍스트 온톨로지 융합연구그룹","kr_role":"공동연구원 (연구책임자: 김휘택)","en_funder":"Chung-Ang University","en_title":"Text Ontology Convergence Research Group","en_role":"Co-Researcher (PI: Kim Hwi-taek)"},{"period":"2018.03.\~2019.02.","ongoing":false,"role":"co","budget":"","kr_funder":"중앙대학교","kr_title":"텍스트 온톨로지를 기반으로 한 문화콘텐츠 구축","kr_role":"공동연구원 (연구책임자: 김휘택)","en_funder":"Chung-Ang University","en_title":"Construction of Cultural Content Based on Text Ontology","en_role":"Co-Researcher (PI: Kim Hwi-taek)"},{"period":"2017.11.01.\~2020.06.30.","ongoing":false,"role":"co","budget":"","kr_funder":"한국연구재단 인문한국플러스(HK+) 지원사업 (2017S1A6A3A01078538)","kr_title":"포스트휴먼 시대, 인문학 가치 고양을 위한 인공지능인문학 구축","kr_role":"HK연구교수 (연구책임자: 이찬규)","en_funder":"National Research Foundation of Korea (2017S1A6A3A01078538)","en_title":"Construction of Artificial Intelligence Humanities to Enhance the Value of Humanities in the Posthuman Era","en_role":"HK Research Professor (PI: Lee Chan-kyu)"},{"period":"2017.11.\~2017.12.","ongoing":false,"role":"co","budget":"","kr_funder":"전통문화연구회","kr_title":"동양고전지식정보 국제교류 기반 연구 - 네덜란드 라이든 대학교 MARKUS 한국판 공동 연구 개발 방안","kr_role":"공동연구원 (연구책임자: 김현)","en_funder":"Institute of Traditional Culture and Studies","en_title":"Research on the Basis of International Exchange of Oriental Classical Knowledge Information - Joint Research and Development Plan for the Korean Edition of MARKUS at Leiden University","en_role":"Co-Researcher (PI: Kim Hyun)"},{"period":"2017.02.\~2019.01.","ongoing":false,"role":"co","budget":"","kr_funder":"Leiden University","kr_title":"K-MARKUS - Critical Approaches to New Asian Media Ecologies (CANAME)","kr_role":"공동연구원 (연구책임자: Hilde De Weerdt)","en_funder":"Leiden University","en_title":"K-MARKUS - Critical Approaches to New Asian Media Ecologies (CANAME)","en_role":"Co-Researcher (PI: Hilde De Weerdt)"},{"period":"2016.09.\~2017.08.","ongoing":false,"role":"co","budget":"343,200,000","kr_funder":"한국학중앙연구원 (AKSR2016-KS02)","kr_title":"한국 기록유산의 디지털 스토리텔링 자원 개발","kr_role":"연구보조원 (연구책임자: 김현)","en_funder":"The Academy of Korean Studies (AKSR2016-KS02)","en_title":"Development of Digital Storytelling Resources for Korean Documentary Heritage","en_role":"Research Assistant (PI: Kim Hyun)"},{"period":"2015.06.\~2017.08.","ongoing":false,"role":"co","budget":"694,000,000","kr_funder":"한국학진흥사업단 (14·15토대집성)","kr_title":"근현대 구(舊)황실 관련 자료 조사 집성","kr_role":"연구보조원 (연구책임자: 최진덕, 한형조)","en_funder":"Korean Studies Promotion Service","en_title":"Investigation and Compilation of Materials Related to the Former Imperial Family in the Modern and Contemporary Periods","en_role":"Research Assistant (PI: Choi Jin-deok, Han Hyung-jo)"},{"period":"2014.05.\~2014.12.","ongoing":false,"role":"co","budget":"90,000,000","kr_funder":"문화재청","kr_title":"문화재 안내표기(설명문 등) 및 체계 개선방안 연구용역","kr_role":"연구보조원 (연구책임자: 김지명)","en_funder":"Cultural Heritage Administration","en_title":"Research Service on Cultural Heritage Information Signs (Explanatory Texts, etc.) and System Improvement Plan","en_role":"Research Assistant (PI: Kim Ji-myung)"},{"period":"2014.05.\~2014.12.","ongoing":false,"role":"co","budget":"11,800,000","kr_funder":"한국학중앙연구원 (AKSR2014-I53)","kr_title":"2014년 인문정보학 연구지형도","kr_role":"연구보조원 (연구책임자: 양창진)","en_funder":"The Academy of Korean Studies (AKSR2014-I53)","en_title":"2014 Research Landscape of Digital Humanities","en_role":"Research Assistant (PI: Yang Chang-jin)"},{"period":"2014.05.\~2014.11.","ongoing":false,"role":"co","budget":"","kr_funder":"한국연구재단 (정책연구-2014-A431-0017)","kr_title":"디지털시대 인문학 성과의 산업화 방안 연구","kr_role":"연구보조원 (연구책임자: 김기덕)","en_funder":"National Research Foundation of Korea (2014-A431-0017)","en_title":"Research on the Industrialization of Humanities Achievements in the Digital Age","en_role":"Research Assistant (PI: Kim Ki-deok)"},{"period":"2013.11.\~2017.11.","ongoing":false,"role":"co","budget":"1,142,061,700","kr_funder":"한국학진흥사업단 (14·15실록)","kr_title":"조선왕조실록 전문사전 편찬","kr_role":"전임연구원+연구보조원 (연구책임자: 원창애)","en_funder":"Korean Studies Promotion Service","en_title":"Compilation of a Specialized Dictionary of the Annals of the Joseon Dynasty","en_role":"Full-time Researcher & Research Assistant (PI: Won Chang-ae)"},{"period":"2013.05.\~2013.12.","ongoing":false,"role":"co","budget":"14,500,000","kr_funder":"한국학중앙연구원 (AKSR2013-I35)","kr_title":"2013년 지리학 연구지형도","kr_role":"연구보조원 (연구책임자: 손용택)","en_funder":"The Academy of Korean Studies (AKSR2013-I35)","en_title":"2013 Research Landscape of Geography","en_role":"Research Assistant (PI: Son Yong-taek)"}\],"patents":\[{"date":"2021.03.04.","number":"10-2021-0028752","country_kr":"대한민국","country_en":"Republic of Korea","kr":"딥러닝을 이용한 도덕 판단 유형 예측시스템 및 방법","en":"Prediction system for type of moral judgment using deep learning and method thereof"}\],"reports":\[{"year":"2023","kr":"국립문화재연구원+한국학중앙연구원: 김바로, 한국고고학사전 정보 메타데이터 설계 연구","en":"National Research Institute of Cultural Heritage + AKS: Kim Baro, Research on Information Metadata Design of the Korean Archaeological Dictionary"},{"year":"2022","kr":"육군본부+건양대학교: 최명진 외, 군사용 인공지능의 안전성 확보를 위한 단계별 윤리적 평가 및 검증요소(기준) 마련 연구","en":"ROK Army Headquarters + Konyang University: Choi Myung-jin et al., Research on Step-by-Step Ethical Evaluation and Verification Elements (Standards) for Ensuring the Safety of Military AI"},{"year":"2021","kr":"경제·인문사회연구회+한밭대학교: 김효은 외, 감염병 시대의 도덕판단유형 분석 : 딥러닝을 활용한 텍스트분석","en":"NRC + Hanbat National University: Kim Hyo-eun et al., Analysis of Moral Judgment Types in the Era of Infectious Diseases: Text Analysis Using Deep Learning"},{"year":"2020","kr":"경제·인문사회연구회+UNIST: 이주영 외, 디지털-빅데이터의 시대 인문학의 새로운 역할에 대한 고찰","en":"NRC + UNIST: Lee Ju-young et al., A Study on the New Role of Humanities in the Age of Digital Big Data"},{"year":"2014","kr":"문화재청: 김지명 외, 문화재 안내표기(설명문 등) 및 체계 개선 방안 연구","en":"Cultural Heritage Administration: Kim Ji-myung et al., Research on Cultural Heritage Information Signs and System Improvement Plan"}\],"awards":\[{"date":"2025.05.","kr":"대한중국학회 우수논문상","en":"Best Paper Award, The Korean Society for Chinese Studies"},{"date":"2009.12.","kr":"2009 베스트 블로그 100 / PC사랑","en":"Best Blog 100 / PC Sarang"},{"date":"2008.12.","kr":"파워블로거 50인 / 월간 말","en":"Top 50 Power Bloggers / Monthly Mal"},{"date":"2008.05.","kr":"다음 블로그뉴스 황금펜 / (주)다음소프트","en":"Daum Blog News Golden Pen / Daumsoft Co., Ltd."}\],"other":\[{"date":"2025.03.","kr":"「디지털 기억 정원: AI와 함께 피어나는 기억의 향기」, 『비전성남』","en":"“Digital Memory Garden: The Fragrance of Memory Blooming with AI,” Vision Seongnam"},{"date":"2021.08.","kr":"한중연 사람들 인터뷰, 한국학중앙연구원 온라인소식지","en":"Interview with AKS People, The Academy of Korean Studies Online Newsletter"},{"date":"2020.12.","kr":"「인공지능 시대, 창작과 비평의 미래」, 『작가들』","en":"“The Future of Creation and Criticism in the Age of Artificial Intelligence,” Writers"}\]};
const I18N = {
kr: {
nav: \[
{ id: "sec-overview", label: "개요" },
{ id: "sec-edu-career", label: "학력·경력" },
{ id: "sec-service", label: "학술·원내활동" },
{ id: "sec-books", label: "저서" },
{ id: "sec-papers", label: "논문" },
{ id: "sec-projects", label: "연구과제" },
{ id: "sec-more", label: "특허·보고서·수상" }
\],
kpi: \["학술 저서", "학술 논문", "연구 과제", "진행 중 과제"\],
secResearch: "연구 관심 및 학생 지도 방향",
interestTitle: "연구 관심 분야",
guidanceTitle: "학생 지도 방향",
secEduCareer: "학력 · 학위논문 · 경력",
subEdu: "학력 및 학위논문",
subCareer: "주요 경력",
advisor: "지도교수",
secService: "학술 활동 및 원내 보직",
subAcademic: "학회 및 대외 학술 활동",
subIntramural: "원내 위원회 및 보직",
secBooks: "학술 저서",
solo: "단독 저서",
co: "공저",
secPapers: "학술 논문",
paperSearch: "논문 제목·학술지 검색...",
paperAll: "전체",
secProjects: "연구 과제",
projSearch: "과제명·지원기관 검색...",
projFilters: \[
{ key: "all", label: "전체" },
{ key: "ongoing", label: "진행 중" },
{ key: "pi", label: "연구책임자(PI)" },
{ key: "co", label: "공동·참여" }
\],
ongoing: "진행 중",
piBadge: "연구책임자",
krw: "원",
secMore: "특허 · 보고서 · 수상 · 기타",
subPatents: "특허",
subReports: "연구 보고서",
subAwards: "수상 사항",
subOther: "기타 기고 및 인터뷰",
showAllPapers: (n) => `전체 ${n}편 모두 보기`,
collapsePapers: "최근 12편만 보기",
showAllProjects: (n) => `전체 ${n}건 모두 보기`,
collapseProjects: "최근 10건만 보기",
noResults: "검색 조건에 맞는 항목이 없습니다.",
copied: (label) => `${label} 복사 완료`,
printBtn: "인쇄 / PDF"
},
en: {
nav: \[
{ id: "sec-overview", label: "Overview" },
{ id: "sec-edu-career", label: "Education & Career" },
{ id: "sec-service", label: "Service" },
{ id: "sec-books", label: "Books" },
{ id: "sec-papers", label: "Papers" },
{ id: "sec-projects", label: "Projects" },
{ id: "sec-more", label: "Patents & More" }
\],
kpi: \["Scholarly Books", "Journal Papers", "Research Projects", "Ongoing Projects"\],
secResearch: "Research Interests & Student Advising",
interestTitle: "Research Interests",
guidanceTitle: "Student Advising Philosophy",
secEduCareer: "Education, Dissertations & Career",
subEdu: "Education & Dissertations",
subCareer: "Academic Career",
advisor: "Advisor",
secService: "Academic & Institutional Service",
subAcademic: "Academic Societies & External Committees",
subIntramural: "Intramural Service (AKS)",
secBooks: "Scholarly Books",
solo: "Monograph",
co: "Co-authored",
secPapers: "Scholarly Papers",
paperSearch: "Search papers or journals...",
paperAll: "All",
secProjects: "Research Projects",
projSearch: "Search projects or funders...",
projFilters: \[
{ key: "all", label: "All" },
{ key: "ongoing", label: "Ongoing" },
{ key: "pi", label: "Principal Investigator" },
{ key: "co", label: "Co-Researcher & Other" }
\],
ongoing: "Ongoing",
piBadge: "PI",
krw: "KRW",
secMore: "Patents, Reports, Awards & Media",
subPatents: "Patents",
subReports: "Research Reports",
subAwards: "Awards",
subOther: "Essays & Interviews",
showAllPapers: (n) => `Show All ${n} Papers`,
collapsePapers: "Show Recent 12 Papers",
showAllProjects: (n) => `Show All ${n} Projects`,
collapseProjects: "Show Recent 10 Projects",
noResults: "No matching records found.",
copied: (label) => `Copied ${label}`,
printBtn: "Print / PDF"
}
};
const state = {
lang: "kr",
bioLang: "kr",
paperEra: "all",
paperQuery: "",
papersExpanded: false,
projFilter: "all",
projQuery: "",
projectsExpanded: false
};
try {
const saved = localStorage.getItem("baro_cv_lang");
if (saved === "kr" || saved === "en") {
state.lang = saved;
state.bioLang = saved;
}
} catch (e) {}
const \$ = (id) => document.getElementById(id);
const esc = (s) => String(s || "").replace(/\[&<>"'\]/g, (c) => ({ "&": "&amp;", "<": "&lt;", ">": "&gt;", "&quot;": "&quot;", "'": "&#39;" }\[c\]));
let toastTimer = null;
function showToast(msg) {
const el = \$("cv-toast");
if (!el) return;
el.textContent = msg;
el.classList.add("show");
clearTimeout(toastTimer);
toastTimer = setTimeout(() => el.classList.remove("show"), 2000);
}
function copyText(text, label) {
const t = I18N\[state.lang\];
if (navigator.clipboard && navigator.clipboard.writeText) {
navigator.clipboard.writeText(text).then(() => showToast(t.copied(label))).catch(() => fallbackCopy(text, label));
} else {
fallbackCopy(text, label);
}
}
function fallbackCopy(text, label) {
const ta = document.createElement("textarea");
ta.value = text;
ta.style.position = "fixed";
ta.style.opacity = "0";
document.body.appendChild(ta);
ta.select();
try { document.execCommand("copy"); } catch (e) {}
document.body.removeChild(ta);
showToast(I18N\[state.lang\].copied(label));
}
function renderHero() {
const m = CV_DATA.meta;
const t = I18N\[state.lang\];
\$("cv-name").innerHTML = state.lang === "kr"
? `${esc(m.name_kr)} &lt;span class=&quot;hero-name-sub&quot;&gt;${esc(m.name_en)} · ${esc(m.name_zh)}&lt;/span&gt;`
: `${esc(m.name_en)} &lt;span class=&quot;hero-name-sub&quot;&gt;${esc(m.name_kr)} · ${esc(m.name_zh)}&lt;/span&gt;`;
\$("cv-role").textContent = state.lang === "kr" ? m.role_kr : m.role_en;
\$("cv-affil").textContent = state.lang === "kr" ? m.affiliation_kr : m.affiliation_en;
\$("cv-print-btn").textContent = t.printBtn;
\$("cv-nav-links").innerHTML = t.nav.map((item, idx) =>
`&lt;a href=&quot;#${item.id}&quot; class=&quot;${idx === 0 ? &quot;active&quot; : &quot;&quot;}&quot;&gt;${esc(item.label)}&lt;/a&gt;`
).join("");
\$("cv-ids").innerHTML = `&lt;a class=&quot;id-chip&quot; href=&quot;${esc(m.homepage)}&quot; target=&quot;_blank&quot; rel=&quot;noopener&quot;&gt;&lt;span class=&quot;id-label&quot;&gt;WEB&lt;/span&gt; ddokbaro.com&lt;/a&gt; &lt;button type=&quot;button&quot; class=&quot;id-chip&quot; data-copy=&quot;${esc(m.email)}&quot; data-label=&quot;Email&quot;&gt;&lt;span class=&quot;id-label&quot;&gt;EMAIL&lt;/span&gt; ${esc(m.email)}&lt;/button&gt; &lt;a class=&quot;id-chip&quot; href=&quot;https://orcid.org/${esc(m.orcid)}&quot; target=&quot;_blank&quot; rel=&quot;noopener&quot;&gt;&lt;span class=&quot;id-label&quot;&gt;ORCID&lt;/span&gt; ${esc(m.orcid)}&lt;/a&gt; &lt;button type=&quot;button&quot; class=&quot;id-chip&quot; data-copy=&quot;${esc(m.isni)}&quot; data-label=&quot;ISNI&quot;&gt;&lt;span class=&quot;id-label&quot;&gt;ISNI&lt;/span&gt; ${esc(m.isni)}&lt;/button&gt; &lt;button type=&quot;button&quot; class=&quot;id-chip&quot; data-copy=&quot;${esc(m.iris)}&quot; data-label=&quot;IRIS+KRI&quot;&gt;&lt;span class=&quot;id-label&quot;&gt;IRIS+KRI&lt;/span&gt; ${esc(m.iris)}&lt;/button&gt;`;
\$("cv-bio-text").textContent = m.bio\[state.bioLang\];
document.querySelectorAll("#cv-bio-tabs .bio-tab").forEach((btn) => {
btn.classList.toggle("active", btn.dataset.bio === state.bioLang);
});
const ongoingCount = CV_DATA.projects.filter((p) => p.ongoing).length;
const kpis = \[
{ num: CV_DATA.books.length, label: t.kpi\[0\] },
{ num: CV_DATA.papers.length, label: t.kpi\[1\] },
{ num: CV_DATA.projects.length, label: t.kpi\[2\] },
{ num: ongoingCount, label: t.kpi\[3\] }
\];
$(&quot;cv-kpi-strip&quot;).innerHTML = kpis.map((k) =&gt;
`&lt;div class=&quot;kpi-card&quot;&gt;&lt;div class=&quot;kpi-num&quot;&gt;${k.num}&lt;/div&gt;&lt;div class=&quot;kpi-label&quot;&gt;${esc(k.label)}&lt;/div&gt;&lt;/div&gt;`
).join(&quot;&quot;);
}
function renderResearch() {
const t = I18N[state.lang];
const m = CV_DATA.meta;
$(&quot;t-research&quot;).textContent = t.secResearch;
const kw = m.keywords[state.lang];
const gd = m.guidance[state.lang];
$(&quot;cv-research-body&quot;).innerHTML = `
&lt;div class=&quot;info-panel&quot;&gt;
&lt;h3&gt;${esc(t.interestTitle)}&lt;/h3&gt;
&lt;p style=&quot;margin:0;font-size:0.94rem;&quot;&gt;${esc(m.interests[state.lang])}&lt;/p&gt;
&lt;div class=&quot;pill-list&quot;&gt;${kw.map((k) =&gt; `&lt;span class=&quot;pill&quot;&gt;${esc(k)}&lt;/span&gt;`).join(&quot;&quot;)}&lt;/div&gt;
&lt;/div&gt;
&lt;div class=&quot;info-panel&quot;&gt;
&lt;h3&gt;${esc(t.guidanceTitle)}&lt;/h3&gt;
&lt;ul class=&quot;guidance-list&quot;&gt;${gd.map((g, i) =&gt; `&lt;li&gt;&lt;span class=&quot;guidance-num&quot;&gt;${i + 1}&lt;/span&gt;&lt;span&gt;${esc(g)}</span></li>`).join(&quot;&quot;)}&lt;/ul&gt; &lt;/div&gt; `;
}
function renderEduCareer() {
const t = I18N\[state.lang\];
const isKr = state.lang === "kr";
$(&quot;t-edu-career&quot;).textContent = t.secEduCareer;
const eduHtml = CV_DATA.education.map((e) =&gt; `
&lt;li class=&quot;tl-item&quot;&gt;
&lt;div class=&quot;tl-date&quot;&gt;${esc(e.period)}&lt;/div&gt;
&lt;div class=&quot;tl-body&quot;&gt;
&lt;strong&gt;${esc(isKr ? e.degree_kr : e.degree_en)}&lt;/strong&gt; · ${esc(isKr ? e.inst_kr : e.inst_en)}
&lt;div class=&quot;tl-sub&quot;&gt;${esc(isKr ? e.thesis_kr : e.thesis_en)} (${esc(t.advisor)}: ${esc(isKr ? e.advisor_kr : e.advisor_en)})&lt;/div&gt;
&lt;/div&gt;
&lt;/li&gt;
`).join(&quot;&quot;);
const careerHtml = CV_DATA.career.map((c) =&gt; `
&lt;li class=&quot;tl-item&quot;&gt;
&lt;div class=&quot;tl-date&quot;&gt;${esc(isKr ? c.period : c.period_en)}&lt;/div&gt;
&lt;div class=&quot;tl-body&quot;&gt;
${c.current ? `&lt;span class=&quot;badge badge-now&quot;&gt;${esc(t.ongoing)}</span>`: &quot;&quot;}${esc(isKr ? c.kr : c.en)} &lt;/div&gt; &lt;/li&gt;`).join("");
$(&quot;cv-edu-career-body&quot;).innerHTML = `
&lt;h3 class=&quot;sub-heading&quot;&gt;${esc(t.subEdu)}&lt;/h3&gt;
&lt;ul class=&quot;timeline&quot;&gt;${eduHtml}&lt;/ul&gt;
&lt;h3 class=&quot;sub-heading&quot;&gt;${esc(t.subCareer)}&lt;/h3&gt;
&lt;ul class=&quot;timeline&quot;&gt;${careerHtml}&lt;/ul&gt;
`;
}
function renderService() {
const t = I18N[state.lang];
const isKr = state.lang === &quot;kr&quot;;
$(&quot;t-service&quot;).innerHTML = `${esc(t.secService)} &lt;span class=&quot;sec-count&quot;&gt;${CV_DATA.activities.length + CV_DATA.intramural.length}&lt;/span&gt;`;
const actHtml = CV_DATA.activities.map((a) =&gt; `
&lt;li class=&quot;tl-item&quot;&gt;
&lt;div class=&quot;tl-date&quot;&gt;${esc(a.period)}&lt;/div&gt;
&lt;div class=&quot;tl-body&quot;&gt;${a.current ? `&lt;span class=&quot;badge badge-now&quot;&gt;${esc(t.ongoing)}&lt;/span&gt;` : &quot;&quot;}${esc(isKr ? a.kr : a.en)}&lt;/div&gt;
&lt;/li&gt;
`).join(&quot;&quot;);
const intraHtml = CV_DATA.intramural.map((a) =&gt; `
&lt;li class=&quot;tl-item&quot;&gt;
&lt;div class=&quot;tl-date&quot;&gt;${esc(a.period)}&lt;/div&gt;
&lt;div class=&quot;tl-body&quot;&gt;${a.current ? `&lt;span class=&quot;badge badge-now&quot;&gt;${esc(t.ongoing)}</span>`: &quot;&quot;}${esc(isKr ? a.kr : a.en)}&lt;/div&gt; &lt;/li&gt;`).join("");
\$("cv-service-body").innerHTML = `&lt;h3 class=&quot;sub-heading&quot;&gt;${esc(t.subAcademic)}&lt;/h3&gt; &lt;ul class=&quot;timeline&quot;&gt;${actHtml}&lt;/ul&gt; &lt;h3 class=&quot;sub-heading&quot;&gt;${esc(t.subIntramural)}&lt;/h3&gt; &lt;ul class=&quot;timeline&quot;&gt;${intraHtml}&lt;/ul&gt;`;
}
function renderBooks() {
const t = I18N\[state.lang\];
const isKr = state.lang === "kr";
\$("t-books").innerHTML = `${esc(t.secBooks)} &lt;span class=&quot;sec-count&quot;&gt;${CV_DATA.books.length}&lt;/span&gt;`;
\$("cv-books-body").innerHTML = CV_DATA.books.map((b) => `&lt;article class=&quot;book-card&quot;&gt; &lt;div&gt; &lt;span class=&quot;badge ${b.type === &quot;solo&quot; ? &quot;badge-solo&quot; : &quot;badge-co&quot;}&quot;&gt;${esc(b.type === &quot;solo&quot; ? t.solo : t.co)}&lt;/span&gt; &lt;div class=&quot;book-title&quot; style=&quot;margin-top:6px;&quot;&gt;${esc(isKr ? b.kr_title : b.en_title)}&lt;/div&gt; &lt;/div&gt; &lt;div class=&quot;book-meta&quot;&gt; &lt;span&gt;${esc(isKr ? b.kr_pub : b.en_pub)}&lt;/span&gt; &lt;span&gt;${esc(b.date)}&lt;/span&gt; &lt;/div&gt; &lt;/article&gt;`).join("");
}
function renderPapers() {
const t = I18N\[state.lang\];
const isKr = state.lang === "kr";
\$("cv-paper-search").placeholder = t.paperSearch;
const eras = \[
{ key: "all", label: t.paperAll },
{ key: "2022+", label: "2022–2025" },
{ key: "2019-2021", label: "2019–2021" },
{ key: "2014-2018", label: "2014–2018" }
\];
\$("cv-paper-years").innerHTML = eras.map((er) =>
`&lt;button type=&quot;button&quot; class=&quot;filter-btn ${state.paperEra === er.key ? &quot;active&quot; : &quot;&quot;}&quot; data-era=&quot;${er.key}&quot;&gt;${esc(er.label)}&lt;/button&gt;`
).join("");
const q = state.paperQuery.trim().toLowerCase();
const filtered = CV_DATA.papers.filter((p) => {
const y = parseInt(p.date.slice(0, 4), 10);
if (state.paperEra === "2022+" && y < 2022) return false;
if (state.paperEra === "2019-2021" && (y < 2019 || y > 2021)) return false;
if (state.paperEra === "2014-2018" && y > 2018) return false;
if (!q) return true;
const hay = `${p.date} ${p.kr_title} ${p.kr_journal} ${p.en_title} ${p.en_journal}`.toLowerCase();
return hay.includes(q);
});
\$("t-papers").innerHTML = `${esc(t.secPapers)} &lt;span class=&quot;sec-count&quot;&gt;${filtered.length} / ${CV_DATA.papers.length}&lt;/span&gt;`;
const limit = (q || state.paperEra !== "all" || state.papersExpanded) ? filtered.length : 12;
const shown = filtered.slice(0, limit);
\$("cv-papers-body").innerHTML = shown.length ? shown.map((p) => `&lt;div class=&quot;pub-item&quot;&gt; &lt;div class=&quot;pub-date&quot;&gt;${esc(p.date)}&lt;/div&gt; &lt;div&gt; &lt;div class=&quot;pub-title&quot;&gt;${esc(isKr ? p.kr_title : p.en_title)}&lt;/div&gt; &lt;div class=&quot;pub-journal&quot;&gt;${esc(isKr ? p.kr_journal : p.en_journal)}&lt;/div&gt; &lt;/div&gt; &lt;/div&gt;`).join("") : `&lt;div class=&quot;empty-state&quot;&gt;${esc(t.noResults)}&lt;/div&gt;`;
const moreBtn = \$("cv-papers-more");
if (!q && state.paperEra === "all" && filtered.length > 12) {
moreBtn.style.display = "block";
moreBtn.textContent = state.papersExpanded ? t.collapsePapers : t.showAllPapers(filtered.length);
} else {
moreBtn.style.display = "none";
}
}
function renderProjects() {
const t = I18N\[state.lang\];
const isKr = state.lang === "kr";
\$("cv-proj-search").placeholder = t.projSearch;
$(&quot;cv-proj-filters&quot;).innerHTML = t.projFilters.map((f) =&gt;
`&lt;button type=&quot;button&quot; class=&quot;filter-btn ${state.projFilter === f.key ? &quot;active&quot; : &quot;&quot;}&quot; data-pfilter=&quot;${f.key}&quot;&gt;${esc(f.label)}&lt;/button&gt;`
).join(&quot;&quot;);
const q = state.projQuery.trim().toLowerCase();
const filtered = CV_DATA.projects.filter((p) =&gt; {
if (state.projFilter === &quot;ongoing&quot; &amp;&amp; !p.ongoing) return false;
if (state.projFilter === &quot;pi&quot; &amp;&amp; p.role !== &quot;pi&quot;) return false;
if (state.projFilter === &quot;co&quot; &amp;&amp; p.role === &quot;pi&quot;) return false;
if (!q) return true;
const hay = `${p.period} ${p.kr_funder} ${p.kr_title} ${p.kr_role} ${p.en_funder} ${p.en_title} ${p.en_role}`.toLowerCase();
return hay.includes(q);
});
$(&quot;t-projects&quot;).innerHTML = `${esc(t.secProjects)} &lt;span class=&quot;sec-count&quot;&gt;${filtered.length} / ${CV_DATA.projects.length}&lt;/span&gt;`;
const limit = (q || state.projFilter !== &quot;all&quot; || state.projectsExpanded) ? filtered.length : 10;
const shown = filtered.slice(0, limit);
$(&quot;cv-projects-body&quot;).innerHTML = shown.length ? shown.map((p) =&gt; `
&lt;article class=&quot;proj-card&quot;&gt;
&lt;div class=&quot;proj-top&quot;&gt;
&lt;div&gt;
${p.ongoing ? `&lt;span class=&quot;badge badge-now&quot;&gt;${esc(t.ongoing)}&lt;/span&gt;` : &quot;&quot;}
${p.role === &quot;pi&quot; ? `&lt;span class=&quot;badge badge-pi&quot;&gt;${esc(t.piBadge)}&lt;/span&gt;` : &quot;&quot;}
&lt;span class=&quot;proj-period&quot;&gt;${esc(isKr ? p.period : (p.period_en || p.period))}&lt;/span&gt;
&lt;/div&gt;
${p.budget ? `&lt;span class=&quot;proj-budget&quot;&gt;${esc(p.budget)} \${esc(t.krw)}</span>`: &quot;&quot;} &lt;/div&gt; &lt;div class=&quot;proj-title&quot;&gt;${esc(isKr ? p.kr_title : p.en_title)}&lt;/div&gt; &lt;div class=&quot;proj-meta&quot;&gt;${esc(isKr ? p.kr_funder : p.en_funder)} · ${esc(isKr ? p.kr_role : p.en_role)}&lt;/div&gt; &lt;/article&gt;`).join("") : `&lt;div class=&quot;empty-state&quot;&gt;${esc(t.noResults)}&lt;/div&gt;`;
const moreBtn = \$("cv-projects-more");
if (!q && state.projFilter === "all" && filtered.length > 10) {
moreBtn.style.display = "block";
moreBtn.textContent = state.projectsExpanded ? t.collapseProjects : t.showAllProjects(filtered.length);
} else {
moreBtn.style.display = "none";
}
}
function renderMore() {
const t = I18N\[state.lang\];
const isKr = state.lang === "kr";
\$("t-more").textContent = t.secMore;
const patHtml = CV_DATA.patents.map((p) => `&lt;li class=&quot;tl-item&quot;&gt; &lt;div class=&quot;tl-date&quot;&gt;${esc(p.date)}&lt;/div&gt; &lt;div class=&quot;tl-body&quot;&gt;&lt;strong&gt;${esc(isKr ? p.kr : p.en)}&lt;/strong&gt;&lt;div class=&quot;tl-sub&quot;&gt;${esc(p.number)} · ${esc(isKr ? p.country_kr : p.country_en)}&lt;/div&gt;&lt;/div&gt; &lt;/li&gt;`).join("");
const repHtml = CV_DATA.reports.map((r) => `&lt;li class=&quot;tl-item&quot;&gt;&lt;div class=&quot;tl-date&quot;&gt;${esc(r.year)}&lt;/div&gt;&lt;div class=&quot;tl-body&quot;&gt;${esc(isKr ? r.kr : r.en)}&lt;/div&gt;&lt;/li&gt;`).join("");
const awHtml = CV_DATA.awards.map((a) => `&lt;li class=&quot;tl-item&quot;&gt;&lt;div class=&quot;tl-date&quot;&gt;${esc(a.date)}&lt;/div&gt;&lt;div class=&quot;tl-body&quot;&gt;${esc(isKr ? a.kr : a.en)}&lt;/div&gt;&lt;/li&gt;`).join("");
const othHtml = CV_DATA.other.map((o) => `&lt;li class=&quot;tl-item&quot;&gt;&lt;div class=&quot;tl-date&quot;&gt;${esc(o.date)}&lt;/div&gt;&lt;div class=&quot;tl-body&quot;&gt;${esc(isKr ? o.kr : o.en)}&lt;/div&gt;&lt;/li&gt;`).join("");
\$("cv-more-body").innerHTML = `&lt;h3 class=&quot;sub-heading&quot;&gt;${esc(t.subPatents)}&lt;/h3&gt;&lt;ul class=&quot;timeline&quot;&gt;${patHtml}&lt;/ul&gt; &lt;h3 class=&quot;sub-heading&quot;&gt;${esc(t.subReports)}&lt;/h3&gt;&lt;ul class=&quot;timeline&quot;&gt;${repHtml}&lt;/ul&gt; &lt;h3 class=&quot;sub-heading&quot;&gt;${esc(t.subAwards)}&lt;/h3&gt;&lt;ul class=&quot;timeline&quot;&gt;${awHtml}&lt;/ul&gt; &lt;h3 class=&quot;sub-heading&quot;&gt;${esc(t.subOther)}&lt;/h3&gt;&lt;ul class=&quot;timeline&quot;&gt;${othHtml}&lt;/ul&gt;`;
}
function renderAll() {
document.querySelectorAll(".lang-btn").forEach((btn) => {
btn.classList.toggle("active", btn.dataset.lang === state.lang);
});
renderHero();
renderResearch();
renderEduCareer();
renderService();
renderBooks();
renderPapers();
renderProjects();
renderMore();
}
document.getElementById("baro-cv-root").addEventListener("click", (e) => {
const langBtn = e.target.closest(".lang-btn");
if (langBtn) {
state.lang = langBtn.dataset.lang;
state.bioLang = state.lang;
try { localStorage.setItem("baro_cv_lang", state.lang); } catch (err) {}
renderAll();
return;
}
const bioTab = e.target.closest(".bio-tab");
if (bioTab) {
state.bioLang = bioTab.dataset.bio;
\$("cv-bio-text").textContent = CV_DATA.meta.bio\[state.bioLang\];
document.querySelectorAll("#cv-bio-tabs .bio-tab").forEach((b) => b.classList.toggle("active", b.dataset.bio === state.bioLang));
return;
}
const copyBtn = e.target.closest("\[data-copy\]");
if (copyBtn) {
copyText(copyBtn.dataset.copy, copyBtn.dataset.label);
return;
}
const eraBtn = e.target.closest("\[data-era\]");
if (eraBtn) {
state.paperEra = eraBtn.dataset.era;
renderPapers();
return;
}
const pfBtn = e.target.closest("\[data-pfilter\]");
if (pfBtn) {
state.projFilter = pfBtn.dataset.pfilter;
renderProjects();
return;
}
if (e.target.id === "cv-papers-more") {
state.papersExpanded = !state.papersExpanded;
renderPapers();
return;
}
if (e.target.id === "cv-projects-more") {
state.projectsExpanded = !state.projectsExpanded;
renderProjects();
return;
}
if (e.target.id === "cv-print-btn") {
const prevP = state.papersExpanded, prevPr = state.projectsExpanded;
state.papersExpanded = true;
state.projectsExpanded = true;
renderPapers();
renderProjects();
window.print();
setTimeout(() => { state.papersExpanded = prevP; state.projectsExpanded = prevPr; renderPapers(); renderProjects(); }, 300);
return;
}
const navLink = e.target.closest("#cv-nav-links a");
if (navLink) {
document.querySelectorAll("#cv-nav-links a").forEach((a) => a.classList.remove("active"));
navLink.classList.add("active");
}
});
\$("cv-paper-search").addEventListener("input", (e) => {
state.paperQuery = e.target.value;
renderPapers();
});
\$("cv-proj-search").addEventListener("input", (e) => {
state.projQuery = e.target.value;
renderProjects();
});
renderAll();
})();
</script>
