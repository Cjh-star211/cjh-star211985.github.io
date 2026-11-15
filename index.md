---
layout: home
title: "首页"
---

<div class="hero">
  <div class="hero-tag">✦ WELCOME TO MY WORLD ✦</div>
  <h1 class="hero-title">蔡叽's World ♡</h1>
  <p class="hero-subtitle">WELCOME TO MY  LITTLE UNIVERSE!</p>
  <p class="hero-description">一个努力学习代码的美女发疯日常</p>
  <div class="hero-clock">
    <span id="clock">00:00:00</span>
    <span class="clock-label">MY LITTLE CORNER OF THE INTERNET</span>
  </div>
  <p class="hero-decoration">♡ ✧ ⋆｡˚ ☁︎ ˚｡⋆ ✧ ♡</p>
</div>

## ✧ ABOUT MY UNIVERSE

这里是努力学习代码的07美女的互联网帝国据点。

> 好看的皮囊千篇一律  
> 有趣的灵魂万里挑一  
> 不巧  
> **蔡叽都有**

这里会记录我的发疯时刻、奇思妙想、家产（博肖），以及我与代码斗智斗勇的奋斗史！

## ✧ MY INTERESTS

**以为我会说什么高级的吗？**

**哈哈哈哈哈！**

- 🖥️ 编程与互联网
- 👽 搞笑
- 🧸 旅游
- 🎧 音乐
- 😋 美食
- 🤤 美色

> 博君一肖是真的  
> 每个女孩都有成为公主的潜质

## ✧ EXPLORE MY UNIVERSE

<div class="universe-grid">
  <a class="universe-card" href="/cjh-star211985.github.io/daily-life/">
    <span>📸</span>
    <strong>MY DAILY LIFE</strong>
    <small>生活碎片与电子剪贴簿</small>
  </a>
  <a class="universe-card" href="/cjh-star211985.github.io/code-chaos/">
    <span>💻</span>
    <strong>CODE & CHAOS</strong>
    <small>代码战争实录</small>
  </a>
  <a class="universe-card" href="/cjh-star211985.github.io/music-player/">
    <span>🎧</span>
    <strong>MY MUSIC PLAYER</strong>
    <small>我的音乐收藏</small>
  </a>
  <a class="universe-card" href="/cjh-star211985.github.io/secret-internet/">
    <span>👾</span>
    <strong>SECRET INTERNET</strong>
    <small>禁止无聊的秘密基地</small>
  </a>
  <a class="universe-card" href="/cjh-star211985.github.io/message-to-me/">
    <span>💌</span>
    <strong>MESSAGE TO ME</strong>
    <small>写给未来自己的信</small>
  </a>
</div>

## ✧ MY LITTLE BLOG

很高兴有人能听我的碎碎念，你愿意和我成为好朋友吗！

<script>
function updateClock() {
  const clock = document.getElementById("clock");
  if (clock) {
    clock.textContent = new Date().toLocaleTimeString("zh-CN", {
      hour12: false
    });
  }
}
updateClock();
setInterval(updateClock, 1000);
</script>
