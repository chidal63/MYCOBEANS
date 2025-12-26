---
title: "Secondments"
permalink: /secondments/
layout: single
classes: wide
sidebar: false
toc: false
---

<style>
/* --- Left rail (uses the page’s empty 1/4 column conceptually) --- */
.rail-layout{
  display: grid;
  grid-template-columns: minmax(220px, 1fr) minmax(0, 3fr);
  gap: 18px;
  align-items: start;
  margin-top: 1.2rem;
}
@media (max-width: 980px){
  .rail-layout{ grid-template-columns: 1fr; }
}

/* Left box */
.rail-box{
  border: 1px solid rgba(0,0,0,.10);
  border-radius: 14px;
  padding: 14px 14px 12px 14px;
  background: rgba(0,0,0,.02);
  position: sticky;
  top: 1rem;
}
@media (max-width: 980px){
  .rail-box{ position: static; }
}
.rail-box h4{
  margin: 0 0 8px 0;
  font-size: 1.0rem;
  font-weight: 700;
}
.rail-box p{
  margin: 0 0 8px 0;
  font-size: .95rem;
  line-height: 1.4;
}
.rail-box a{ font-weight: 650; }
.rail-note{
  font-size: .85rem;
  color: rgba(0,0,0,.70);
}

/* At-a-glance summary box */
.at-a-glance{
  margin: 1.8rem 0 2.2rem 0;
  padding: 1.1rem 1.2rem;
  border: 1px solid rgba(0,0,0,.10);
  border-radius: 14px;
  background: rgba(0,0,0,.02);
}
.at-a-glance h3{
  margin: 0 0 .6rem 0;
  font-size: 1.05rem;
  font-weight: 700;
}
.at-a-glance ul{
  margin: 0;
  padding-left: 1.1rem;
}
.at-a-glance li{ margin: .35rem 0; }
.at-a-glance .note{
  margin-top: .8rem;
  font-size: .88rem;
  color: rgba(0,0,0,.70);
}

/* Representative examples */
.small-note{
  margin-top: 10px;
  font-size: .9rem;
  color: rgba(0,0,0,.70);
}

/* Examples grid (full-width within the 3/4 content column) */
.examples{
  margin: 1.0rem 0 0 0;
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
}
@media (max-width: 980px){ .examples{ grid-template-columns: repeat(2, minmax(0, 1fr)); } }
@media (max-width: 620px){ .examples{ grid-template-columns: 1fr; } }

.example-card{
  border: 1px solid rgba(0,0,0,.10);
  border-radius: 14px;
  padding: 14px 14px 12px 14px;
  background: #fff;
}
.example-card h4{
  margin: 0 0 8px 0;
  font-size: 1.0rem;
  font-weight: 750;
  min-height: 2.4em; /* aligns titles across cards */
}
.kv{
  margin: 0 0 8px 0;
  font-size: .94rem;
  line-height: 1.35;
  color: rgba(0,0,0,.80);
}
.kv .k{
  font-weight: 600;
  color: rgba(0,0,0,.85);
}
.example-card .kv + .kv{ margin-top: 6px; }

.example-card ul{
  margin: 6px 0 0 0;
  padding-left: 1.1rem;
}
.example-card li{ margin: .22rem 0; }
</style>

<div class="rail-layout">

  <aside class="rail-box">
    <h4>Hear from our secondees</h4>
    <p>
      Short testimonies from researchers involved in MYCOBEANS secondments,
      describing interdisciplinary and intersectoral mobility experiences.
    </p>
    <p>
      <a href="ZENODO_LINK_HERE" target="_blank" rel="noopener">
        Watch the video on Zenodo →
      </a>
    </p>
    <p class="rail-note">
      The video is hosted on Zenodo as a public project resource.
    </p>
  </aside>

  <div>

## Mobility patterns

### A1. Interdisciplinary mobility (core activity)

Interdisciplinary mobility is the core secondment activity in MYCOBEANS.  
The project implements short-term exchanges connecting complementary scientific domains involved in mycotoxin risk assessment in legumes.

Mobility activities primarily involve **early-career researchers** moving between academic institutions in Europe, the United Kingdom and ASEAN countries, enabling hands-on cross-disciplinary learning. **Senior researchers** are involved selectively when advanced methodological alignment or strategic integration across disciplines is required.

Interdisciplinary mobility is organised around recurrent exchange patterns, supporting cumulative capacity building and a shared methodological language across the consortium.

---

### A2. Intersectoral mobility (technology transfer–oriented)

Intersectoral mobility supports **targeted transfer of technology and applied know-how** between academia and non-academic partners.

These secondments are **short and tightly scoped**, focusing on method implementation, workflow adaptation and feasibility assessment under real-world constraints. Intersectoral mobility complements interdisciplinary exchanges by anchoring scientific developments to applied and industrial contexts.

---

### A3. Applied research organisations

MYCOBEANS includes mobility involving **applied research and technology transfer organisations** operating at the interface between academic research and industrial application.

These organisations act as **bidirectional hubs**, hosting early-career researchers for applied training and supporting senior-level exchanges focused on validation, optimisation and technology adaptation.

---

<div class="at-a-glance">
  <h3>At a glance — Secondments in MYCOBEANS</h3>
  <ul>
    <li><strong>Mobility patterns:</strong> interdisciplinary · intersectoral · applied research</li>
    <li><strong>Geographical scope:</strong> Europe · United Kingdom · ASEAN countries</li>
    <li><strong>Career stages involved:</strong> predominantly early-career, with targeted senior mobility</li>
    <li><strong>Scientific domains bridged:</strong> analytical chemistry · toxicology · molecular biology · bioinformatics · food science · food processing</li>
    <li><strong>Typical duration:</strong> short-term, objective-driven stays</li>
  </ul>
  <div class="note"><strong>Mobility volume:</strong> <em>to be added</em> (reported as person-months).</div>
</div>

---

## Representative examples

<div class="small-note">
The examples below illustrate representative mobility patterns implemented in MYCOBEANS and are not intended as an exhaustive list of individual secondments.
</div>

<div class="examples">

  <div class="example-card">
    <h4>Example 1 — Interdisciplinary mobility</h4>
    <p class="kv"><span class="k">From → To:</span> University of Parma (IT) → Thammasat University (TH)<br>
    <span class="k">Career stage:</span> Early-career researcher<br>
    <span class="k">Typical duration:</span> Short-term</p>
    <p class="kv"><span class="k">Focus:</span> Integrating analytical workflows with occurrence data generated in different contexts.</p>
    <ul>
      <li>cross-training in methods and interpretation</li>
      <li>alignment of workflows across institutions</li>
      <li>contribution to shared consortium practices</li>
    </ul>
  </div>

  <div class="example-card">
    <h4>Example 2 — Applied research hub</h4>
    <p class="kv"><span class="k">From → To:</span> Universities ↔ NSTDA-BIOTEC (TH)<br>
    <span class="k">Career stage:</span> Early-career and senior researchers<br>
    <span class="k">Typical duration:</span> Short- to medium-term</p>
    <p class="kv"><span class="k">Focus:</span> Validation, optimisation and adaptation of methods under operational and regulatory constraints.</p>
    <ul>
      <li>method validation and workflow optimisation</li>
      <li>bidirectional knowledge transfer (EU ↔ ASEAN)</li>
      <li>translation of research into implementable tools</li>
    </ul>
  </div>

  <div class="example-card">
    <h4>Example 3 — Intersectoral technology transfer</h4>
    <p class="kv"><span class="k">From → To:</span> UNIPR / industrial partner → applied research organisation (TH)<br>
    <span class="k">Career stage:</span> Early-career (industrial doctorate)<br>
    <span class="k">Typical duration:</span> Medium-term</p>
    <p class="kv"><span class="k">Focus:</span> Food processing knowledge transferred across academic, applied and industrial environments.</p>
    <ul>
      <li>integration of processing into applied workflows</li>
      <li>alignment with industrial constraints</li>
      <li>consolidation of technology transfer pathways</li>
    </ul>
  </div>

</div>

  </div>
</div>
