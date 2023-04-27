<style>
#cube {
  position: relative;
  float: right;
  top: 20px;
  transform-style: preserve-3d;
  animation: spin 20s linear infinite;
}

#cube > div {
  position: absolute;
  transform-style: preserve-3d;
}

@keyframes spin {
  from {
    transform: rotateX(-0.1turn) rotateY(0turn);
  }
  to {
    transform: rotateX(-0.1turn) rotateY(1turn);
  }
}

/* unspinning */
#cube > div > div {
  animation: un-spin 20s linear infinite;
}

@keyframes un-spin {
  from {
    transform: rotateY(0turn);
  }
  to {
    transform: rotateY(-1turn);
  }
}
</style>

<a href="https://github.com/cyae">
    <img align="left" src="https://komarev.com/ghpvc/?username=cyae&label=Visitors&color=red&style=flat&logo=github" alt="gtihub-visitors" />
</a>

<div id="cube" style="width: 4em; height: 8em;">
    <div style="transform: translate3d(2em, 2em, 0em)">
      <div>🔭</div>
    </div>
    <div style="transform: translate3d(0em, 0em, 2em)">
      <div>🌠</div>
    </div>
    <div style="transform: translate3d(4em, 0em, 2em)">
      <div>🪐</div>
    </div>
    <div style="transform: translate3d(0em, 4em, 2em)">
      <div>🌍</div>
    </div>
    <div style="transform: translate3d(4em, 4em, 2em)">
      <div>🌞</div>
    </div>
    <div style="transform: translate3d(0em, 0em, -2em)">
      <div>🌛</div>
    </div>
    <div style="transform: translate3d(4em, 0em, -2em)">
      <div>🛸</div>
    </div>
    <div style="transform: translate3d(0em, 4em, -2em)">
      <div>🚀</div>
    </div>
    <div style="transform: translate3d(4em, 4em, -2em)">
      <div>🌌</div>
    </div>
  </div>

<br>

---

## Hiya! I'm cyae!

- 🔭 My research interests include transfer learning, generative model.
- 🌱 I'm currently working at AntGroup, an <b>fintech</b> company. Before that, I took internship at Huawei Cloud Ltd.
- ❤️ I like eating 🍉, raising 🐈, playing 🏸, sleeping in 🛌 and running 🏃‍♂️!

---

<div align="right">
    <a href="https://github.com/cyae">
        <img
            src="https://github-readme-stats-cyae.vercel.app/api?username=cyae&show_icons=true&theme=transparent&count_private=true&include_all_commits=true&card_width=430&exclude_repo=github-readme-stats" />
    </a>
    <br>
    <a href="https://github.com/cyae">
        <img src="https://github-readme-stats-cyae.vercel.app/api/top-langs/?username=cyae&layout=compact&theme=transparent&langs_count=10&card_width=438&exclude_repo=github-readme-stats" />
    </a>
</div>
