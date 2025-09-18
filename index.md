---
layout: homepage
---

<style>
  /* Justify all normal text */
  body {
    text-align: justify;
  }

  /* Keep all headings aligned left */
  h1, h4, h5, h6 {
    text-align: left;
  }

<style>
  h2 {
    border-bottom: 1.5px solid #d3d3d3; /* light gray line */
    padding-bottom: 0.3em; 
    margin-bottom: 0.8em; 
    display: block; /* ensures line spans full width */
  }

  /* Add extra top margin only to h2 except the first one */
  h2:not(:first-of-type) {
    margin-top: 1.5em; /* space before subsequent h2 */
  }
</style>

<h2>About Me</h2>
<div style="text-align: justify;">
  <p>
    I am an Oceanography graduate and geospatial enthusiast with a strong foundation in remote sensing, GIS mapping, and environmental data science. My expertise spans geospatial analysis, spatial modeling, and advanced data visualization, with proficiency in tools such as ArcGIS, SeaDAS, and Google Earth Engine for satellite data processing and geographic analysis.
  </p>
  <p>
    In addition to my technical skills, I am experienced in programming with Python and R, as well as advanced MS Excel, enabling me to apply computational, statistical, and spatial approaches to complex environmental and oceanographic datasets. I am particularly passionate about leveraging these skills to address practical challenges in coastal and urban systems, contributing to innovative, data-driven research and solutions.
  </p>
</div>

<h2>Research Interests</h2>
<ul style="list-style:none; padding-left:0;">
  <li style="margin-bottom:24px; display:flex; align-items:flex-start;">
    <span style="width:44px; height:44px; display:flex; align-items:center; justify-content:center; background:#f6f6f6; border-radius:50%; font-size:1.8em; margin-right:17px;">
      🌍
    </span>
    <div>
      <div style="font-size:1.07em; font-weight:600;">Remote Sensing & GIS Applications</div>
      <div style="color:#444;">Satellite data analysis, spatial modeling, and geospatial data management.</div>
    </div>
  </li>
  <li style="margin-bottom:24px; display:flex; align-items:flex-start;">
    <span style="width:44px; height:44px; display:flex; align-items:center; justify-content:center; background:#f6f6f6; border-radius:50%; font-size:1.8em; margin-right:17px;">
      📊
    </span>
    <div>
      <div style="font-size:1.07em; font-weight:600;">Oceanographic Data Science</div>
      <div style="color:#444;">Computational and statistical approaches to marine and atmospheric datasets.</div>
    </div>
  </li>
  <li style="margin-bottom:24px; display:flex; align-items:flex-start;">
    <span style="width:44px; height:44px; display:flex; align-items:center; justify-content:center; background:#f6f6f6; border-radius:50%; font-size:1.8em; margin-right:17px;">
      🌊
    </span>
    <div>
      <div style="font-size:1.07em; font-weight:600;">Coastal & Urban Flood Risk Assessment</div>
      <div style="color:#444;">Integrated modeling, spatial analysis, and machine learning applications.</div>
    </div>
  </li>
  <li style="margin-bottom:24px; display:flex; align-items:flex-start;">
    <span style="width:44px; height:44px; display:flex; align-items:center; justify-content:center; background:#f6f6f6; border-radius:50%; font-size:1.8em; margin-right:17px;">
      🌡️
    </span>
    <div>
      <div style="font-size:1.07em; font-weight:600;">Climate Change & Environmental Monitoring</div>
      <div style="color:#444;">Impacts on coastal ecosystems, agriculture, and trade vulnerability.</div>
    </div>
  </li>
  <li style="margin-bottom:24px; display:flex; align-items:flex-start;">
    <span style="width:44px; height:44px; display:flex; align-items:center; justify-content:center; background:#f6f6f6; border-radius:50%; font-size:1.8em; margin-right:17px;">
      🤖
    </span>
    <div>
      <div style="font-size:1.07em; font-weight:600;">Geospatial Artificial Intelligence (GeoAI)</div>
      <div style="color:#444;">Machine learning and predictive modeling for environmental systems.</div>
    </div>
  </li>
  <li style="margin-bottom:24px; display:flex; align-items:flex-start;">
    <span style="width:44px; height:44px; display:flex; align-items:center; justify-content:center; background:#f6f6f6; border-radius:50%; font-size:1.8em; margin-right:17px;">
      ⚓
    </span>
    <div>
      <div style="font-size:1.07em; font-weight:600;">Marine & Coastal Resource Management</div>
      <div style="color:#444;">Sustainable development, conservation, and blue economy applications.</div>
    </div>
  </li>
</ul>



<h2>Research Projects</h2>
  <h3 style="margin-bottom: 5px;">Spatial and Temporal Variability of PAR, Kd<sub>490</sub>, and SST in the Bangladesh EEZ (2016–2022)</h3>
  <p style="margin-top: 0;">Undergraduate Project &nbsp; | &nbsp; <b>Supervisor:</b> Abu Bokkar Siddique &nbsp; | &nbsp; Jul 2023 - Dec 2023</p>
  <div style="display:flex; flex-wrap:wrap; gap:1.5em;">
    
    <!-- Representative Project Image 
    <div style="flex:1; gap: 10px; flex-wrap: wrap;">
    
      <img src="./projects/study_area.png" 
      alt="study_area" style="width:50%; border-radius:0px; box-shadow:0 2px 8px #bbb;">
      <img src="./projects/PAR.png" 
      alt="PAR" style="width:50%; border-radius:0px; box-shadow:0 2px 8px #bbb;">
      <img src="./projects/KD.png" 
      alt="KD" style="width:50%; border-radius:0px; box-shadow:0 2px 8px #bbb;">
      <img src="./projects/SST.png" 
      alt="SST" style="width:50%; border-radius:0px; box-shadow:0 2px 8px #bbb;">
     </div> -->

    <!-- Project Highlights -->
    <div style="flex:2; min-width:320px;">
    
      <h4 style="margin-bottom:.2em;">Project Summary</h4>
      <div style="text-align: justify;">
      <p> This research investigates how <strong>Photosynthetically Available Radiation (PAR)</strong>, <strong>Diffuse Attenuation Coefficient (Kd<sub>490</sub>)</strong>, and <strong>Sea Surface Temperature (SST)</strong> vary both spatially and temporally in the Bangladesh Exclusive Economic Zone (EEZ) from 2016 to 2022. Using satellite-derived data (MODIS-Aqua) processed in SeaDAS and ArcGIS, the study analyzes monthly and annual trends for each parameter. The aim is to reveal how these physical factors influence marine ecosystems in the Bay of Bengal and to provide insights crucial for sustainable management amid climate change.</p>
      </div> 
      
       <h4 style="margin-bottom:.2em;">Key Findings</h4>
       <div style="text-align: justify;">
          <ul style="margin-top:0;">
            <li>PAR ranged from <b>32.47 – 55 Einstein/m²/day</b> with higher values offshore and seasonal highs in May–July.</li>
            <li>Kd<sub>490</sub> values indicated higher water turbidity (up to <b>0.33 m⁻¹</b>) near coastlines due to runoff &amp; anthropogenic impacts.</li>
            <li>SST varied seasonally from <b>22°C – 31°C</b>, revealing a subtle multi-year warming trend.</li>
          </ul>
        </div>
       
<h4 style="margin-bottom: .2em;">
  <a href="./projects/undergrad_project.pdf" 
     target="_blank" 
     style="text-decoration: none; color: inherit; display: inline-flex; align-items: center; gap: 6px;">
    View Full Project
    <svg xmlns="http://www.w3.org/2000/svg" 
         width="18" height="18" fill="currentColor" 
         viewBox="0 0 24 24" style="margin-left: 4px;">
      <path d="M14 3h7v7h-2V6.41l-9.29 9.3-1.42-1.42 9.3-9.29H14V3z"/>
      <path d="M5 5h5V3H3v7h2V5zm0 14v-5H3v7h7v-2H5z"/>
    </svg>
  </a>
</h4>

<p>
</p>
  <h3 style="margin-top: 1.3em; margin-bottom: 5px;"> Quantitative Analysis of Annual Chlorophyll-a and Sea Surface Temperature Fluctuations in the Bay of Bengal Using Remote Sensing Data</h3>
  <p style="margin-top: 0;">Lab Project &nbsp; | &nbsp; <b>Supervisor:</b> Dr. Subrata Sarker &nbsp; | &nbsp; May 2023 - Jun 2023</p>
  <div style="display:flex; flex-wrap:wrap; gap:1.5em;">
    
    <!-- Representative Project Image 
    <div style="flex:1; gap: 10px; flex-wrap: wrap;">
    
      <img src="./projects/study_area.png" 
      alt="study_area" style="width:50%; border-radius:0px; box-shadow:0 2px 8px #bbb;">
      <img src="./projects/PAR.png" 
      alt="PAR" style="width:50%; border-radius:0px; box-shadow:0 2px 8px #bbb;">
      <img src="./projects/KD.png" 
      alt="KD" style="width:50%; border-radius:0px; box-shadow:0 2px 8px #bbb;">
      <img src="./projects/SST.png" 
      alt="SST" style="width:50%; border-radius:0px; box-shadow:0 2px 8px #bbb;">
     </div> -->

    <!-- Project Highlights -->
    <div style="flex:2; min-width:320px;">
    
      <h4 style="margin-bottom:.2em;">Project Summary</h4>
      <div style="text-align: justify;">
      <p> This research analyzes the spatial and temporal patterns of Chlorophyll-a concentration and Sea Surface Temperature (SST) in the Bay of Bengal using monthly satellite data from January to December 2020. Data were sourced from the NASA Ocean Color Web and processed using SNAP and ArcMap software. Specific coastal regions near Bangladesh were selected for detailed comparison, while regional and seasonal variability across the Bay was mapped and quantified. The study aimed to enrich understanding of marine ecological dynamics and climate processes in the Bay of Bengal, providing valuable data for marine research and management.</p>
      </div> 
      
       <h4 style="margin-bottom:.2em;">Key Findings</h4>
       <div style="text-align: justify;">
          <ul style="margin-top:0;">
            <li>Chlorophyll-a levels were <b>lowest</b> in May and peaked in August, indicating strong seasonal variation.</li>   
            <li>Sea Surface Temperature (SST) <b>increased</b> gradually from January, peaked in May, then declined after October.</li>
            <li>There was a <b>negative correlation</b> between chlorophyll-a and SST: higher chlorophyll was found when SST was lower.</li>
            </ul>
      </div>
       
<h4 style="margin-bottom: .2em;">
  <a href="./projects/4_1_project.pdf" 
     target="_blank" 
     style="text-decoration: none; color: inherit; display: inline-flex; align-items: center; gap: 6px;">
    View Full Project
    <svg xmlns="http://www.w3.org/2000/svg" 
         width="18" height="18" fill="currentColor" 
         viewBox="0 0 24 24" style="margin-left: 4px;">
      <path d="M14 3h7v7h-2V6.41l-9.29 9.3-1.42-1.42 9.3-9.29H14V3z"/>
      <path d="M5 5h5V3H3v7h2V5zm0 14v-5H3v7h7v-2H5z"/>
    </svg>
  </a>
</h4>

