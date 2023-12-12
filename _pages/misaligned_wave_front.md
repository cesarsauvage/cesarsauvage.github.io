---
title: <div align="center">Wind-waves coupling response during atmospheric cold fronts</div>
layout: splash 
classes : wide
author_profile : false
permalink: /research/misaligned_wave_front/
header:
  overlay_image: /assets/images/wave_2.png
---

<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.left_col {
  float: left;
  width: 50%;
  padding: 2px;
}
.right_col {
  float: right;
  width: 50%;
  padding: 2px;
}
  .container {
  display: flex;
  align-items: center;
  justify-content: center
  }
  .text {
  font-size: 20px;
  padding-left: 20px;
  }  
/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

 img {  
 max-width: 100%;  
 height: auto;  
 }  

  /* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
  
</style>

  <div class="row">
    <div class="left_col">
<center>
<img src="/assets/images/misaligned_wave_front/noaa_weather_map_20171206.gif" style="height:80%; width:80%">
<figcaption></figcaption>
</center>
    </div>
    <div class="right_col">
<center>
<img src="/assets/images/misaligned_wave_front/satellite_image_front_dec2017_v2.png" style="height:100%; width:100%">
<figcaption></figcaption>
</center>
    </div>
</div>


<p align="justify">Atmospheric cold fronts have elongated along-frontal scales of many 1000s km, but much shorter cross-frontal scales of only 10-100s km. The figures above show an archetypal atmospheric cold front passing over the Northeast of the U.S. on December 6, 2017, at 12:00 pm local time.
They are accompanied by gale-force surface winds (15-30 m/s) and mark abrupt shifts in the direction between the pre-frontal and post-frontal winds.
At the sea surface, the strong winds generate short-length scale coupled wind-waves of 0.1-10s cm, while the veering of the wind leads to a large area of growing wind-waves that become misaligned with local winds due to the rapid translation of the fronts.
These misaligned wind waves behind the cold fronts have yet to be characterized by in situ observations, and the aggregated impacts of the associated sea state on the surface drag and the air-sea momentum fluxes have not been evaluated by numerical models. </p>

  <div class="row">
    <div class="left_col">
<center>
<img src="/assets/images/misaligned_wave_front/time_serie_OOI_WBF.png" style="height:90%; width:90%">
<figcaption> Fig1: Timeseries comparison between the Ocean Observatory Initiative (OOI) and the coupled simulation WBF_θ. </figcaption>
</center>
    </div>
    <div class="right_col">
<center>
<img src="/assets/videos/wavspec_front_case_gif.gif" style="height:80%; width:80%">
<figcaption>Fig2: Normalized energy density (m2/deg) simulated during the atmospheric cold front passage.</figcaption>
</center>
    </div>
</div>
<p align="justify">The analysis of the observed surface waves and momentum fluxes from the OOI Pioneer Array (Fig1) indicates the abrupt veering of wind direction as the front passes the mooring location, i.e., southerly prior to the front followed by the northerly after the front.
On the other hand, the wave direction changes much more slowly since these wind waves in the northward direction are still growing (as indicated by the low wave age, Fig1, Fig2 and Fig3) in response to southerly wind prior to the front passage. 
This leads to a period of strong misalignment between wind and waves lasting more than 24 hours (Fig1 and Fig3). The analysis of moored observations is complemented by the analysis of two high-resolution ocean-atmosphere-wave coupled model simulations contrasting the run (WBF) with the default wave-based formulation in COARE, which assumes the scalar wave stress to another run (WBF_θ), which increase the roughness length if the waves are significantly misaligned with winds.
The simulations show that area of the misaligned waves is significant, commensurate with the along-frontal length scales of many 1000s km behind the front and the time-scales of the frontal passage. The misaligned waves increase the surface drag and air-sea momentum fluxes, in this case, by up to 20% over the large area of the misaligned waves (Fig4). </p>

  <div class="row">
    <div class="left_col">
<center>
<img src="/assets/images/misaligned_wave_front/map_wbftheta_wbf_angle_waveage.png" style="height:100%; width:100%">
<figcaption>Fig3: Angle between wind and waves (top) and wave wage (bottom) evolution during the atmospheric cold front passage.</figcaption>
</center>
    </div>
    <div class="right_col">
<center>
<img src="/assets/images/misaligned_wave_front/map_wbftheta_wbf_TAU.png" style="height:100%; width:100%">
<figcaption>Fig4: Momentum flux evolution (top) and differences between WBF_θ and WBF (bottom) during the atmospheric cold front passage.</figcaption>
</center>
    </div>
</div>
