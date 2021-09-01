<script>
  let Creative = "assets/Creative.png";
</script>

<div class="container">
  <div class="content text">
    <div class="button">
      <span>About Us</span>
    </div>
    <div class="text-area">
      <h2>
        We're a team of dynamic personalities, creativity, & cutting edge
        innovation
      </h2>
      <span
        >Lorem ipsum, dolor sit amet consectetur adipisicing elit. Libero
        officia aperiam optio illo qui error perferendis facere. Dolores fugit
        saepe esse sequi a culpa consequuntur qui, accusantium modi
        reprehenderit in! Lorem ipsum dolor sit amet, consectetur adipisicing
        elit. Accusamus, architecto. Aspernatur, eaque! Reprehenderit, doloribus
        quidem! Modi inventore facilis nobis, culpa optio quisquam suscipit
        aspernatur iure nostrum placeat nihil accusantium expedita.:50</span
      >
      <h4>Read more..</h4>
    </div>
  </div>
  <div class="content">
    <img alt="creative team" src={Creative} />
  </div>
</div>

<style>
  .container {
    max-width: 1200px;
    margin: 5rem auto 5rem auto;

    display: flex;
    height: 100%;
  }
  .content {
    justify-content: flex-start;
    align-items: center;
    width: 50%;
    overflow: hidden;
    height: 100%;
  }
  .text {
    margin: 50px 100px 1rem 1rem;
  }
  .text h4 {
    color: #7a64f2;
  }
  .text h2 {
    font-size: 2.5rem;
  }
  .text-area {
    padding-right: 50px;
  }
  .text-area span {
    line-height: 30px;
  }
  .content h2,
  .content span,
  h4 {
    display: flex;
    text-align: left;
  }
  .content img {
    display: block;
    max-height: 605px;
    width: auto;
    height: auto;
  }
  .content .button {
    background-color: rgba(254, 145, 11, 0.24);
    color: #fe910b;
    width: fit-content;
    padding: 6px 20px 5px;
    border-radius: 4px;
    margin-bottom: 20px;
    letter-spacing: 0;
  }
  h2 {
    line-height: 3rem;
  }
</style>
