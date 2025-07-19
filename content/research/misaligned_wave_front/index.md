---
title: Wind-waves coupling response during atmospheric cold fronts
type: page
layout: custom_layout
date: 2024-08-05
---
<br>
<p align="justify">Atmospheric cold fronts have elongated along-frontal scales of many 1000s km, but much shorter cross-frontal scales of only 10-100s km. They are accompanied by gale-force surface winds (15-30 m/s) and mark abrupt shifts in the direction between the pre-frontal and post-frontal winds.
 </p>
<br>
<!--more-->

<br>
<figure class="flex flex-col items-center h-full justify-end">
<img src="./featured.png" alt="Image 1" style="height:80%; width:80%" class="w-full object-contain">
<figcaption class="text-center text-sm mt-2">Fig1: A schematic representation of an atmospheric front passing over the ocean showing aligned wind‐waves under the warm sector and strongly misaligned waves behind the cold front. The schematic at the top left represents the mechanism of the enhanced drag behind the cold front when wind and waves are misaligned. The “L” symbol denotes the center of the low‐pressure system..</figcaption>
</figure>
<br>

<br>
<p align="justify">
At the sea surface, the strong winds generate short-length scale coupled wind-waves of 0.1-10s cm, while the veering of the wind leads to a large area of growing wind-waves that become misaligned with local winds due to the rapid translation of the fronts.
These misaligned wind waves behind the cold fronts have yet to be characterized by in situ observations, and the aggregated impacts of the associated sea state on the surface drag and the air-sea momentum fluxes have not been evaluated by numerical models. </p>
<br>
<p align="justify">The figures below show an archetypal atmospheric cold front passing over the Northeast of the U.S. on December 6, 2017, at 12:00 pm local time.
 </p>

<br>
<div class="grid grid-cols-2 gap-4 items-stretch">
  <figure class="flex flex-col items-center h-full justify-end">
  <img src="./noaa_weather_map_20171206.gif" alt="Image 1" style="height:100%; width:100%" class="w-full object-contain">
  <figcaption class="text-center text-sm mt-2">Fig2: --.</figcaption>
  </figure>
  <figure class="flex flex-col items-center h-full justify-end">
  <img src="./satellite_image_front_dec2017_v2.png" alt="Image 2" style="height:85%; width:100%" class="w-full object-contain">
  <figcaption class="text-center text-sm mt-2">Fig3: --.</figcaption>
  </figure>
</div>
<br>

<p align="justify">The analysis of the observed surface waves and momentum fluxes from the OOI Pioneer Array (Fig4) indicates the abrupt veering of wind direction as the front passes the mooring location, i.e., southerly prior to the front followed by the northerly after the front.
On the other hand, the wave direction changes much more slowly since these wind waves in the northward direction are still growing (as indicated by the low wave age, Fig4, Fig5) in response to southerly wind prior to the front passage. 
This leads to a period of strong misalignment between wind and waves lasting more than 24 hours (Fig4). 
</p>


<br>
<div class="grid grid-cols-2 gap-4 items-stretch">
  <figure class="flex flex-col items-center h-full justify-end">
  <img src="./time_serie_OOI_WBF.png" alt="Image 1" style="height:100%; width:100%" class="w-full object-contain">
  <figcaption class="text-center text-sm mt-2">Fig4: --.</figcaption>
  </figure>
  <figure class="flex flex-col items-center h-full justify-end">
  <img src="./wavspec_front_case_gif.gif" alt="Image 2" style="height:85%; width:100%" class="w-full object-contain">
  <figcaption class="text-center text-sm mt-2">Fig5: --.</figcaption>
  </figure>
</div>
<br>

<p align="justify">The analysis of moored observations is complemented by the analysis of two high-resolution ocean-atmosphere-wave coupled model simulations contrasting the run (WBF) with the default wave-based formulation in COARE, which assumes the scalar wave stress to another run (WBF_θ), which increase the roughness length if the waves are significantly misaligned with winds.
The simulations show that area of the misaligned waves is significant, commensurate with the along-frontal length scales of many 1000s km behind the front and the time-scales of the frontal passage. The misaligned waves increase the surface drag and air-sea momentum fluxes, in this case, by up to 20% over the large area of the misaligned waves (Fig6). 
</p>

<br>
<center>
<img src="./map_wbftheta_wbf_TAU.png" style="height:100%; width:100%">
<figcaption>Fig6: Momentum flux evolution (top) and differences between WBF_θ and WBF (bottom) during the atmospheric cold front passage.</figcaption>
</center>
<br>
<br>


<div class="border border-gray-300 p-4 rounded bg-gray-100">
  <ul class="my_list"> <li><strong>Sauvage, C.</strong>,  Seo, H., Barr, B., Clayson, C-A., Edson, J.B., <em>Misaligned Wind-Waves Behind Atmospheric Cold Fronts.</em> Journal of Geophysical Research: Oceans, DOI: <span class="epub-section__item"><a class="epub-section__doi__text" href=" https://doi.org/10.1029/2024JC021162">10.1029/2024JC021162</a></span>, 2024</li></ul>
</div>
