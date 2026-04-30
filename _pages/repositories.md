---
layout: page
permalink: /repositories/
title: Models & Datasets
description: Research datasets, model outputs, and code repositories
nav: true
nav_order: 5
---

<style>
.resource-page {
  --resource-date-width: 5.5rem;
}
.resource-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin: 0 0 2rem;
}
.resource-actions a {
  border: 1px solid var(--global-divider-color);
  border-radius: 6px;
  padding: 0.35rem 0.65rem;
  text-decoration: none;
}
.resource-section {
  margin-bottom: 2.75rem;
}
.resource-section h2 {
  border-bottom: 1px solid var(--global-divider-color);
  margin-bottom: 1rem;
  padding-bottom: 0.35rem;
}
.resource-list {
  list-style: none;
  padding-left: 0;
}
.resource-list li {
  display: grid;
  grid-template-columns: var(--resource-date-width) minmax(0, 1fr);
  column-gap: 1rem;
  margin-bottom: 1.15rem;
}
.resource-year,
.resource-type {
  color: var(--global-theme-color);
  font-weight: 600;
}
.resource-title {
  font-weight: 600;
}
.resource-meta {
  color: var(--global-text-color-light);
}
.repo-grid {
  display: grid;
  gap: 1rem;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
}
.repo-card {
  border: 1px solid var(--global-divider-color);
  border-radius: 8px;
  padding: 1rem;
}
.repo-card h3 {
  font-size: 1.05rem;
  margin-bottom: 0.4rem;
}
.repo-card p {
  margin-bottom: 0.5rem;
}
@media (max-width: 575.98px) {
  .resource-list li {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="resource-page">

<div class="resource-actions">
  <a href="https://github.com/YuZHOUbiogeo?tab=repositories">GitHub repositories</a>
  <a href="https://sites.google.com/view/yu-zhou/model-and-dataset">Model &amp; Dataset archive</a>
</div>

<section class="resource-section">
  <h2>Datasets and Model Outputs</h2>
  <ol class="resource-list">
    <li>
      <div class="resource-year">2024</div>
      <div>
        <div><span class="resource-title">Global dryland phenology dataset (GDPD)</span></div>
        <div>Dong, Yuqi; Zhou, Yu; Zhang, Li; Tian, Feng; Xie, Qiaoyun; Chen, Yiyang; et al. Figshare dataset.</div>
        <div class="resource-meta"><a href="https://doi.org/10.6084/m9.figshare.27160602.v2">https://doi.org/10.6084/m9.figshare.27160602.v2</a></div>
      </div>
    </li>
    <li>
      <div class="resource-year">2021</div>
      <div>
        <div><span class="resource-title">Forest Carbon Stocks and Fluxes from the NFCMS, Conterminous USA, 1990-2010</span></div>
        <div>Williams, C.A., N. Hasler, H. Gu, and Y. Zhou. ORNL DAAC, Oak Ridge, Tennessee, USA.</div>
        <div class="resource-meta"><a href="https://doi.org/10.3334/ORNLDAAC/1829">https://doi.org/10.3334/ORNLDAAC/1829</a></div>
      </div>
    </li>
    <li>
      <div class="resource-year">2019</div>
      <div>
        <div><span class="resource-title">ACT-America: Gridded Ensembles of Surface Biogenic Carbon Fluxes, 2003-2017</span></div>
        <div>Zhou, Yu, C.A. Williams, T. Lauvaux, S. Feng, I.T. Baker, Y. Wei, A.S. Denning, K. Keller, and K.J. Davis. ORNL DAAC, Oak Ridge, Tennessee, USA.</div>
        <div class="resource-meta"><a href="https://doi.org/10.3334/ORNLDAAC/1675">https://doi.org/10.3334/ORNLDAAC/1675</a></div>
      </div>
    </li>
    <li>
      <div class="resource-year">2020</div>
      <div>
        <div><span class="resource-title">Ensemble model output of North American atmospheric CO2 simulations for summer 2016</span></div>
        <div>Feng, S., T. Lauvaux, C.A. Williams, K.J. Davis, Y. Zhou, I. Baker, Z.R. Barkley, and D. Wesloh. Data Commons.</div>
        <div class="resource-meta"><a href="https://doi.org/10.26208/z864-qk73">https://doi.org/10.26208/z864-qk73</a></div>
      </div>
    </li>
    <li>
      <div class="resource-year">2019</div>
      <div>
        <div><span class="resource-title">Forest Carbon Stocks and Fluxes After Disturbance, Southeastern USA, 1990-2010</span></div>
        <div>Gu, H., C.A. Williams, N. Hasler, and Y. Zhou. ORNL DAAC, Oak Ridge, Tennessee, USA.</div>
        <div class="resource-meta"><a href="https://doi.org/10.3334/ORNLDAAC/1728">https://doi.org/10.3334/ORNLDAAC/1728</a></div>
      </div>
    </li>
    <li>
      <div class="resource-year">Data</div>
      <div>
        <div><span class="resource-title">Ensemble model output of North American atmospheric CO2 simulation, full WRF-Chem output</span></div>
        <div>Sha Feng, Thomas Lauvaux, Kenneth J. Davis, Klaus Keller, Peter Rayner, Tomohiro Oda, Kevin R. Gurney, Yu Zhou, Christopher Williams, Andrew E. Schuh, Junjie Liu, and Ian Baker. Penn State Data Commons.</div>
        <div class="resource-meta"><a href="https://doi.org/10.26208/7a4p-q224">https://doi.org/10.26208/7a4p-q224</a></div>
      </div>
    </li>
  </ol>
</section>

<section class="resource-section">
  <h2>Code Repositories</h2>
  <div class="repo-grid">
    <article class="repo-card">
      <h3><a href="https://github.com/YuZHOUbiogeo/HDA4ForestCarbon">HDA4ForestCarbon</a></h3>
      <p>R code repository for hierarchical data assimilation and forest carbon modeling.</p>
      <p class="resource-meta">Language: R. Original repository under YuZHOUbiogeo.</p>
    </article>
    <article class="repo-card">
      <h3><a href="https://github.com/YuZHOUbiogeo/NDVI-residual">NDVI-residual</a></h3>
      <p>Code repository related to NDVI residual analysis.</p>
      <p class="resource-meta">Original repository under YuZHOUbiogeo.</p>
    </article>
  </div>
</section>

</div>