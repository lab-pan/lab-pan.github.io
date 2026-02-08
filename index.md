---
layout: default
title: Pan Lab - Sex determination & developmental innovations

permalink: /
---

<style>
/* General layout */
.section{ padding:48px 0; }
.lead{ font-size:1.05rem; line-height:1.6; max-width:80ch; }

/* Subtitle styling */
.page-subtitle{
  font-family: inherit;
  font-size:1.6rem;
  font-weight:600;
  color:#0f7b6c;               /* Max Planck green */
  margin-top:6px;
  margin-bottom:26px;
}

/* Central illustration */
.section-illustration{
  display:block;
  max-width:520px;
  width:100%;
  height:auto;
  margin:48px auto 56px auto;
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
  grid-template-columns:repeat(3, minmax(0,1fr));
  gap:22px;
  margin-top:28px;
}
@media (max-width:1050px){
  .people-grid{ grid-template-columns:repeat(3,1fr); }
}
@media (max-width:700px){
  .people-grid{ grid-template-columns:repeat(2,1fr); }
}
.person{ text-align:center; }
.avatar{
  width:198px;
  height:198px;
  object-fit:cover;
  border-radius:50%;
  box-shadow:0 4px 10px rgba(0,0,0,0.10);
}
.person .name{ margin-top:12px; font-weight:600; font-size:1.05rem; }
.person .role{
  font-size:0.95rem;
  font-weight:600;
}
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
  margin:0 0 18px 0;
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
  We combine comparative genomics, population genetics, and functional experiments to dissect sex-determining pathways and reconstruct their evolutionary origins, with a particular emphasis on ants.
  </p>

  <p>
  Our lab is based at the Max Planck Institute for Biology in Tübingen. We collaborate closely with the Darras lab at the
  <a href="https://evolution.zju.edu.cn/en/index.html">Centre for Evolutionary and Organismal Biology</a>
  at Zhejiang University.
  </p>

</div>

<!-- Illustration above Lab members -->

<div class="research-images" style="margin-top:70px;">
  <img src="{{ '/assets/images/Ants-haplodiploidy.png' | relative_url }}" alt="">
  <img src="{{ '/assets/images/2.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/images/1.jpg' | relative_url }}" alt="">
  <img src="{{ '/assets/images/3.jpg' | relative_url }}" alt="">
</div>


<h2 class="section-header">Lab members</h2>

<div class="people-grid">

  <div class="person">
    <img class="avatar" src="{{ '/assets/images/miya-pan.png' | relative_url }}" alt="Miya Pan">
    <div class="name">Qiaowei (Miya) Pan  |  潘乔维 </div>
    <div class="role">Principal Investigator</div>
    <div><a href="mailto:qiaowei.pan@tuebingen.mpg.de">qiaowei.pan@tuebingen.mpg.de</a></div>
  </div>

  <div class="person">
    <img class="avatar" src="{{ '/assets/images/chuanxin.png' | relative_url }}" alt="Chuanxin Yu">
    <div class="name">Chuanxin Yu  ｜  余传鑫</div>
    <div class="role">PhD Student</div>
    <div><a href="mailto:chuanxin.yu@tuebingen.mpg.de">chuanxin.yu@tuebingen.mpg.de</a></div>
  </div>

  <div class="person">
    <img class="avatar" src="{{ '/assets/images/hugo-darras.png' | relative_url }}" alt="Hugo Darras">
    <div class="name">Hugo Darras</div>
    <div class="role">Co-investigator</div>
    <div><a href="mailto:hdarras@zju.edu.cn">hdarras@zju.edu.cn</a></div>
  </div>

</div>



</section>
