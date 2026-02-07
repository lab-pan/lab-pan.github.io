---
layout: default
title: Pan Lab - Haplodiploidy
permalink: /
show_title: false
---

<style>
/* General layout */
.section{ padding:48px 0; }
.lead{ font-size:1.05rem; line-height:1.6; max-width:80ch; }

/* Custom title with image */
.title-with-icon{
  display:flex;
  align-items:center;
  gap:24px;
  margin-bottom:28px;
}
.title-with-icon h1{
  margin:0;
}
.title-with-icon img{
  height:3.2em;
  width:auto;
}

/* Research images */
.research-images{
  display:flex;
  gap:2%;
  justify-content:space-between;
  margin-top:30px;
}
.research-images img{
  width:23.5%;
  height:auto;
  object-fit:cover;
}

/* People */
.people-grid{
  display:grid;
  grid-template-columns:repeat(4, minmax(0,1fr));
  gap:18px;
  margin-top:24px;
}
@media (max-width:1050px){
  .people-grid{ grid-template-columns:repeat(3,1fr); }
}
@media (max-width:700px){
  .people-grid{ grid-template-columns:repeat(2,1fr); }
}
.person{ text-align:center; }
.avatar{
  width:110px;
  height:110px;
  object-fit:cover;
  border-radius:50%;
  box-shadow:0 4px 10px rgba(0,0,0,0.10);
}
.person .name{ margin-top:10px; font-weight:600; font-size:1.02rem; }
.person .role{ font-size:0.9rem; font-weight:600; }
.person a{
  font-size:0.9rem;
  color:#0066cc;
  text-decoration:none;
}
.person a:hover{ text-decoration:underline; }

/* Section header */
.section-header{
  font-size:1.4em;
  font-weight:700;
  margin:0 0 16px 0;
}
</style>

<section class="section">

<div class="title-with-icon">
  <h1 class="page-title">Pan Lab - Haplodiploidy</h1>
  <img src="{{ '/assets/images/Ants-haplodiploidy.png' | relative_url }}"
       alt="Ant haplodiploidy illustration">
</div>

<div class="lab-text">

<p>
Our lab studies how sex is determined at the molecular level and how sex-determining mechanisms evolve over time. Sex determination is the developmental process that directs an embryo to develop as female or male. We are interested in understanding both how these mechanisms operate in different species and why they are remarkably diverse and evolutionarily labile. While we also work on sex chromosomes, our primary focus is on haplodiploid organisms.
</p>

<p>
Using multiple haplodiploid model species, we investigate how sex is specified during early development, from gamete formation to the first cell fate decisions.
</p>

<ul>
  <li>What are the molecular mechanisms underlying haplodiploid sex determination?</li>
  <li>How do transitions between different sex-determining systems occur?</li>
  <li>What developmental innovations accompanied the evolution of haplodiploidy?</li>
</ul>

<p>
Our lab is based at the Max Planck Institute for Biology in Tübingen. We collaborate closely with the Darras lab at the <a href="https://evolution.zju.edu.cn/en/index.html">Centre for Evolutionary and Organismal Biology</a> at Zhejiang University.
</p>

</div>

<div style="height:40px;"></div>

<h2 class="section-header">Lab members</h2>

<div class="people-grid">

  <div class="person">
    <img class="avatar" src="{{ '/assets/images/miya-pan.png' | relative_url }}" alt="Miya Pan">
    <div class="name">Qiaowei (Miya) Pan</div>
    <div class="role">Principal Investigator</div>
    <div><a href="mailto:qiaowei.pan@tuebingen.mpg.de">qiaowei.pan@tuebingen.mpg.de</a></div>
  </div>

  <div class="person">
    <img class="avatar" src="{{ '/assets/images/chuanxin.png' | relative_url }}" alt="Chuanxin Yu">
    <div class="name">Chuanxin Yu</div>
    <div class="role">PhD Student</div>
  </div>

  <div class="person">
    <img class="avatar" src="{{ '/assets/images/hugo-darras.png' | relative_url }}" alt="Hugo Darras">
    <div class="name">Hugo Darras</div>
    <div class="role">Co-investigator</div>
  </div>

</div>

<div class="research-images" style="margin-top:70px;">
  <img src="{{ '/assets/images/6962841056_04bd7b4b6f_c.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/images/14831812109_248e71f584_c.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/images/7294863010_93d13923bb_c.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/images/4837265100_7ff68cd6f6_c.jpg' | relative_url }}" alt="">
</div>

</section>
