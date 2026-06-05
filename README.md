<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>이동영 | Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
}

body{
    font-family:'Segoe UI', sans-serif;
    background:#0f172a;
    color:#f8fafc;
}

header{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:20px;
    background:linear-gradient(135deg,#0f172a,#1e293b);
}

.hero h1{
    font-size:4rem;
    margin-bottom:10px;
}

.hero span{
    color:#38bdf8;
}

.hero p{
    color:#94a3b8;
    font-size:1.2rem;
    margin-bottom:25px;
}

.btn{
    display:inline-block;
    padding:12px 25px;
    background:#38bdf8;
    color:#0f172a;
    text-decoration:none;
    border-radius:8px;
    font-weight:bold;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-3px);
}

section{
    max-width:1100px;
    margin:auto;
    padding:80px 20px;
}

.section-title{
    text-align:center;
    font-size:2rem;
    margin-bottom:40px;
    color:#38bdf8;
}

.card{
    background:#1e293b;
    padding:25px;
    border-radius:15px;
    margin-bottom:20px;
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
}

.skills{
    display:flex;
    flex-wrap:wrap;
    gap:10px;
}

.skill{
    background:#334155;
    padding:10px 15px;
    border-radius:999px;
}

.project{
    border-left:4px solid #38bdf8;
}

footer{
    text-align:center;
    padding:30px;
    color:#94a3b8;
}

@media(max-width:768px){

.hero h1{
    font-size:2.5rem;
}

.section-title{
    font-size:1.7rem;
}

}
</style>
</head>

<body>

<header>
    <div class="hero">
        <h1>안녕하세요.<br>프론트 개발 수업을 듣는 <span>이동영</span>입니다.</h1>
        <p> 프론트엔드 개발 이스트 부스캠프 HTML< CSS를 활용한 포토폴리오를 작성 하였습니다. </p>
        <a href="#about" class="btn">포트폴리오 보기</a>
    </div>
</header>

<section id="about">
    <h2 class="section-title">👋 자기소개</h2>

    <div class="card">
        <p>
            안녕하세요. 이동영입니다.
            디자인이라는 관점에 관심이 없다가 나중에 디자인에 관심을 두게되면서 활실치는 않지만, 
            프론트 개발이 나에게 도움이 될까하여 배우게 되었습니다.
        </p>
    </div>
</section>

<section>
    <h2 class="section-title">🎯 프로젝트 목표</h2>

    <div class="card">
        <p>
            웹 개발 기술을 학습하고 실제 서비스를 배포하는 경험을 얻기 위해
            개인 포트폴리오 웹사이트를 제작하였습니다.
            HTML, CSS, JavaScript, React, Ai 등을 배워가는 과정입니다.
        </p>
    </div>
</section>

<section>
    <h2 class="section-title"> <img width="498" height="498" alt="SadCryGIF" src="https://github.com/user-attachments/assets/81bd3a1f-32ba-406a-92da-3397cd2cfdd0" />
사용 기술</h2>

    <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Git</div>
        <div class="skill">GitHub</div>
        <div class="skill">React</div>
    </div>
</section>

<section>
    <h2 class="section-title"><img width="498" height="280" alt="ProjectCluelessGIF" src="https://github.com/user-attachments/assets/cbd082eb-885a-414c-94ec-514a3e6980d8" />
프로젝트</h2>

    <div class="card project">
        <h3>개인 포트폴리오 웹사이트</h3>
        <br>

        <p><strong>제작 기간</strong><br>2026.05 ~ 2026.06</p>
        <br>

        <p><strong>배포 주소</strong><br>
        https://meykeongi909-rgb.github.io/meykeongi909-rgb/
        </p>

        <br>

        <p><strong>프로젝트 구조</strong></p>
        <ul>
            <li>index.html</li>
            <li>style.css</li>
            <li>script.js</li>
            <li>assets</li>
        </ul>

        <br>

        <p><strong>주요 기능</strong></p>
        <ul>
            <li>자기소개</li>
            <li>기술 스택 소개</li>
            <li>프로젝트 소개</li>
            <li>반응형 웹 지원</li>
            <li>GitHub 연결</li>
        </ul>
    </div>
</section>

<section>
    <h2 class="section-title">😁
 반응형 웹</h2>

    <div class="card">
        <p>
            모바일, 태블릿, PC 환경에 맞춰 화면이 자동으로 최적화되도록
            반응형 웹 디자인을 적용했습니다.
        </p>
    </div>
</section>

<section>
    <h2 class="section-title">☆*: .｡. o(≧▽≦)o .｡.:*☆ 배운 점</h2>

    <div class="card">
        <p>
            Git과 GitHub를 활용한 버전 관리,
            GitHub Pages를 통한 배포 과정,
            그리고 반응형 웹 제작 경험을 쌓을 수 있었습니다.
        </p>
    </div>
</section>

<section>
    <h2 class="section-title">🔧 트러블 슈팅</h2>

    <div class="card">
        <h3>GitHub Pages 배포 오류</h3>
        <br>
        <p>
            사이트가 열리지 않는 문제가 발생했습니다.
            확인 결과 Pages 브랜치가 설정되지 않았고,
            main 브랜치를 지정하여 해결했습니다.
        </p>
    </div>

    <div class="card">
        <h3>모바일 화면 크기조절</h3>
        <br>
        <p>
            PC 화면에서 윗줄에 나와 있는 내용이 모바일로는 아랫줄로 
            가는 현상이 발생하여 많이 골머리를 굴렸습니다. 그런데
            content의 방향의 위치를 바꾸니 그런 현상이 살아졌습니다.
        </p>
    </div>
</section>

<footer>
    <p>© 2026 이동영 Portfolio</p>
</footer>

</body>
</html>
