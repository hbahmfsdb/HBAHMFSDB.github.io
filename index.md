---
layout: default
---

<h1>动态效果测试页111</h1>

<style>
  .test-card {
    width: 200px;
    height: 150px;
    background: #007bff;
    color: white;
    text-align: center;
    line-height: 150px;
    margin: 100px auto;
    border-radius: 10px;
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  .test-card:hover {
    transform: scale(1.1);
  }
  .fade-up {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.6s ease;
  }
  .fade-up.visible {
    opacity: 1;
    transform: translateY(0);
  }
</style>

<div class="fade-up">
  <div class="test-card">悬停变大</div>
</div>

<script>
  document.addEventListener("DOMContentLoaded", function () {
    console.log("✅ 脚本运行");

    const el = document.querySelector('.fade-up');
    if (el) {
      el.classList.add('visible');
    }
  });
</script>
