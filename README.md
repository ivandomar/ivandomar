<div id="main">
  <div id="row-1">
      <h1 id="name">IVAN</h1>
      <h2 id="title">ENGENHEIRO <br />DE SOFTWARE</h2>
  </div>
  <div id="row-2">
      <h3 id="js">JAVASCRIPT</h3>
      <h3 id="ts">TYPESCRIPT</h3>
      <h3 id="node">NODEJS</h3>
      <h3 id="react">REACT</h3>
      <h3 id="angular">ANGULAR</h3>
      <h3 id="php">PHP</h3>
      <h3 id="laravel">LARAVEL</h3>
  </div>
</div>
<style>
  * {
      margin: 0;
      padding: 0;
      font-family: helvetica, sans-serif;
  }

  #main {
      display: flex;
      flex-direction: column;
  }

  #row-1, #row-2 {
      display: flex;
      justify-content: space-between;
  }

  h1, h2 {
      display: inline-block;
  }

  h1 {
      font-weight: bolder;
      font-size: 18vw;
      line-height: 14vw;
  }

  h2 {
      font-weight: 300;
      font-size: 7.6vw;
      line-height: 7vw;
  }

  h3 {
      font-weight: 100;
      font-size: 2vw;
      line-height: 1rem;
      padding: 1vw;
  }

  #name {
      color: #222;
  }

  #title {
      color: #777;
  }

  #js {
      color: #F0DB4F;
      background-color: #323330;
  }

  @media (prefers-color-scheme: dark) {

  }

  @media (max-width: 767px) {
      #row-1 {
          flex-direction: column;
          text-align: center;
      }

      #row-2 {
          width: 65vw;
          align-self: center;
      }

      h1 {
          font-size: 30vw;
          line-height: 23vw;
      }

      h2 {
          font-size: 9vw;
          line-height: 7vw;
      }

      h3 {
          font-size: 1.9vw;
          line-height: 1.9vw;
      }
  }
</style>
