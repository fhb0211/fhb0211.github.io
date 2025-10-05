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
<div style="margin: 20px 0;">
  <h1 id="typewriter-text" style="font-size: 1.5em; font-weight: bold; text-align: left;"></h1>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    const element = document.getElementById('typewriter-text');
    const text = "😎 Welcome to My Homepage (正在装修中)";
    let i = 0;
    
    function typeWriter() {
      if (i < text.length) {
        element.innerHTML += text.charAt(i);
        i++;
        setTimeout(typeWriter, 100);
      }
    }
    setTimeout(typeWriter, 500);
  });
</script>
---

<img src='/images/Homepage/Home.jpg'>

---

<div style="height: 50px;"></div>

# 🔥 News 

<table style="width: 100%; border: none; border-collapse: collapse; padding: 15px; margin-bottom: 20px; background: transparent;">
<tr class="hover-row">
<td style="width: 20%; vertical-align: top; padding-right: 20px; border: none;">
<img src='/images/paper/SCS1.PNG' alt="sym" style="width: 100%; border-radius: 4px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</td>
<td style="width: 80%; vertical-align: top; border: none; padding-left: 20px;" markdown="1">

- 🌈 Our Research Paper was Accepted -- *2025.10*
  
- 📝 Title: Differentiated landscape pattern transformation strategies drive territorial space carbon neutrality: A path exploration based on mixed land use units [Link](https://doi.org/10.1016/j.scs.2025.106865)

- 📘 Journal: _Sustainable Cities and Society_

- 👨🏻‍🎓 Authors: **Fan, H.**, Jin, X., Zhu, J., Zhang, Z., Hu, C., Hu, H., Du, X, Zhou, Y

- 🎉🎉 Congratulations to all the authors!
</td>
</tr>
</table>

<table style="width: 100%; border: none; border-collapse: collapse; padding: 15px; margin-bottom: 20px; background: transparent;">
<tr class="hover-row">
<td style="width: 20%; vertical-align: top; padding-right: 20px; border: none;">
<img src='/images/paper/EIAR1.png' alt="sym" style="width: 100%; border-radius: 4px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</td>
<td style="width: 80%; vertical-align: top; border: none; padding-left: 20px;" markdown="1">

- 🌈 Our Research Paper was Accepted -- *2024.12*

- 📝 Title: Comprehensive evaluation of land-use carbon emissions integrating social network analysis and a zone-based machine learning approach [Link](https://doi.org/10.1016/j.eiar.2024.107775)

- 📘 Journal: _Environmental Impact Assessment Review_

- 👨🏻‍🎓 Authors: **Fan, H.**, Zhang, X., Zhou, X., Sun, Z., He, Y., Wan, W., Lv, T

- 🎉🎉 Congratulations to all the authors!
</td>
</tr>
</table>

<style>
/* 整行悬停效果 */
.hover-row {
  transition: all 0.3s ease !important;
}

.hover-row:hover {
  transform: translateY(-7px) !important;
}

.hover-row:hover img {
  transform: translateY(-15px) !important;
  box-shadow: 0 8px 16px rgba(0,0,0,0.2) !important;
}
</style>
---
<div style="height: 50px;"></div>


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
  margin-top: 20px;
}
.timeline::before {
  content: '';
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 2px;
  background: linear-gradient(to bottom, #3498db, #2ecc71);
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
  background: linear-gradient(135deg, #3498db, #2ecc71);
  box-shadow: 0 0 0 3px rgba(52,152,219,0.2);
}
.timeline-date {
  font-weight: bold;
  color: #3498db;
  margin-bottom: 5px;
}
.timeline-content h3 {
  font-size: 16px;
  margin-bottom: 8px;
}
</style>
---
<div style="height: 50px;"></div>

# 🔬 Research Interests

<div class="research-cards">
  <div class="research-card">
    <div class="card-header gradient-header">
      <h3>🌾 Farmland Protection</h3>
    </div>
    <div class="card-content">
      <p>To be updated</p>
    </div>
  </div>

  <div class="research-card">
    <div class="card-header gradient-header2">
      <h3>🏙️ Sustainable Cities</h3>
    </div>
    <div class="card-content">
      <p>To be updated</p>
    </div>
  </div>

  <div class="research-card">
    <div class="card-header gradient-header3">
      <h3>🌳 Ecological Restoration</h3>
    </div>
    <div class="card-content">
      <p>To be updated</p>
    </div>
  </div>
</div>

<style>
.research-cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 25px;
  margin: 30px 0;
}

.research-card {
  background: rgba(255,255,255,0.2);
  backdrop-filter: blur(12px);
  border: 1px solid rgba(255,255,255,0.2);
  border-radius: 16px;
  overflow: hidden;
  box-shadow: 0 6px 18px rgba(0,0,0,0.1);
  transition: transform 0.4s, box-shadow 0.4s;
}

.research-card:hover {
  transform: translateY(-10px) scale(1.03);
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
}

.card-header {
  padding: 18px 20px;
  color: white;
}

.gradient-header {
  background: linear-gradient(135deg, #4facfe, #00f2fe);
}
.gradient-header2 {
  background: linear-gradient(135deg, #43e97b, #38f9d7);
}
.gradient-header3 {
  background: linear-gradient(135deg, #fa709a, #fee140);
}

.card-header h3 {
  margin: 0;
  font-size: 20px;
  font-weight: 700;
  letter-spacing: 0.5px;
}

.card-content {
  padding: 20px;
  font-size: 15px;
  color: #333;
  line-height: 1.7;
  background: rgba(255,255,255,0.3);
}

.research-card:hover .card-header {
  filter: brightness(1.15);
}
</style>
---
<div style="height: 50px;"></div>

# 🌏 Visitor Map
{: style="margin-bottom: 0;"}

<div style="padding: 10px 0; margin-top: 5px;">
  <div style="display: flex; flex-wrap: wrap; gap: 20px; align-items: center;">
    
    <!-- 地球部分 -->
    <div style="flex: 1; min-width: 250px;">
      <div style="width: 100%; max-width: 300px;">
        <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=t_uzPbOFNu4gwh09R56IYNh122kCKzSjy1fMgWGC02Q"></script>
      </div>
    </div>
    
    <!-- 统计信息部分 -->
    <div style="flex: 1; min-width: 250px;">
      <div>
        <h3 style="margin-top: 0; color: #2c3e50; border-bottom: 1px solid #eee; padding-bottom: 10px;">Statistics</h3>
        
        <div style="display: flex; justify-content: space-between; margin-bottom: 15px;">
          <div style="text-align: center;">
            <div style="font-size: 24px; font-weight: bold; color: #3498db;">1,247</div>
            <div style="font-size: 12px; color: #7f8c8d;">Total visits</div>
          </div>
          <div style="text-align: center;">
            <div style="font-size: 24px; font-weight: bold; color: #2ecc71;">24</div>
            <div style="font-size: 12px; color: #7f8c8d;">Today's visits</div>
          </div>
          <div style="text-align: center;">
            <div style="font-size: 24px; font-weight: bold; color: #e74c3c;">18</div>
            <div style="font-size: 12px; color: #7f8c8d;">Country/Region</div>
          </div>
        </div>
        
        <div style="margin-top: 15px;">
          <div style="font-size: 14px; color: #7f8c8d; margin-bottom: 5px;">🌏 Popular visit areas</div>
          <div style="display: flex; flex-wrap: wrap; gap: 8px;">
            <span style="background: #eaf2f8; color: #3498db; padding: 4px 10px; border-radius: 20px; font-size: 12px;">China</span>
            <span style="background: #eaf2f8; color: #3498db; padding: 4px 10px; border-radius: 20px; font-size: 12px;">America</span>
            <span style="background: #eaf2f8; color: #3498db; padding: 4px 10px; border-radius: 20px; font-size: 12px;">Germany</span>
            <span style="background: #eaf2f8; color: #3498db; padding: 4px 10px; border-radius: 20px; font-size: 12px;">Japan</span>
          </div>
        </div>
        
        <div style="margin-top: 15px; font-size: 12px; color: #95a5a6; text-align: center;">
          Last updated: October 1, 2025 (I will not operate, the data is wrong🤭)
        </div>
      </div>
    </div>
    
  </div>
</div>

<style>
#clstr_globe {
  width: 100% !important;
  height: 20px !important;
  max-width: 500px;
  display: block;
  margin: 0 auto;
}
</style>
---
<div style="height: 50px;"></div>


# 👀 其他内容待开发，等有时间再来装修我的主页


