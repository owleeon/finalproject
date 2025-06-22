# finalproject
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>자기소개 프로젝트</title>
  <link rel="stylesheet" href="index.css">
  <link href="https://fonts.googleapis.com/css2?family=Alfa+Slab+One&display=swap" rel="stylesheet">
</head>
<body>
  <nav>
    <div class="nav-list">
      <div class="nav-left">
        <h3>저를 소개합니다!</h3>
      </div>
      <div class="nav-right">
        <a href="#About-intro" class="list-link">About</a>
        <a href="#section4" class="list-link">Mindset</a>
        <a href="https://www.instagram.com/jwleeonw2/" class="list-link">SNS</a>
        <a href="https://codespaces.new/owleeon/finalproject" class="list-link btn-code">Code</a>
      </div>
    </div><hr>
  </nav>

  <div class="section1">
    <div class="carousel-container">
      <div class="carousel-track">
        <div class="carousel-slide"><img src="../zproject/image/main.jpg" alt="1번 이미지" /></div>
        <div class="carousel-slide"><img src="../zproject/image/main2.jpg" alt="2번 이미지" /></div>
        <div class="carousel-slide"><img src="../zproject/image/main3.jpg" alt="3번 이미지" /></div>
      </div>
    </div>
    
    <div class="intro-text">
        <h1>저의 이름은 이정원입니다 !</h1>
        <p>끊임없이 배우고, 도전하는 삶. 그런 삶을 살고 싶습니다 !</p>
        <p>경기도 고양시 출생, 나이 21</p>
    </div>
  </div>

  <div class="section2">
    <h1 class="About-intro" id="About-intro">About Me!</h1>
  </div>

  

  <div class="card-container">
  <div class="game-card" onclick="openModal('game1')">
    <img src="../zproject/image/movie_image.jpg" alt="취미">
    <p>취미</p>
  </div>
  <div class="game-card" onclick="openModal('game2')">
    <img src="../zproject/image/life.png" alt="갤러리">
    <p>갤러리</p>
  </div>
  <div class="game-card" onclick="openModal('game3')">
    <img src="../zproject/image/music.jpg" alt="음악">
    <p>음악</p>
  </div>
  <div class="game-card" onclick="openModal('game4')">
    <img src="../zproject/image/baseball.jpg" alt="스포츠">
    <p>스포츠</p>
  </div>
</div>

<!-- 모달들 -->
<div id="modal-game1" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('game1')">&times;</span>
    <h2>제 취미는 영화 감상입니다!</h2>
    <p>OTT를 통한 영화시청도 좋아하지만, 극장 관람을 정말 좋아합니다.</p>
    <p>인생영화:</p>
    <p><img src="../zproject/image/movie1.jpg" style="width: 200px; float: left; margin-right: 15px;">
    포레스트 검프는 우리의 삶에 대한 교훈을 주는 영화입니다!<br>
    주인공 검프는 부족한 지능을 갖고 있는 사람이지만<br>
    그가 달려야하는 상황에 놓였을 때는 그 누구보다 열정적으로<br>
    뛰는 모습을 보여줍니다.<br>
    감독이 검프의 삶을 통해 "지금 이 순간을 사는 것"을 강조하며<br>
    큰 교훈을 주는 영화입니다.<br>
    이 영화는 제 가치관에도 큰 영향을 줄 정도로 감명 받았던<br>
    영화이기 때문에 여러분에게도 꼭 추천을 드리고 싶은 영화입니다.
    </p>
  </div>
</div>

<div id="modal-game2" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('game2')">&times;</span>
    <h2>갤러리</h2>
    <p>제 어릴적 모습과 지금의 모습입니다ㅎ</p>
    <p>많이 못생겨졌네요...</p>
    <img src="../zproject/image/life3.jpg" style="width: 250px;">
    <img src="../zproject/image/life.png" style="width: 250px;">
    <img src="../zproject/image/life2.PNG" style="width: 200px;"><br>
    <img src="../zproject/image/main.jpg" style="width: 250px;">
    <img src="../zproject/image/main2.jpg" style="width: 250px;">
    <img src="../zproject/image/main3.jpg" style="width: 250px;">
  </div>
</div>

<div id="modal-game3" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('game3')">&times;</span>
    <h2>음악</h2>
    <p>저는 음악 감상을 정말 좋아합니다.</p>
    <p><img src="../zproject/image/music2.jpg" style="width: 200px; float: left; margin-right: 15px;">
    주로 락 장르의 음악을 선호하고<br>
    LP를 모으는 취미 또한 있습니다.<br>
    제가 생각하는 최고의 명반 하나 추천 드리자면<br>
    단연코 BLUR의 Parklife를 추천 드릴 것 같습니다!
    </p><br><br>
    <p>또한 콘서트 다니는 걸 정말 좋아합니다! 제가 다녀온 콘서트들입니다</p>
    <img src="../zproject/image/music3.jpg" style="width: 200px;">
    <img src="../zproject/image/music4.jpg" style="width: 200px;">
    <img src="../zproject/image/music5.jpg" style="width: 250px;">
  </div>
</div>

<div id="modal-game4" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('game4')">&times;</span>
    <h2>스포츠</h2>
    <p>저는 다양한 스포츠를 좋아하지만, 그 중에서도 야구를 정말 좋아합니다</p>
    <img src="../zproject/image/baseball1.jpg" style="width: 200px;">
    <img src="../zproject/image/baseball2.jpg" style="width: 200px;">
    <img src="../zproject/image/baseball3.jpg" style="width: 200px;">
  </div>
</div>


<div class="section3">
    <!--섹션2 여백용 -->
</div>

<div class="section4" id="section4">
    <div class="Last-text">
        <h1>가치관</h1>
        <h2>FORTIS FORTUNA ADIUVAT</h2> 
        <p>영화 존윅의 명장면 속 명언이자, 저의 좌우명입니다. </p>
        <p>행운은 용감한 자를 돕는다.</p>
        <p>실패를 두려워하지 않는 마음으로, 주저하기보단 실패를</p>
        <p>그리고 그 실패를 발판삼아 어제보다 더 나은 사람이 되고 싶습니다.</p>
    </div>
</div>




<script src="index.js"></script>
</body>
</html>






html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  padding: 0;
}

nav {
  width: 100%;
}

.nav-list {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 50px;
  list-style: none;
  color: #7392eb;
  background-color: white;
  padding: 0 40px;
}

.nav-right {
  display: flex;
  gap: 50px;
}

hr {
  border: none;
  height: 3px;
  background-color: #7392eb;
  margin: 0 auto;
}

.section1 {
  padding: 100px;
  background-color: #dfe2f7;
  display: flex;
  justify-content: center;
  align-items: center;

}

/* 인트로 */
.intro-text {
  font-family: 'Alfa Slab One', 'Nanum Gothic', 'Malgun Gothic', sans-serif; 
  color:  #7392eb;                          
  font-size: 18px;                         
  line-height: 1.5;                        
}

.intro-text h1 {
  font-size: 36px;
  font-weight: bold;
  color: #2a3d66;
  margin-bottom: 20px;
}

.intro-text p {
  font-size: 16px;
  color: #555555;
}

/* 이미지 슬라이더 */
.carousel-container {
  width: 300px;
  height: 400px;
  overflow: hidden;
  border-radius: 15px;
  box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);

  position: relative;  
  left: -100px;         
}

.carousel-track {
  display: flex;
  transition: transform 0.5s ease-in-out;
}

.carousel-slide {
  min-width: 100%;
  height: 100%;
}

.carousel-slide img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}


/* 섹션2 ABOUT */
.section2 {
  padding: 50px 100px;
  background-color: white;
  padding-top: 1px;
  text-align: center;
}

.About-intro{
  text-align: center;
  margin-top: 80px;  
}




/* 섹션3 카드 */
.card-container {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
  margin-top: 50px;
}

.game-card {
  width: 180px;
  background-color: white;
  border-radius: 15px;
  text-align: center;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  cursor: pointer;
  transition: transform 0.3s;
}

.game-card:hover {
  transform: scale(1.05);
}

.game-card img {
  width: 100%;
  height: 150px;
  border-radius: 15px 15px 0 0;
  object-fit: cover;
}

.game-card p {
  margin: 10px 0;
  font-weight: bold;
}


/* 모달 */
.modal {
  display: none;
  position: fixed;
  z-index: 999;
  left: 0; top: 0;
  width: 100%; height: 100%;
  background-color: rgba(0, 0, 0, 0.6);
}

.modal-content {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  background-color: white;
  padding: 20px;
  width: 800px;
  border-radius: 15px;
}

.close {
  position: absolute;
  top: 10px; 
  right: 15px;
  font-size: 24px;
  cursor: pointer;
}


/* 공백 */
.section3{
  padding: 100px 100px;
  background-color: white;
}


/* 가치관 섹션4 */
.section4{
  padding: 300px 100px;
  background-image:url("../zproject/image/LastImage.jpg");
  background-repeat: no-repeat;       
  background-size: cover;            
  background-position: center center; 
}

.Last-text {
  font-family: 'Alfa Slab One', 'Nanum Gothic', 'Malgun Gothic', sans-serif; 
  font-size: 18px;                         
  color: white;
  line-height: 1.5;                        
  text-align: center;
}






const track = document.querySelector('.carousel-track');
const slides = document.querySelectorAll('.carousel-slide');
let currentIndex = 0;
const totalSlides = slides.length;

function moveToSlide(index) {
  track.style.transform = `translateX(-${index * 100}%)`;
}

function autoSlide() {
  currentIndex = (currentIndex + 1) % totalSlides;
  moveToSlide(currentIndex);
}

setInterval(autoSlide, 3000); 






  function openModal(id) {
    document.getElementById("modal-" + id).style.display = "block";
  }

  function closeModal(id) {
    document.getElementById("modal-" + id).style.display = "none";
  }

  
  window.onclick = function(event) {
    const modals = document.querySelectorAll(".modal");
    modals.forEach(modal => {
      if (event.target === modal) {
        modal.style.display = "none";
      }
    });
  }


