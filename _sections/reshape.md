---
title: Reshaping the world
icon: fa-check
order: 5
---

<h3>Destructivity of the crops</h3>
<div style="text-align: justify">
<p>
  Now, the study will shift toward  the destructive impact assessment of selected crops on the biome it is being cultivated in. Such impacts depicts the originally raw surface which is transformed for cultivation puroposes. More precisely, a crop will be considered as destructive if its culture is mainly meant for
  satisfying global food demand compared to local needs. This will allow us to get the impact of global food trends on local landscape. On should however mention that imports followed by exports  for specific crop are considered here as originaly produced by the concerned region. 
 
</li>
</p>

<p>
  In order to  asses this impact, we considered correlation between export quantity and area loss for a specific geographical area and biome. As the orginal cause for such area loss is absent from our data, a strong correlation would suggest that culturable lands tookover. Hence, the higher is the correlation coefficient, the higher the area
  loss. As a side note, we used an arbitrary threshold of 0.7 (absolute value) for the correlation coefficient. Thus, any crop having a correlation over this threshold was
  considered potentially harmful to the local landscape. Conversely, any value under this threshold was not taken into account. The resulting correlations are shown on a heatmap
  First, one can observe that such high coefficiant are experienced for the Forest vs Region loss shown above. For instance Western Asia lands seem to have been affected by Watermelon demand over the years. European regions also display high coefficiant and such  for several different crops. However one should mention the quite high number of negative coefficiant (below -0.7). Further analysis would have required additional information for interpretation.
  One theory would be that the time span for crop growth is sometime long. For instance, growing palm trees would take around 4 years for oil export. Knowing that, land expansion for that culture could not instantly be followed by production growth. More over land expansion is not continuous but pulse stage like.
  
  On the other hand, since satisfying global food demand is considered harmfull for local lands, another metric was taken into account. After dividing exports by production quantity,
  a ratio was obtained to depict the production yield that was meant for global demand. That way if a crop is mostly produced for exportation in a given country and a strong correlation is being experienced for country's region as well, one could state that the crop has a destructive outcome. 
  Using both informations, this study outlines a subset of countries for wich crops were considered to have a shapping effect. 


  One should however mention the limits of negative crops detection. Since corp culture depends on multiple factors such as: local environement, economical context, geographical situation ... It can quickly become a hard task to state overall negative crops. Being country specific guarantees that the above mentioned are matched for a given crop. 




  
</p>

{% include Correlation_between_Forest_Area_Loss_and_Export_by_regions.html %}

<p>
  
</p>  
  The study aims as 
<p>


  Another aspect of our work was to try to provide suggestions to countries for replacing destructive crops with other, more sustainable crops. Therefore, we want this time to
  evaluate the positive impact of a crop. To do this, we thought about using the following features for a given crop :
</p>

<ul>
<li>
  The quantity which is used locally
</li>
<li>
  The surface yield
</li>
<li>
  The economic yield
</li>
<li>
  The destructive impact of the crop
</li>
</ul>

<p>
  The quantity which is used locally is simply measured as the percentage of production which is not exported. For its part, the surface yield is measured by the production
  quantity in tonnes over the area harvested in hectares. This represents the efficiency of the crop culture with respect to the allocated space.
</p>
</div>
