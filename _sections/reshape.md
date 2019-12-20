---
title: Reshaping the world
icon: fa-check
order: 5
---

<h3>Destructivity of the crops</h3>
<div style="text-align: justify">
<p>
  Now, the study will shift a little bit and we will try to identify the destructive impact of selected crops on the biome it is being cultivated in. Such impacts
  depicts the originally raw surface which is transformed for cultivation puroposes. More precisely, a crop will be considered as destructive if its culture is mainly meant for
  satisfying global food demand compared to local needs. This will allow us to get the impact of global food trends on local landscape.
</p>

<p>
  In order to find this impact, we computed the correlation between export quantity and area loss for a specific geographical area and biome and used it as an insightful metric.
  As you can see on the correlation heatmap, the "Forest" biome was considered and it gave us interesting results. The higher is the correlation coefficient, the higher the area
  loss. As a side note, we used an arbitrary threshold of 0.7 (in absolute value) for the correlation coefficient. Thus, any crop having a correlation over this threshold was
  considered harmful to the local landscape. Conversely, any value under this threshold was not taken into account. The resulting correlations are shown on the heatmap.
</p>

{% include Correlation_between_Forest_Area_Loss_and_Export_by_regions.html %}

<p>
  Looking at this heatmap, we see that quite a lot of these crops and regions have a consequent correlation with respect to the quantity exported and the area loss. Take the
  Middle Africa and strawberries for example. The value is of 1, which means that the quasi-totallity of Middle Africa's production of strawberries is exported. This implies that
  strawberries might be a very harmful crop to Middle Africa local landscape, depending on the actual quantity exported. One interesting thing we noticed is that there are also quite a lot of negatively high correlation coefficient.
  The meaning of that is quite difficult to see, but our investigation resulted in the fact that some crops take a lot of time before giving things to sell or exports. This means
  that the transformation of a biome might not be directly followed by the production of a crop in the same year. The palm trees are a good example of this : it takes around 4 years
  for a palm tree to give oil. However, it is also important to take into account the actual quantity which is exported, as a country could for example produce very few tomatoes and
  export all of them which would result in a very high correlation coefficient.
</p>

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
