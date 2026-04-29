---
layout: page
title: News
permalink: /news/
nav: true
nav_order: 1
---
<!-- <ul class="news-subitems">
  <li>
    <p>First news paragraph.</p>
  </li>
  <li>
    <p>Second news paragraph with <a href="https://example.com">an embedded link</a>.</p>

    <p>Optional second paragraph inside the same arrow item.</p>
  </li>
</ul> -->


<style>
.news-timeline {
  position: relative;
  margin-top: 1.5rem;
}
.news-timeline::before {
  content: "";
  position: absolute;
  top: 0.25rem;
  bottom: 0;
  left: 8rem;
  width: 2px;
  background: var(--global-divider-color);
}
.news-timeline-item {
  position: relative;
  display: grid;
  grid-template-columns: 6.5rem minmax(0, 1fr);
  gap: 2.75rem;
  margin-bottom: 2.5rem;
}
.news-timeline-date {
  position: sticky;
  top: 5rem;
  align-self: start;
  color: var(--global-theme-color);
  font-weight: 600;
  line-height: 1.2;
  text-align: right;
}
.news-timeline-date::after {
  content: "";
  position: absolute;
  top: 0.25rem;
  right: -1.95rem;
  width: 0.8rem;
  height: 0.8rem;
  border-radius: 50%;
  background: var(--global-theme-color);
  border: 3px solid var(--global-bg-color);
  box-shadow: 0 0 0 1px var(--global-divider-color);
}
.news-subitems {
  list-style: none;
  padding-left: 0;
  margin-bottom: 0;
}

.news-subitems > li {
  position: relative;
  padding-left: 1.75rem;
  margin-bottom: 1.25rem;
}

.news-subitems > li::before {
  content: "\2192";
  position: absolute;
  left: 0;
  top: 0;
  color: var(--global-theme-color);
  font-size: 1.15rem;
  font-weight: 700;
  line-height: 1.5;
}

.news-subitems > li p {
  margin-bottom: 0.75rem;
}

.news-subitems > li > :last-child {
  margin-bottom: 0;
}

.news-subitems .news-detail-list {
  margin: 0.5rem 0 0;
  padding-left: 1.1rem;
}

.news-subitems .news-detail-list li {
  margin-bottom: 0.35rem;
}

.news-timeline-content {
  min-width: 0;
}
.news-timeline-content img {
  max-width: 70%;
  max-height: 320px;
  object-fit: contain;
  background: var(--global-bg-color);
}

@media (max-width: 575.98px) {
  .news-timeline::before {
    left: 0.4rem;
  }
  .news-timeline-item {
    grid-template-columns: 1fr;
    gap: 0.5rem;
    padding-left: 1.75rem;
  }
  .news-timeline-date {
    position: relative;
    top: auto;
    text-align: left;
  }
  .news-timeline-date::after {
    left: -1.75rem;
    right: auto;
  }
}
</style>

<div class="news-timeline"><section class="news-timeline-item">
  <div class="news-timeline-date">2026 April</div>
  <div class="news-timeline-content" markdown="1">

I attended a workshop to discuss the progress of WG3 of <a href="https://cleanforest.eu/">CLEANFOREST COST Action</a>. It was also my second time visit to the <a href="https://anaee.fi/facility/hyytiala-smear-ii/">Hyytiälä SMEAR II LTER Site</a>.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2026 March</div>
  <div class="news-timeline-content" markdown="1">

Wonder how trees in dryland use water during the dry periods? We show that hydraulic redistribution declines as precipitation becomes larger and more frequent, highlighting its key role during dry spells. A data-model fusion approach improves soil moisture predictions in drylands. Here is the <a href="http://bg.copernicus.org/articles/23/2045/2026/">link</a> to this new Biogeosciences paper!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2026 January</div>
  <div class="news-timeline-content" markdown="1">

At the Swiss Forest Lab Science Day in Bern, I gave a talk about our recent work on the drivers of gross primary productivity (GPP) changes in European ecosystems over the past two decades. I was happy to meet so many colleagues at the beginning of 2026!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2025 December</div>
  <div class="news-timeline-content" markdown="1">

At ETH Zurich in Prof. Nina Buchmann's group, we are launching two initiatives focused on applying machine learning (ML) and artificial intelligence (AI) to understand carbon and water fluxes. Each initiative has about ten participants. Stay tuned!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2025 October</div>
  <div class="news-timeline-content" markdown="1">

Science paper <a href="https://www.science.org/doi/10.1126/science.adv7104">"Drought-induced peatland carbon loss exacerbated by elevated CO2 and warming"</a> by Quan et al. is now online! See more from <a href="https://news.cornell.edu/stories/2025/10/peatlands-huge-reservoir-carbon-risk-release">Cornell News</a> and <a href="https://research.gatech.edu/peatlands-huge-reservoir-carbon-risk-release">Georgia Tech News</a>!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2025 July</div>
  <div class="news-timeline-content" markdown="1">

<ul class="news-subitems">
  <li>
    <p>Our paper, "Drought-induced peatland carbon loss exacerbated by elevated CO2 and warming", has been accepted by Science! Thanks to Quan for leading this fantastic work!</p>
  </li>
  <li>
    <p>Our paper, "<a href="https://www.nature.com/articles/s41597-025-05519-2?utm_source=rct_congratemailt&utm_medium=email&utm_campaign=oa_20250709&utm_content=10.1038/s41597-025-05519-2">An Enhanced Phenology Dataset for Global Drylands from 2001 to 2019</a>", is now online on Scientific Data. We present the Global Dryland Phenology Dataset (GDPD) for 2001-2019, covering 88.4% of global drylands, which compensates for missing regions in other products.</p>

    <p>If you are looking for a dryland phenology dataset for your future work, please consider our dataset and access it via our <a href="https://figshare.com/articles/dataset/Global_dryland_phenology_dataset_GDPD_/27160602/2">open-source repository</a>!</p>
  </li>
</ul>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2025 June</div>
  <div class="news-timeline-content" markdown="1">

<ul class="news-subitems">
  <li>
    <img src="{{ '/assets/img/news/Yiqiluo.png' | relative_url }}" alt="Nature Geoscience figure" class="img-fluid rounded z-depth-1 mb-3">

    <p>Our paper, "<a href="https://www.nature.com/articles/s41561-025-01731-2">Large CO2 removal potential of woody debris preservation in managed forests</a>", is now available online at Nature Geoscience. One key message is that To Slow Global Warming, Bury Wood Debris, as the headline from <a href="https://news.cornell.edu/stories/2025/06/slow-global-warming-bury-wood-debris">Cornell News</a>. Our study shows that burying this woody biomass over the next 76 years could remove between 770 and 937 gigatons of CO2 from the atmosphere, or between 10.1 and 12.3 gigatons of CO2 per year.</p>

    <p>"Based on my knowledge, this is the most effective and the least expensive-and possibly the most sustainable-way to capture carbon," said study first author and Cornell University researcher Yiqi Luo. "There's huge potential."</p>
  </li>
  <li>
    <p>Our group attended the 1st eLTER meeting in Tampere. I presented the work "Interactive Effect of Nitrogen Deposition and Drought on Forest Carbon Sequestration" with data from 47 ICOS+FLUXNET sites.</p>

    <p>We also visited the <a href="https://anaee.fi/facility/hyytiala-smear-ii/">Hyytiälä SMEAR II LTER Site</a>, which included a forest site (pine) and a peatland site.</p>

    <p>We also enjoyed the daylight in summer and the sauna in Finland!</p>
  </li>
</ul>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2025 May</div>
  <div class="news-timeline-content" markdown="1">

We visited the <a href="https://www.hfsjg.ch/en/home/">High Altitude Research Stations at Jungfraujoch and Gornergrat</a>! Greenhouse gas concentrations at Jungfraujoch are continuously rising and air temperature has already risen by 2.1 °C between the pre-industrial period 1871-1900 and now (1994-2023).

The observation facilities are impressive and the views are breathtaking! Many thanks to Kukkis and the local scientists and staff for organizing this fantastic trip!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2025 March</div>
  <div class="news-timeline-content" markdown="1">

<ul class="news-subitems">
  <li>
    <p>It was very nice to meet many collaborators at the 3rd CLEANFOREST meeting and to visit Warsaw and field sites in Kampinos National Park! Many thanks to the organizers and local park staff!</p>
  </li>
  <li>
    <p>Using a hierarchical assimilation framework, we found that our community needs more than just live biomass to improve process-based models. We call for more measurements of dead biomass and soil carbon to better support modelers!</p>

    <p>Our paper, "Forest Carbon Modeling Improved Through Hierarchical Assimilation of Pool-Based Measurements," is now (finally!) <a href="https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2024MS004622">online</a> on JAMES!</p>
  </li>
</ul>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2025 February</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/elephants.png' | relative_url }}" alt="elephants" class="img-fluid rounded z-depth-1 mb-3">

I am happy to give a talk at the Grassland Seminar at ETH Zurich to introduce my previous work on "Improved estimation of forest carbon dynamics via model-data fusion."

Side story: Do you know how much 100 Gt CO2 (the carbon we need to remove from the atmosphere by 2100) is?

It equals the weight of 20 billion elephants! (Generated by ChatGPT)

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2024 December</div>
  <div class="news-timeline-content" markdown="1">

Get ready for AGU2024 @DC! My colleagues and I will be presenting at the oral and poster sessions! Here is the list:

- Friday, 13, 09:10 - 09:20, 150 B (Convention Center), B51A-05: AI-powered interpretation of dryland carbon dynamics
- Monday, 13:40 - 17:30, Hall B-C: Community Trait Synergy Enhances Dryland Ecosystem Productivity and Stability
- Thursday, 08:30 - 12:20, Hall B-C: The fate of peatland carbon interactively determined by elevated carbon dioxide and warming
- Monday, 13:40 - 17:30, Hall B-C: Hydraulic Redistribution Decreases with Precipitation in a Dryland Ecosystem
- Monday, 13:40 - 17:30, Hall B-C: A framework monitoring carbon in forest ecosystems and wood products: a case study in the Howland Forest, Maine

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2024 September</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/ETH.png' | relative_url }}" alt="ETH Zurich" class="img-fluid rounded z-depth-1 mb-3">

I have moved to ETH Zurich to start my Research Associate position in Prof. Dr. Nina Buchmann's group.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2024 June</div>
  <div class="news-timeline-content" markdown="1">

Glad to be the instructor of the 7th training course on New Advances in Land Carbon Cycle Modeling. We will have Hybrid Virtual + in Person this year! Check out more details about this course: <a href="https://ecolab.cals.cornell.edu/?workshop">https://ecolab.cals.cornell.edu/?workshop</a>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2023 December</div>
  <div class="news-timeline-content" markdown="1">

Get ready for AGU2023!

We host an oral session on Friday from 16:00 - 17:30 PST in 2006 - West (Level 2, West, MC) GC54B - Bridging Science and Policy for Effective Climate Mitigation and Sustainable Carbon Neutrality II Oral. The poster session is from 8:30 - 12:50 PST on Friday at Poster Hall A-C - South (Exhibition Level, South, MC).

My collaborators and I have several presentations:

- Zhou et al. B43H-2646 Convergent Pattern of Plant Strategies in Varied Dryness Conditions. December 14, 14:10 - 18:30 PST, Poster Hall A-C - South (Exhibition Level, South, MC).
- Chandel et al. B43G-2634 Investigating the Role of Hydraulic Redistribution on Water and Carbon Cycle in Dryland Ecosystems: Empirical and Modeling Approaches. December 14, 14:10 - 18:30 PST, Poster Hall A-C - South (Exhibition Level, South, MC).
- Luo et al. GC54B-09 Preserving wood debris towards net-zero carbon emission. December 15, 17:12 - 17:21 PST, 2006 - West (Level 2, West, MC).
- Zhou et al. B44A-05 Interactive effect of elevated CO2 and warming on the carbon cycle in a boreal peatland. December 14, 16:44 - 16:55 PST, 3008 - West (Level 3, West, MC).
- Wang et al. H13J-1574 Trait mechanisms of plant community response and adaptation to drought in arid-semi-arid grassland of Northern China. December 11, 14:10 - 18:30 PST, Poster Hall A-C - South (Exhibition Level, South, MC).
- Ruehr et al. GC21H-1009 Attribution and evidence for historic enhancement of the land carbon sink. December 12, 08:30 - 12:50 PST, Poster Hall A-C - South (Exhibition Level, South, MC).
- Dong et al. Intensive Land-use Led to Trade-offs of Sustainable Development Goals in Port Cities of Southeast Asia. 24 January 2024, 08:00 - 09:30 PST, GC07 - Online Poster Session for Global Environmental Change: Urban XV.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2023 July</div>
  <div class="news-timeline-content" markdown="1">

<ul class="news-subitems">
  <li>
    <p>Call for abstract! Working on Carbon Dioxide Removal? Developing innovative approaches? Evaluating current CDRs for broader application? Submit your work to #AGU2023 Session GC063 - Leveraging Multifaceted Approaches to Carbon Dioxide Removal for Effective Climate Change Mitigation: <a href="https://agu.confex.com/agu/fm23/prelim.cgi/Session/185033">https://agu.confex.com/agu/fm23/prelim.cgi/Session/185033</a></p>
  </li>
  <li>
    <img src="{{ '/assets/img/news/43017_2023_456_Fig3_HTML.webp' | relative_url }}" alt="2023 July Nature Reviews Earth & Environment figure" class="img-fluid rounded z-depth-1 mb-3">

    <p>Thrilled to share our new paper in Nature Reviews Earth & Environment! Here, we look into the past to help the future. Evidence and attribution of the enhanced land carbon sink. Full text link: <a href="https://www.nature.com/articles/s43017-023-00456-3">https://www.nature.com/articles/s43017-023-00456-3</a></p>
  </li>
  <li>
    <p>How do we manipulate both the mean and variance of precipitation? Check out our paper about the Sevilleta experiments on the dryland ecosystems in Ecosphere: Infrastructure to factorially manipulate the mean and variance of precipitation in the field.</p>
  </li>
</ul>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2023 June</div>
  <div class="news-timeline-content" markdown="1">

Glad to be the instructor of the 6th training course on New Advances in Land Carbon Cycle Modeling. We will have Hybrid Virtual + in Person this year! Check out more details about this course: <a href="https://ecolab.cals.cornell.edu/?workshop">https://ecolab.cals.cornell.edu/?workshop</a>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2023 March</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/portcity2.jpg' | relative_url }}" alt="Port cities" class="img-fluid rounded z-depth-1 mb-3">

Our new results about how land use is associated with development status in port cities. Check out why these cities are important, how they have evolved in the past decades, and what they are expected to experience in the next several decades!

It is now <a href="https://iopscience.iop.org/article/10.1088/1748-9326/acc2d2">online</a> in Environmental Research Letters!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2023 February</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/enqinghou.jpg' | relative_url }}" alt="Model uncertainty" class="img-fluid rounded z-depth-1 mb-3">

Model uncertainty comes from various sources, and different models may agree or disagree with each other due to these uncertainty sources. Check out how we pinned down the sources of across-model spread!

This work is <a href="https://onlinelibrary.wiley.com/doi/10.1111/gcb.16643">online</a> in Global Change Biology now!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2023 January</div>
  <div class="news-timeline-content" markdown="1">

<ul class="news-subitems">
  <li>
    <p>Our group attended SEV all-hands meeting in Albuquerque, presented ModEx results, and visited the nice field experiment sites!</p>
  </li>
  <li>
    <img src="{{ '/assets/img/news/MVE.jpg' | relative_url }}" alt="MVE" class="img-fluid rounded z-depth-1 mb-3">

    <p>I am thrilled to join the first cohort of the Eric and Wendy Schmidt AI in Science at Cornell University! Check out this <a href="https://science.ai.cornell.edu/">website</a> to explore 2023 postdoc fellowship openings!</p>
  </li>
</ul>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2022 December</div>
  <div class="news-timeline-content" markdown="1">

AGU presentations:

- Improved Estimates of Carbon and Water Dynamics by TECO-Dryland and Data Assimilation. Yu Zhou (presenting author).
- The Biogeochemical Model Database bgc_md2, a Python Package for Fast Comparison and Benchmarking of Element Cycling Models. Markus Müller (presenting author).
- Towards reducing uncertainty in land carbon predictions through the Global Matrix MIP traceability framework. Kostiantyn Viatkin (presenting author).
- How can we use comprehensive ensembles to improve regional carbon flux estimation? Sha Feng (presenting author).

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2022 August</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/cornell.png' | relative_url }}" alt="cornell" class="img-fluid rounded z-depth-1 mb-3" style="max-width: 50%; max-height: 300px;">

I moved to Ithaca and started my new position as a postdoctoral associate at Cornell University!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2022 May</div>
  <div class="news-timeline-content" markdown="1">

I will be the instructor of the 5th training course on New Advances in Land Carbon Cycle Modeling. We will have Hybrid Virtual + in Person this year! Check out more details about this course: <a href="https://www2.nau.edu/luo-lab/?workshop">https://www2.nau.edu/luo-lab/?workshop</a>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2021 November</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/Sharon Gourdji.jpg' | relative_url }}" alt="VPRM" class="img-fluid rounded z-depth-1 mb-3">

Check out our new paper led by Dr. Sharon Gourdji. This work introduces a modified Vegetation Photosynthesis and Respiration Model that is relatively unbiased and better explains hourly atmospheric CO2 variability compared to other biosphere models.

It's available on <a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2021JG006290">JRG-Biogeosciences</a> now!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2021 July-August-September</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/NAU.png' | relative_url }}" alt="NAU" class="img-fluid rounded z-depth-1 mb-3">

Back in Worcester! Completed my doctoral degree! Moved to Flagstaff, and I am ready to start my postdoc at Northern Arizona University!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2021 June</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/NFCMSdata.png' | relative_url }}" alt="NFCMSdata" class="img-fluid rounded z-depth-1 mb-3">

Our NFCMS dataset is available now! Check out <a href="https://doi.org/10.3334/ORNLDAAC/1829">https://doi.org/10.3334/ORNLDAAC/1829</a>.

It provides estimates of forest carbon stocks and fluxes in the form of aboveground woody biomass (AGB), total live biomass, total ecosystem carbon, aboveground coarse woody debris (CWD), and net ecosystem productivity (NEP) as a function of the number of years since the most recent disturbance (i.e., stand age) for forests of the conterminous U.S. at a 30 m resolution for the benchmark years 1990, 2000, and 2010. Have fun exploring it!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2021 March</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/NFCMS.jpg' | relative_url }}" alt="NFCMS" class="img-fluid rounded z-depth-1 mb-3">

We evaluated the National Forest Carbon Monitoring System (NFCMS), which combines forest inventory data, satellite remote sensing of stand biomass and forest disturbances, and an ecosystem carbon cycle model, to show its potential to serve as a candidate monitoring, reporting and verification (MRV) system, informed by field and remotely sensed inventories, and tracking the carbon balance of the forest sector across the United States.

Our paper, "Beyond biomass to carbon fluxes: application and evaluation of a comprehensive Forest Carbon Monitoring System" is <a href="https://iopscience.iop.org/article/10.1088/1748-9326/abf06d">online</a> in Environmental Research Letters!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2020 December</div>
  <div class="news-timeline-content" markdown="1">

<ul class="news-subitems">
  <li>
    <p>We have two presentations at the AGU fall meeting this year. Check this out!</p>

    <ul class="news-detail-list">

      <li>Abstract ID# 743618: Matrix MIP to trace uncertainty in predicting land carbon dynamics lead by Enqing Hou from NAU.</li>

      <li>Abstract ID# 740452: Constraint of terrestrial model parameters from ensemble forward simulations lead by Sha Feng from PSU.</li>

    </ul>
  </li>
  <li>
    <p>Our dataset "Ensemble model output of North American atmospheric CO2 simulations for summer 2016, including transport, CASA and CT2017, and boundary condition ensembles" is available on <a href="https://www.datacommons.psu.edu/commonswizard/MetadataDisplay.aspx?Dataset=6278">Penn State Data Commons</a> now! The resulting "super ensemble" of modeled [CO2] demonstrates that the biosphere introduces the majority of uncertainty to the simulations and that biogenic [CO2] can be lifted by the fronts beyond the top of the atmospheric boundary layer.</p>
  </li>
</ul>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2020 November</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/fungi.webp' | relative_url }}" alt="Fungi" class="img-fluid rounded z-depth-1 mb-3">

Our paper, "Species diversity with comprehensive annotations of wood-inhabiting poroid and corticioid fungi in Uzbekistan," is <a href="https://www.frontiersin.org/journals/microbiology/articles/10.3389/fmicb.2020.598321/full">online</a> in Frontiers in Microbiology - Fungi and Their Interactions! This work is based on 790 fungal occurrence records: 185 from recently collected specimens, 101 from herbarium specimens made by earlier collectors, and 504 from literature-based records.

I really enjoyed my collaboration with the fungi group!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2020 August</div>
  <div class="news-timeline-content" markdown="1">

Welcome back to another year at Clark!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2020 July</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/CASA_earthdata.jpg' | relative_url }}" alt="2020 July news photo" class="img-fluid rounded z-depth-1 mb-3">

NASA Earth Data features our team's surface biogenic CO2 exchanges simulated for North America, generated as part of the NASA ACT-America campaign. The featured zoom shows contrasting carbon source/sink patterns across pasturelands and croplands from Oklahoma to Tennessee. Data are available at the ORNL DAAC. More on ACT-America can be found at <a href="https://www-air.larc.nasa.gov/missions/ACT-America/index.html">https://www-air.larc.nasa.gov/missions/ACT-America/index.html</a>.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2020 February</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/JGR-B_TD.png' | relative_url }}" alt="2020 February Taylor diagram" class="img-fluid rounded z-depth-1 mb-3">

We introduce a new perturbed-parameter model ensemble with the CASA model to estimate surface biogenic carbon fluxes at monthly and 3-hourly scales for North America at ~500-m and 5-km resolutions.

Our paper, "A Multiyear Gridded Data Ensemble of Surface Biogenic Carbon Fluxes for North America: Evaluation and Analysis of Results", is <a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2019JG005314">online</a> in JGR-Biogeosciences. The dataset is available on ORNL DAAC <a href="https://doi.org/10.3334/ORNLDAAC/1675">https://doi.org/10.3334/ORNLDAAC/1675</a>.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2020 January</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/WUE.jpg' | relative_url }}" alt="WUE" class="img-fluid rounded z-depth-1 mb-3">

We used a data-driven (or machine learning) approach, along with observations from a number of FLUXNET sites and spatially continuous satellite and meteorological data, to generate gridded carbon and water flux estimates for semi-arid regions globally, and then examined the magnitude, spatial patterns, and trends of carbon and water fluxes and their responses to climate change during the period 1982-2015.

Our paper "Increased carbon uptake and water use efficiency in global semi-arid ecosystems" is <a href="https://iopscience.iop.org/article/10.1088/1748-9326/ab68ec">online</a> in Environmental Research Letters.

Happy new year and welcome to the 2020s!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2019 December</div>
  <div class="news-timeline-content" markdown="1">

<ul class="news-subitems">
  <li>
    <img src="{{ '/assets/img/news/fengsha.jpg' | relative_url }}" alt="ACT" class="img-fluid rounded z-depth-1 mb-3">

    <p>We merge top-down and bottom-up approaches with an ensemble-based, regional modeling system able to diagnose and quantify the causes of uncertainties in top-down atmospheric estimates of the terrestrial sink over North America. Our ensemble approach quantifies and partitions the uncertainty stemming from atmospheric transport, the biosphere, and large-scale CO2 boundary inflow (boundary conditions).</p>

    <p>Our paper, "Seasonal characteristics of model uncertainties from biogenic fluxes, transport, and large-scale boundary inflow in atmospheric CO2 simulations over North America", is <a href="https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2019JD031165">online</a> in JGR-Atmospheres.</p>
  </li>
  <li>
    <p>I will attend the 2019 AGU fall meeting at San Francisco, CA. I will present our recent work: Linking Biomass Data with Carbon Cycle Modeling in Session B13H - Complexity and Emergent Behavior in the Terrestrial Carbon Sink II Posters.</p>

    <p>Dr. Williams will present Carbon, Climate, and US Forests: Synthesis of Harvesting, Wood Products, Deforestation, Reforestation, and Natural Disturbance Impacts in Session B027 - Carbon Monitoring Systems Research and Applications.</p>
  </li>
</ul>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2019 August</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/Huangu.jpg' | relative_url }}" alt="SEforest" class="img-fluid rounded z-depth-1 mb-3">

We estimate annual carbon stocks and fluxes in southeastern U.S. forests at 30 m with remote sensing, inventory data and a carbon cycle model. We analyzed the trends and regional greenhouse gas exchange.

Our paper, "The Carbon Balance of the Southeastern U.S. Forest Sector as Driven by Recent Disturbance Trends", is online in JGR - Biogeosciences! Find the data here <a href="https://doi.org/10.3334/ORNLDAAC/1728">https://doi.org/10.3334/ORNLDAAC/1728</a>!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2019 April</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/Biome-BGC MuSo.webp' | relative_url }}" alt="Biome-BGC MuSo" class="img-fluid rounded z-depth-1 mb-3">

We improved the estimations of soil-related processes in Biome-BGC MuSo by assimilating ground-measured multi-layer daily soil temperature and moisture at the Changbai Mountains forest flux site by using the Ensemble Kalman Filter algorithm.

Our paper, "Improved simulation of carbon and water fluxes by assimilating multi-layer soil temperature and moisture into process-based biogeochemical model", is <a href="https://forestecosyst.springeropen.com/articles/10.1186/s40663-019-0171-5">online</a> in Forest Ecosystems.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2018 December</div>
  <div class="news-timeline-content" markdown="1">
<ul class="news-subitems">
  <li>
    <img src="{{ '/assets/img/news/stone.jpg' | relative_url }}" alt="Central Asia" class="img-fluid rounded z-depth-1 mb-3">

    <p>Our paper, "Spatiotemporal transition of institutional and socioeconomic impacts on vegetation productivity in Central Asia over last three decades," is available <a href="https://www.sciencedirect.com/science/article/pii/S0048969718350009">online</a> in Science of The Total Environment!</p>

    <p>The findings highlight the spatiotemporal changes of institutional and socioeconomic impacts on vegetation productivity in Central Asian drylands and provide implications for future dryland management and restoration efforts.</p>
  </li>
  <li>
    <p>I will attend the 2018 AGU fall meeting in DC, Washington. I will present our recent work: A multi-year gridded data product of surface biogenic carbon fluxes for North America: Evaluation and analysis of results, Y Zhou, CA Williams, T Lauvaux, S Feng, K Keller, KJ Davis in the Session B41J: Advances in Uncertainty Assessment and Reduction for Terrestrial Carbon Cycle Diagnosis and Prediction II Posters, Location: Convention Center; Hall A-C (Poster Hall). Look forward to seeing you there!</p>

    <p>Dr. Williams will present: Moving Ecosystem Carbon Cycle Models Forward: Strategies for Improved Assessment and Prediction, Christopher A Williams, Yu Zhou, Huan Gu, Sha Feng, Thomas Lauvaux, Klaus Keller, Kenneth J Davis.</p>

    <p>Dr. Feng will present: Quantification of modeled atmospheric CO2 uncertainty from various sources using ACT-America aircraft data, Sha Feng, Thomas Lauvaux, Klaus Keller, Kenneth J Davis, Peter J Rayner, Yu Zhou, Christopher A Williams, David Baker, Andrew E Schuh, S Basu, Junjie Liu.</p>
  </li>
</ul>

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2018 October</div>
  <div class="news-timeline-content" markdown="1">

Dr. Williams presented my work at the international ForestSAT conference held in College Park, MD. Thanks, Chris!

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2018 August</div>
  <div class="news-timeline-content" markdown="1">

I enjoyed attending the Ecological Society of America annual meeting in August 2018, in New Orleans, LA. I presented in the Inspire session "Improving the Predictive Ability of the Global Carbon Cycle Models".

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2018 May</div>
  <div class="news-timeline-content" markdown="1">

I was selected to attend a May short course on New Advances in Land Carbon Cycle Modeling hosted by Yiqi Luo's EcoLab of the Center for Ecosystem Science and Society at Northern Arizona University. My travel is funded by the Summer Pruser Enhancement Award from Clark University.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2017 September</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/qifeng.png' | relative_url }}" alt="PolInSAR" class="img-fluid rounded z-depth-1 mb-3">

Our paper, "The Performance of Airborne C-Band PolInSAR Data on Forest Growth Stage Types Classification," is <a href="https://www.mdpi.com/2072-4292/9/9/955">online</a> in Remote Sensing now!

This paper proposes a classification scheme for forest growth stage types and other cover types using a support vector machine (SVM) based on the Polarimetric SAR Interferometric (PolInSAR) data acquired by the Chinese Multidimensional Space Joint-observation SAR (MSJosSAR) system.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2017 April</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/harvardforest.png' | relative_url }}" alt="HF" class="img-fluid rounded z-depth-1 mb-3">

I was awarded the Edna Bailey Sussman Fellowship to support my summer research at the Harvard Forest LTER!

I will (1) participate in field measurement programs recording biomass in recently harvested landscapes and (2) use plot-measured biomass to constrain a biogeochemical model for estimating rates of carbon uptake and release.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2016 December</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/lizhang.jpg' | relative_url }}" alt="Drought" class="img-fluid rounded z-depth-1 mb-3">

Our paper titled "Drought events and their effects on vegetation productivity in China" is <a href="https://esajournals.onlinelibrary.wiley.com/doi/10.1002/ecs2.1591">online</a> in Ecosphere today!

In this paper, we characterized the drought events in China from 1982 to 2012 and assessed their effects on vegetation productivity inferred from satellite data.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2016 October</div>
  <div class="news-timeline-content" markdown="1">

I attended the Data-Driven and Simulation Science Summer School in Jena hosted by Friedrich Schiller University and the Max Planck Institute for Biogeochemistry. I enjoyed my time in Germany!

I got a Travel Award to attend the Data-Driven and Simulation Science Summer School in Jena.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2015 November</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/jingfengxiao.jpg' | relative_url }}" alt="natural and human" class="img-fluid rounded z-depth-1 mb-3">

Our paper "Contributions of natural and human factors to increases in vegetation productivity in China" is <a href="https://esajournals.onlinelibrary.wiley.com/doi/10.1890/ES14-00394.1">online</a> in the Ecosphere.

We analyzed the long-term trends in vegetation productivity in China using the satellite-derived normalized difference vegetation index (NDVI) and assessed the relationships of NDVI with a suite of natural (air temperature, precipitation, photosynthetically active radiation (PAR), atmospheric carbon dioxide (CO2) concentrations, and nitrogen (N) deposition) and human (afforestation and improved agricultural management practices) factors.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2015 March</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/remotesensing.png' | relative_url }}" alt="central asia" class="img-fluid rounded z-depth-1 mb-3">

Our paper, "Climate contributions to vegetation variations in central Asian drylands: Pre-and post-USSR collapse," is <a href="https://www.mdpi.com/2072-4292/7/3/2449">online</a> in Remote Sensing.

Our results clearly illustrate the combined influence of climatic/anthropogenic contributions on vegetation growth in Central Asian drylands. Due to the USSR collapse, this region represents a unique case study of the vegetation response to climate changes under different climatic and socio-economic conditions.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2014 April</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/binghua zhang.jpg' | relative_url }}" alt="Mekong" class="img-fluid rounded z-depth-1 mb-3">

Our paper, "Drought impact on vegetation productivity in the Lower Mekong Basin," is <a href="https://www.tandfonline.com/doi/abs/10.1080/01431161.2014.890298">online</a> in the International Journal of Remote Sensing.

We assessed the impact of drought on vegetation productivity in the LMB during 2000-2011 using MOD17 products.

</div>
</section>

<section class="news-timeline-item">
  <div class="news-timeline-date">2014 January</div>
  <div class="news-timeline-content" markdown="1">

<img src="{{ '/assets/img/news/rangeland.jpg' | relative_url }}" alt="GPP" class="img-fluid rounded z-depth-1 mb-3">

Our paper, "A Comparison of Satellite-Derived Vegetation Indices for Approximating Gross Primary Productivity of Grasslands," is <a href="https://www.sciencedirect.com/science/article/pii/S1550742414500103">online</a> in Rangeland Ecology & Management.

We examined the relationships between the nine VIs derived from the moderate-resolution imaging spectroradiometer (MODIS) and tower-based GPP at five eddy covariance flux sites over the grasslands of northern China.

</div>
</section>
</div>
