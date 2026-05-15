---
theme: seriph
background: https://cover.sli.dev
title: Ubuntu release at NCHU
info: 
class: text-center
drawings:
  persist: false
transition: slide-left
comark: true
---

# Ubuntu Release Party

報告人：中興應數 林煒宸 Windson

---
transition: slide-left
---

# WHOAMI

- 中興大學 長虹吉他社 50th 教學、51st 副社長
- 用 Linux 的一般人

> email: info AT windson.cc <br>
> blog: www.windson.cc

---
transition: slide-up
---

# 比較 Windows ＆ Linux

- ## 記憶體用量

<div class="memory-container">
  <div class="memory-item">
    <img src="./img/mint-memory.png" alt="Mint Memory">
    <div v-click="1">
      <span class="memory-label">12.6%</span>
    </div>
  </div>
  
  <div class="memory-item">
    <img src="./img/windows-memory.png" alt="Windows Memory">
    <div v-click="2">
      <span class="memory-label">68%</span>
    </div>
  </div>
</div>


<style>
.memory-container {
  display: flex;
  gap: 10px;
  margin-top: 50px;
  margin-right: 20px; 
}

/* 將容器設為 Flexbox 並垂直排列子元素 */
.memory-item {
  display: flex;
  flex-direction: column; /* 垂直排列：圖片在上，文字在下 */
  align-items: center;    /* 於交錯軸 (Cross Axis) 置中對齊 */
  gap: 8px;               /* 控制圖片與文字之間的間距 */
}

.memory-item img {
  width: 450px;
  height: auto;
  display: flex;
}

/* 移除 position: absolute，保留文字排版設定 */
.memory-label {
font-size: 1.2rem;
  font-family: monospace;
  font-weight: bold;
  color: #ffffff; /* 配合淺色背景調整為深色文字 */
}
</style>
---
transition: slide-up
---


- ## 更新
<div v-click="1">
  <img src="./img/windows-update.png" class="mx-auto">
</div>

<style>
img {
  margin-top: 60px;
  width: 500px;
  height: auto;

}
</style>



