---
layout: default
title: Pan Lab - Haplodiploidy
permalink: /
---

<style>
/* General layout */
.section{ padding:48px 0; }
.lead{ font-size:1.05rem; line-height:1.6; max-width:80ch; }

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
.person .role, .person .inst{
  font-size:0.9rem;
  line-height:1.25;
}
.person .role{ font-weight:600; }
.person .inst{ opacity:0.8; }
.person a{
  font-size:0.9rem;
  color:#0066cc;
  text-decoration:none;
}
.person a:hover{ text-decoration:underline; }

/* Banner link */
.team-banner{
  text-align:center;
  margin-top:50px;
}
.team-banner a{
  font-size:1rem;
  color:#0066cc;
  text-decoration:none;
}
.team-banner a:hover{
  color:#004999;
  text-decoration:underline;
}
</style>

<section class="section">
  
<style>
  .lab-text a {
    color: #2f4a6d;
    text-decoration: none;
  }

  .lab-text a:hover {
    text-decoration: underline;
  }
</style>

<div class="lab-text">

  <p>Our lab studies how sex is determined at the molecular level and how sex-determining mechanisms evolve over time. Sex determination is the developmental process that directs an embryo to develop as female or male. We are interested in understanding both how these mechanisms operate in different species and why they are remarkably diverse and evolutionarily labile.</p>

  <p>While we also work on sex chromosomes, our primary focus is on <strong>haplodiploid organisms</strong>, in which females develop from fertilized, diploid eggs (2n) and males develop from unfertilized, haploid eggs (1n). Haplodiploidy has evolved repeatedly from ancestors with chromosomal sex determination, yet the molecular and developmental changes underlying this transition remain poorly understood.</p>

  <p>Using multiple haplodiploid model species, we investigate how sex is specified during early development, from gamete formation to the first cell fate decisions. We ask how alternative sex-determining pathways are established, how they interact with genome architecture, and how novel mechanisms emerge and spread through populations.</p>

  <p>Our work addresses three main questions:</p>

  <ul>
    <li>What are the molecular mechanisms underlying haplodiploid sex determination?</li>
    <li>How do transitions between different sex-determining systems occur?</li>
    <li>What developmental innovations accompanied the evolution of haplodiploidy?</li>
  </ul>

  <p>We combine comparative genomics, population genetics, and functional experiments to dissect sex-determining pathways and reconstruct their evolutionary origins, with a particular emphasis on ants.</p>

  <p>Our lab is based at the Max Planck Institute for Biology in Tübingen.  We collaborate closely with the Darras lab  at the <a href="https://evolution.zju.edu.cn/en/index.html">Centre for Evolutionary and Organismal Biology</a> at Zhejiang University through shared projects and resources.</p>

</div>


<div style="height:40px;"></div>

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
      <div><a href="mailto:chuyu@uni-mainz.de">chuyu@uni-mainz.de</a></div>
    </div>

     <div class="person">
      <img class="avatar" src="{{ '/assets/images/hugo-darras.png' | relative_url }}" alt="Hugo Darras">
      <div class="name">Hugo Darras</div>
      <div class="role"> Co-investigator</div>
      <div><a href="mailto:hdarras@zju.edu.cn">hdarras@zju.edu.cn</a></div>
    </div>

  </div>

  <div class="research-images" style="display:flex; gap:2%; justify-content:center; margin-top:70px;">
  <img src="{{ '/assets/images/6962841056_04bd7b4b6f_c.jpg' | relative_url }}" alt="Research image" style="width:21%; height:auto; object-fit:cover;">
  <img src="{{ '/assets/images/14831812109_248e71f584_c.jpg' | relative_url }}" alt="Research image" style="width:21%; height:auto; object-fit:cover;">
  <img src="{{ '/assets/images/7294863010_93d13923bb_c.jpg' | relative_url }}" alt="Research image" style="width:21%; height:auto; object-fit:cover;">
  <img src="{{ '/assets/images/4837265100_7ff68cd6f6_c.jpg' | relative_url }}" alt="Research image" style="width:21%; height:auto; object-fit:cover;">
</div>

</section>
