<script>
  // your script goes here
</script>

<!-- markup (zero or more items) goes here -->
<header>
  <div class="header-cover">
    <h1 class="header-title">PONGDANG's BLOG</h1>
  </div>
</header>

<style>
  .header-cover {
    background: #800080;
    background: -webkit-linear-gradient(to right, #ffc0cb, #800080);
    background: linear-gradient(to right, #ffc0cb, #800080);

    height: 30vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .header-title {
    background-color: rgba(0, 0, 0, 0.728);
    padding: 0 2rem;
    /* 폰트 */
    font-size: 3.5vw;
    color: white;
    line-height: 2;
    letter-spacing: 1vw;
    /* 효과 */
    /* 원래 크기로 돌아오는데 0.6s 걸림 */
    transform: scale(1);
    transition: transform 0.6s;
  }

  .header-cover:hover .header-title {
    /* 효과 */
    /* 1.4배만큼 커지고 커지는데 0.6s 걸림 */
    transform: scale(1.1);
    transition: transform 0.6s;
  }
  .header-title:focus {
    outline: none;
    box-shadow: none;
    -webkit-box-shadow: none;
  }
</style>
