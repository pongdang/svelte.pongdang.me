<script>
  // your script goes here
</script>

<nav>
  <div class="wrapper">
    <h2 class="title">구경해보세용</h2>

    <ul class="menu-container">
      <li class="menu-box">
        <a href="/pongstudy/">
          공부해라
          <img class="joy" src="/images/joy.png" alt="조이" />
        </a>
      </li>
      <li class="menu-box">
        <a href="/pongwork/">
          무언가를 만들어 보았습니다
          <img class="disgust" src="/images/disgust.png" alt="까칠이" />
        </a>
      </li>
      <li class="menu-box">
        <a href="/pongtoday/">
          오늘의 날씨
          <img class="anger" src="/images/anger.png" alt="버럭이" />
        </a>
      </li>
      <li class="menu-box">
        <a href="/pongbook/"> 책 좀 읽어라 </a>
      </li>
      <li class="menu-box">
        <a href="/studylog/"> 준비중 </a>
      </li>
    </ul>
  </div>
</nav>

<section>
  <div class="wrapper">
    <h2 class="title">여기는 뭘하면 좋을까 🤔</h2>

    <div class="contents-container">
      <div class="contents-box">
        <h3 class="contents-title">너무 귀엽고 어지러운 나의 전 블로그</h3>
        <a href="/asdf.html"> 🌟 보러가기 🌟 </a>
      </div>

      <div class="contents-box">
        <h3 class="contents-title">Math.random()을 공부했슴니다...</h3>
        <a href="/pongwork/08/12.html"> 🌟 보러가기 🌟 </a>
      </div>

      <div class="contents-box">
        <h3 class="contents-title">방향키 이벤트,,,</h3>
        <a class="workItem" href="/pongwork/08/15"> 🌟 보러가기 🌟 </a>
      </div>
    </div>
  </div>
</section>

<style>
  .menu-container {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    text-align: center;
  }

  .menu-box {
    height: 300px;
    width: 300px;
    margin-bottom: 30px;
  }

  .menu-box a {
    height: 100%;
    width: 100%;
    font-weight: bold;
    background-color: #f1d7ff;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
    position: relative;
    overflow: hidden;
  }

  .menu-box a:hover {
    background-color: #e9e9e9;
  }

  /* 튀어나오는 친구들 */

  .menu-box a img {
    position: absolute;
    width: 200px;
    transition: transform 0.5s;
  }

  .menu-box a img.joy {
    top: -200px;
    transform: translateY(0);
  }

  .menu-box a img.anger {
    bottom: 0;
    transform: translateY(100%);
  }

  .menu-box a img.disgust {
    right: 0;
    bottom: 0;
    transform: translateX(100%);
  }

  .menu-box a:hover img.joy {
    transform: translateY(100%);
  }

  .menu-box a:hover img.anger {
    transform: translateY(0);
  }

  .menu-box a:hover img.disgust {
    transform: translateX(0);
  }

  /* contents */

  .contents-container {
    display: flex;
    flex-direction: column;
    text-align: center;
  }

  .contents-title {
    margin-bottom: 30px;
  }

  .contents-box a {
    background-color: rgba(216, 112, 147, 0.571);
    padding: 10px;
    border-radius: 50px;
  }

  .contents-box {
    border: 4px solid #f1d7ff;
    border-radius: 20px;
    background-color: white;
    padding: 50px;
    margin-bottom: 30px;
  }

  .contents-box a:hover {
    background-color: palevioletred;
  }
</style>
