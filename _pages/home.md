---
layout: archive
title: ""
permalink: /home/
author_profile: true
redirect_from:
  - /
  - /home
---

{% include base_path %} 
<div class="typewriter-container">
    <h1 class="typewriter-title" id="typewriter-text"></h1>
</div>

<style>
.typewriter-container {
    text-align: center;
    margin: 30px 0;
}
.typewriter-title {
    font-size: 2.5em;
    font-weight: bold;
    color: #000000;
    overflow: hidden;
    border-right: 3px solid #000000;
    white-space: nowrap;
    margin: 0 auto;
    letter-spacing: 2px;
    animation: blink-cursor 0.75s step-end infinite;
}
@keyframes blink-cursor {
    from, to { border-color: transparent; }
    50% { border-color: #000000; }
}
@media (max-width: 768px) {
    .typewriter-title {
        font-size: 1.2em;
        letter-spacing: 1px;
    }
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const typewriterElement = document.getElementById('typewriter-text');
    const text = "😎 Welcome to My Homepage (正在装修中)";
    let i = 0;
    const speed = 100;
    
    function typeWriter() {
        if (i < text.length) {
            typewriterElement.innerHTML += text.charAt(i);
            i++;
            setTimeout(typeWriter, speed);
        }
    }
    setTimeout(typeWriter, 500);
});
</script>
---

<img src='/images/Homepage/Home.jpg'>

---

# 🔥 News 

<table style="width: 100%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 15px; margin-bottom: 20px;">
<tr>
<td style="width: 20%; vertical-align: top; padding-right: 20px;">
<img src='/images/paper/EIAR1.png' alt="sym" style="width: 100%; border-radius: 4px;">
</td>
<td style="width: 80%; vertical-align: top;" markdown="1">


- 🌈 Our Research Paper was Accepted -- *2025.10*
  
- 📝 Title: Differentiated landscape pattern transformation strategies drive territorial space carbon neutrality: A path exploration based on mixed land use units [Link](https://doi.org/10.1016/j.scs.2025.106865)

- 📘 Journal: _Sustainable Cities and Society_

- 👨🏻‍🎓 Authors: **Fan, H.**, Jin, X., Zhu, J., Zhang, Z., Hu, C., Hu, H., Du, X, Zhou, Y

- 🎉🎉 Congratulations to all the authors
</td>
</tr>
</table>

<table style="width: 100%; border: 1px solid #e1e4e8; border-radius: 6px; padding: 15px; margin-bottom: 20px;">
<tr>
<td style="width: 20%; vertical-align: top; padding-right: 20px;">
<img src='/images/paper/EIAR1.png' alt="sym" style="width: 100%; border-radius: 4px;">
</td>
<td style="width: 80%; vertical-align: top;" markdown="1">

- 🌈 Our Research Paper was Accepted -- *2024.12*

- 📝 Title: Comprehensive evaluation of land-use carbon emissions integrating social network analysis and a zone-based machine learning approach [Link](https://doi.org/10.1016/j.eiar.2024.107775)

- 📘 Journal: _Environmental Impact Assessment Review_

- 👨🏻‍🎓 Authors: **Fan, H.**, Zhang, X., Zhou, X., Sun, Z., He, Y., Wan, W., Lv, T

- 🎉🎉 Congratulations to all the authors
</td>
</tr>
</table>

# 📖 Education

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2025.09 – Present</div>
    <div class="timeline-content">
      <h3><strong>Nanjing University, School of Geography and Ocean Science</strong></h3>
      <p>PhD in Geography, Supervisor: <a href="https://sgos.nju.edu.cn/jxb/list.htm">Dr. Xiaobin Jin</a></p>
    </div>
  </div>
  
  <div class="timeline-item">
    <div class="timeline-date">2022.09 – 2025.06</div>
    <div class="timeline-content">
      <h3><strong>Jiangxi University of Finance and Economics, Institute of Ecological Civilization</strong></h3>
      <p>Master's in Land Resources and Ecological Economics</p>
    </div>
  </div>

  <div class="timeline-item">
    <div class="timeline-date">2018.09 – 2022.06</div>
    <div class="timeline-content">
      <h3><strong>Yichun University, School of Economics and Management</strong></h3>
      <p>Bachelor’s in Business Administration</p>
    </div>
  </div>
</div>

<style>
.timeline {
  position: relative;
  padding-left: 30px;
}
.timeline::before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 2px;
  background: linear-gradient(to bottom, #92CDDC, #D9958F);
}
.timeline-item {
  position: relative;
  margin-bottom: 30px;
  padding-left: 20px;
}
.timeline-item::before {
  content: '';
  position: absolute;
  left: -8px;
  top: 5px;
  width: 12px;
  height: 12px;
  border-radius: 50%;
  background: #92CDDC;
  border: 2px solid white;
  box-shadow: 0 0 0 2px #92CDDC;
}
.timeline-date {
  font-weight: bold;
  color: #92CDDC;
  margin-bottom: 5px;
}
</style>

# 🔬 Research Interests

<div class="research-cards">
  <div class="research-card">
    <h3>🌿 Land Use Carbon Emissions</h3>
    <p>Investigating the relationship between land use patterns and carbon neutrality</p>
  </div>
  <div class="research-card">
    <h3>🏙️ Sustainable Cities</h3>
    <p>Urban planning strategies for environmental sustainability</p>
  </div>
  <div class="research-card">
    <h3>📊 Spatial Analysis</h3>
    <p>Advanced geospatial techniques for environmental research</p>
  </div>
</div>

<style>
.research-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin: 30px 0;
}
.research-card {
  background: white;
  padding: 25px;
  border-radius: 10px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.1);
  transition: transform 0.3s;
  border-left: 4px solid #28a745;
}
.research-card:hover {
  transform: translateY(-5px);
}
</style>

# 🌍 Visitor Map

# 👀 其他内容待开发，等有时间再来装修我的主页

