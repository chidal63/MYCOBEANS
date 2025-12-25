---
title: "Consortium"
permalink: /consortium/
layout: single
classes: wide
sidebar: false
toc: false
---

<style>
  /* layout */
  .partner-grid{
    display:grid;
    gap:20px;
    margin: 0 0 26px 0;
  }
  .grid-2{ grid-template-columns: repeat(2, minmax(0, 1fr)); }
  .grid-3{ grid-template-columns: repeat(3, minmax(0, 1fr)); }
  .grid-4{ grid-template-columns: repeat(4, minmax(0, 1fr)); }

  /* responsive */
  @media (max-width: 980px){
    .grid-3, .grid-4{ grid-template-columns: repeat(2, minmax(0, 1fr)); }
  }
  @media (max-width: 620px){
    .grid-2, .grid-3, .grid-4{ grid-template-columns: 1fr; }
  }

  /* cards */
  .partner-card{
    background:#fff;
    border:1px solid rgba(0,0,0,.08);
    border-radius:16px;
    padding:16px 16px 14px 16px;
    box-shadow: 0 1px 0 rgba(0,0,0,.02);
  }

  /* logo box */
  .partner-logo{
    background:#fff;
    border:1px solid rgba(0,0,0,.06);
    border-radius:14px;
    padding:16px 16px;
    display:flex;
    align-items:center;
    justify-content:center;
    min-height:110px;
    margin-bottom:10px;
  }
  .partner-logo img{
    max-height:78px;
    max-width:100%;
    width:auto;
    height:auto;
    object-fit:contain;
    display:block;
  }

  /* name lines */
  .partner-title{
    margin:0 0 6px 0;
    line-height:1.15;
  }
  .partner-title .name{
    font-weight:800;
    font-size:1.02rem;
    display:block;
    white-space:nowrap;
    overflow:hidden;
    text-overflow:ellipsis;
  }
  .partner-title .meta{
    display:block;
    font-size:.92rem;
    opacity:.8;
  }

  .partner-desc{
    margin:0;
    line-height:1.35;
    font-size:0.98rem;
  }

  /* section labels */
  .subsection-label{
    font-weight:800;
    margin: 0 0 10px 0;
  }

  /* compensate excessive white margins in some logos */
  .logo-wide{
    transform: scale(1.18);
  }

  /* PI / Industry contact */
  .partner-contact{
    margin-top:10px;
    padding-top:8px;
    border-top:1px solid rgba(0,0,0,.08);
    font-size:0.85rem;          /* smaller */
    line-height:1.25;
    color:rgba(0,0,0,.65);      /* lighter */
    font-weight:400;            /* lighter */
  }
  .partner-contact .label{
    font-weight:600;            /* label slightly stronger */
    color:rgba(0,0,0,.70);
  }
</style>

## Consortium overview

MYCOBEANS is implemented by a multidisciplinary and intersectoral consortium composed of academic and non-academic organisations from Europe, the United Kingdom and ASEAN countries. The consortium integrates complementary expertise in analytical chemistry, toxicology, biotechnology, bioinformatics, molecular biology, food chemistry, food processing and regulatory science, ensuring full coverage of the project objectives and strong integration between research and application.  
The consortium includes six academic institutions, one public non-academic research organisation and four industrial partners. The partnership is based in the EU, the UK and the ASEAN region.

---

## Coordinating Institution

<div class="partner-grid grid-2">
  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/UNIPR.jpg' | relative_url }}" alt="University of Parma (UNIPR)">
    </div>
    <p class="partner-title">
      <span class="name">University of Parma</span>
      <span class="meta">(UNIPR – Italy)</span>
    </p>
    <p class="partner-desc">UNIPR coordinates the project and ensures scientific coherence, governance and dissemination activities. The institution contributes expertise in food safety, mycotoxin analysis and risk assessment, acting as a central hub for interdisciplinary integration across the consortium.</p>
    <div class="partner-contact"><span class="label">Principal Investigator:</span> Chiara Dall’Asta</div>
  </div>
</div>

---

## Academic partners

<div class="subsection-label">Europe &amp; UK</div>
<div class="partner-grid grid-2">

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/UNIVIE.jpeg' | relative_url }}" alt="University of Vienna (UNIVIE)">
    </div>
    <p class="partner-title">
      <span class="name">University of Vienna</span>
      <span class="meta">(UNIVIE – Austria)</span>
    </p>
    <p class="partner-desc">UNIVIE provides expertise in toxicology and exposure assessment, contributing to the evaluation of health risks associated with mycotoxin occurrence and combined exposure scenarios.</p>
    <div class="partner-contact"><span class="label">Principal Investigator:</span> Doris Marko</div>
  </div>

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/QUB.png' | relative_url }}" alt="Queen’s University Belfast (QUB)">
    </div>
    <p class="partner-title">
      <span class="name">Queen’s University Belfast</span>
      <span class="meta">(QUB – United Kingdom)</span>
    </p>
    <p class="partner-desc">QUB supports knowledge transfer and training activities, with experience in interdisciplinary education, dissemination and public engagement.</p>
    <div class="partner-contact"><span class="label">Principal Investigator:</span> Nicholas Birse</div>
  </div>

</div>

<div class="subsection-label">Thailand</div>
<div class="partner-grid grid-3">

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/TU.png' | relative_url }}" alt="Thammasat University (TU)" class="logo-wide">
    </div>
    <p class="partner-title">
      <span class="name">Thammasat University</span>
      <span class="meta">(TU – Thailand)</span>
    </p>
    <p class="partner-desc">TU contributes expertise in analytical chemistry and interlaboratory method development, supporting the detection and monitoring of mycotoxins in beans and legumes.</p>
    <div class="partner-contact"><span class="label">Principal Investigator:</span> Awanwee Petchkongkaew</div>
  </div>

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/MU.png' | relative_url }}" alt="Mahidol University (MU)" class="logo-wide">
    </div>
    <p class="partner-title">
      <span class="name">Mahidol University</span>
      <span class="meta">(MU – Thailand)</span>
    </p>
    <p class="partner-desc">MU contributes expertise in molecular biology and bioinformatics, supporting the application of genomics-driven approaches to the study of fungal contamination and mycotoxin-related risks.</p>
    <div class="partner-contact"><span class="label">Principal Investigator:</span> Thidathip Wongsurawat</div>
  </div>

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/PSU.png' | relative_url }}" alt="Prince of Songkla University (PSU)" class="logo-wide">
    </div>
    <p class="partner-title">
      <span class="name">Prince of Songkla University</span>
      <span class="meta">(PSU – Thailand)</span>
    </p>
    <p class="partner-desc">PSU provides expertise in food science and food processing, contributing to the assessment of mycotoxin occurrence and mitigation strategies along the food production chain.</p>
    <div class="partner-contact"><span class="label">Principal Investigator:</span> Chongdee Thammakhet-Buranachai</div>
  </div>

</div>

---

## Non-academic partner

<div class="partner-grid grid-2">
  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/NSTDA-BIOTEC.png' | relative_url }}" alt="NSTDA-BIOTEC">
    </div>
    <p class="partner-title">
      <span class="name">NSTDA-BIOTEC</span>
      <span class="meta">(Thailand)</span>
    </p>
    <p class="partner-desc">NSTDA-BIOTEC contributes expertise in biotechnology and fermentation processes, supporting the development and evaluation of bio-based strategies and multi-omics integration for mycotoxin risk mitigation.</p>
    <div class="partner-contact"><span class="label">Principal Investigator:</span> Nitsara Karoonuthaisiri</div>
  </div>
</div>

---

## Industrial partners

<div class="partner-grid grid-4">

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/Barilla.png' | relative_url }}" alt="Barilla">
    </div>
    <p class="partner-title">
      <span class="name">Barilla</span>
      <span class="meta">(Italy)</span>
    </p>
    <p class="partner-desc">Barilla contributes an industrial perspective on legume-based food products, supporting the alignment of research activities with real-world production and quality requirements.</p>
    <div class="partner-contact"><span class="label">Industry contact:</span> Michele Suman</div>
  </div>

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/Hifood.png' | relative_url }}" alt="HiFood">
    </div>
    <p class="partner-title">
      <span class="name">HiFood</span>
      <span class="meta">(Italy)</span>
    </p>
    <p class="partner-desc">HiFood provides expertise in food ingredients and processing, contributing to the evaluation of practical mitigation strategies and their applicability in industrial contexts.</p>
    <div class="partner-contact"><span class="label">Industry contact:</span> Daniele Mori</div>
  </div>

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/Biopharm.png' | relative_url }}" alt="Biopharm">
    </div>
    <p class="partner-title">
      <span class="name">Biopharm</span>
      <span class="meta">(Italy)</span>
    </p>
    <p class="partner-desc">Biopharm contributes experience in applied biotechnology, supporting the exploration of innovative bio-based solutions relevant to food and feed safety.</p>
    <div class="partner-contact"><span class="label">Industry contact:</span> Michalina Oplatowska</div>
  </div>

  <div class="partner-card">
    <div class="partner-logo">
      <img src="{{ '/assets/images/logos/finnebrogue.png' | relative_url }}" alt="Finnebrogue">
    </div>
    <p class="partner-title">
      <span class="name">Finnebrogue</span>
      <span class="meta">(United Kingdom)</span>
    </p>
    <p class="partner-desc">Finnebrogue provides an industrial perspective on food processing and safety, contributing to the assessment of feasibility and scalability of mitigation approaches.</p>
    <div class="partner-contact"><span class="label">Industry contact:</span> [Name]</div>
  </div>

</div>

---

## International and intersectoral framework

The consortium builds on the existing network of the International Joint Research Center on Food Security (Thailand), providing a platform for long-term collaboration, staff mobility and capacity building across regions. Intersectoral and interdisciplinary collaboration is embedded through staff exchanges, expert visits and joint activities involving early-career and senior researchers, ensuring effective knowledge transfer within a highly multidisciplinary environment.
