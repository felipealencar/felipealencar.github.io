# News Drafts for Blogger

How the homepage actually uses these (see `blogger.xml` lines ~3614-3656 and `POSTING-CHEATSHEET.md`):

- **Recent News** card = post **Title** (as the link text) + post **published date** (auto, shown by Blogger). The body is *not* shown on the card — it only matters when someone clicks through. So make titles read as complete headlines.
- Labels needed: `en` + (`research` for papers/grants, `work` for career milestones).
- Add `featured` + a representative image to also surface a post in **Featured projects and papers** (title + image only, no text).
- The published date shown is whatever date the post has in Blogger. For the older 2018–2023 items, either backdate the post (Blogger lets you set "Post date" manually) or accept it'll show today's date — your call.

For each post below: copy the **Title** into Blogger's title field, copy the **Body** block into the HTML view of the editor, add the listed **Labels**, and fill in the `[ ... ]` placeholders (real links, co-author order, exact dates) before publishing — I didn't verify these against the actual DOIs/press pages.

---

## 1. USDA-NIFA GENESIS grant

**Title:** Co-PI on a $1M USDA-NIFA grant to build GENESIS, a GeoAI-enabled seed and environmental intelligence platform

**Labels:** `en`, `research`, `featured`

**Body:**
```html
<p>Excited to share that our team has been awarded a $1M grant from USDA-NIFA to develop <strong>GENESIS</strong> (DSFAS-CIN: GeoAI-Enabled Next-Generation Environmental and Seed Intelligence Platform). I'm serving as Co-PI on the project, which combines geospatial AI, remote sensing, and seed science to [one-line description of the goal — e.g., improve seed quality assessment and environmental monitoring at scale].</p>
<p>More details soon as the project kicks off. [Link to grant announcement / university press release]</p>
```

---

## 2. IEEE IGARSS 2026 paper

**Title:** Our paper "Data-Centric Phenotyping Under Scale Mismatch: A Spectral-Spatial Search Model" accepted at IEEE IGARSS 2026

**Labels:** `en`, `research`

**Body:**
```html
<p>Our paper <em>"Data-Centric Phenotyping Under Scale Mismatch: A Spectral-Spatial Search Model"</em> has been accepted at <strong>IEEE IGARSS 2026</strong>. The work tackles the scale mismatch between UAV/satellite observations and ground-truth phenotyping data with a spectral-spatial search approach.</p>
<p>[Co-authors]. See you at IGARSS! [Paper link when available]</p>
```

---

## 3. Smart Agricultural Technology — industrial hemp carbon paper

**Title:** New paper in Smart Agricultural Technology: estimating industrial hemp carbon with UAV LiDAR and hyperspectral fusion

**Labels:** `en`, `research`, `featured`

**Body:**
```html
<p>Our paper <em>"A novel approach to estimate total carbon accounting for below and above-ground carbon content of industrial hemp with UAV LiDAR and hyperspectral data fusion"</em> is now out in <strong>Smart Agricultural Technology</strong>.</p>
<p>With A. Pawar, V. Sagan, H. Alifu, K.R. Tamang, G.C. Bagnall, C. Gul, N. Shrestha, and collaborators, we fuse UAV LiDAR and hyperspectral data to estimate both above- and below-ground carbon in industrial hemp. [Paper link]</p>
```

---

## 4. Remote Sensing — soybean disease detection paper

**Title:** Self-supervised learning boosts soybean disease detection from UAV hyperspectral imagery — new paper in Remote Sensing

**Labels:** `en`, `research`

**Body:**
```html
<p>New paper out: <em>"Self-Supervised Learning for Soybean Disease Detection Using UAV Hyperspectral Imagery"</em>, published in <strong>Remote Sensing</strong> (17(23), 3928).</p>
<p>With M. Rahaman, V. Sagan, H. Alifu, C. Gul, H. Aliakbarpour, and collaborators, we show how self-supervised pretraining improves disease detection when labeled hyperspectral data is scarce. [Paper link]</p>
```

---

## 5. IEEE TGRS — Geospatial Time Machine

**Title:** Geospatial Time Machine: our generative model for enhancing spectral-temporal resolution, published in IEEE TGRS

**Labels:** `en`, `research`, `featured`

**Body:**
```html
<p>Our paper <em>"Geospatial time machine: a generative model to enhance spectral-temporal data resolution"</em> is published in <strong>IEEE Transactions on Geoscience and Remote Sensing</strong> (Vol. 63, pp. 1-13).</p>
<p>With V. Sagan, S. Sarkar, A. Stylianou, and F. Esposito, we introduce a generative approach that fills spectral and temporal gaps in satellite imagery time series — effectively letting us "look back" at moments the sensors missed. [Paper link]</p>
```

---

## 6. ICBA IWMT consultancy completed

**Title:** Wrapped up the IWMT consultancy for ICBA — a multi-language, ML-powered water management tool

**Labels:** `en`, `work`

**Body:**
```html
<p>Completed a consultancy with the <strong>International Center for Biosaline Agriculture (ICBA)</strong> on the <strong>Integrated Water Management Tool (IWMT)</strong>, delivering multi-language support and machine learning models to help [one line on what the tool does — e.g., support water management decisions in water-scarce regions].</p>
```

---

## 7. Promoted to Research Scientist at SLU

**Title:** Promoted to Research Scientist at Saint Louis University

**Labels:** `en`, `work`

**Body:**
```html
<p>I've been promoted to <strong>Research Scientist</strong> at Saint Louis University, continuing my work in the Remote Sensing Lab on GeoAI, generative models, and precision agriculture applications.</p>
```

---

## 8. PlantPlotGAN — WACV 2024

**Title:** PlantPlotGAN: our physics-informed GAN for plant disease prediction, presented at WACV 2024

**Labels:** `en`, `research`, `featured`

**Body:**
```html
<p>Presented <em>"PlantPlotGAN: A Physics-Informed Generative Adversarial Network for Plant Disease Prediction"</em> at the <strong>IEEE/CVF Winter Conference on Applications of Computer Vision (WACV) 2024</strong>.</p>
<p>With V. Sagan and F. Esposito, PlantPlotGAN embeds physical priors into a GAN to generate realistic synthetic plant plot imagery for disease prediction tasks. [Paper link] [Code link]</p>
```

---

## 9. Postdoctoral Fellow, SLU Remote Sensing Lab

**Title:** Selected as a Postdoctoral Fellow at the SLU Remote Sensing Lab

**Labels:** `en`, `work`

**Body:**
```html
<p>Starting a new chapter as a <strong>Postdoctoral Fellow</strong> at the Remote Sensing Lab at Saint Louis University, working with Dr. Vasit Sagan on GeoAI and generative modeling for agriculture and environmental monitoring.</p>
```

---

## 10. (Optional) Brazil years — retrospective

**Title:** Five years of teaching, tenure, and founding LEAD — a look back at my time as a lecturer in Brazil

**Labels:** `en`, `work`

**Body:**
```html
<p>Before moving into remote sensing research in the US, I spent five years as a lecturer at <strong>IFAL</strong> in Brazil — starting on the tenure track in 2018 and earning tenure in 2021.</p>
<p>Along the way I founded the <strong>Laboratory of Data Analysis and Engineering (LEAD)</strong> in 2020, and in 2021 we released the first version of <strong>PC2I</strong> [one line on what PC2I does]. It was also during this time that a student project analyzing public administration data for the city of Arapiraca, which I advised, was awarded at Febrace.</p>
```

---

### Not included (optional extras if you want more posts)
- *Bridging the gap between crop breeding and GeoAI* — ISPRS Journal of Photogrammetry and Remote Sensing, 2024 (co-author)
- *SoilSR: A Soil-Oriented Super-Resolution Method* — Optical Sensors, 2025 (co-author)
- *A multifaceted benchmarking of GAN architectures on generating synthetic satellite imagery* — AIPR, 2023
- AGU Fall Meeting abstracts (2024, 2025) — conference presentations, lighter weight than journal papers

Let me know if you want these turned into posts too, or want the drafts trimmed further to only 3-4 for now.
