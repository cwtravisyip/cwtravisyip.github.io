---
layout: post
title: Regional GDP in England and Wales
subtitle: London's recovery from the COVID-19 outpaced the rest of England and Wales
date: 2024-01-22
img_src: /images/porfolio_of_work/20240122_gdp_gr_by_region_01.png
tags: dataViz


---
<div class='tableauPlaceholder' id='viz1713530964113' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;HJ&#47;HJJTFBXSR&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;HJJTFBXSR' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;HJ&#47;HJJTFBXSR&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-GB' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1713530964113');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1827px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>



![Absolute GDP in 2019 million pounds](/images/porfolio_of_work/20240122_gdp_by_region_02.png)
The latest [GDP index](https://www.ons.gov.uk/economy/grossdomesticproductgdp/methodologies/grossdomesticproductgdpukregionsandcountriesqmi) published by the ONS shows that England and Wales generated close to 500 billion in 2019 pounds. London alone contributes to 27% of the economic output in the region.

![Latest Quarter GDP (Value-Added) by Industry](/images/porfolio_of_work/20240122_gdp_gr_by_region_01.png)
Compared to the previous year, London's economy fared better compared to the rest of England and Wales in the recovery from COVID-19. Comparing the third quarterly GDP between 2022 and 2023, the economy has grown and rebounded by over 6%, more than double the country's aggregated. According to a [TLDR; report](https://www.youtube.com/watch?v=Ype43hG6lN8&t=620s), this discrepancy is attributed to regional inequality: The wealthier region is more resilient and emerges from the economic turmoil better than those on the other end of the spectrum.

![GDP Growth Rate by Industry](/images/porfolio_of_work/20240122_gdp_gr_by_region_04.png)
Looking at the GDP growth rate aggregated by industry, it seems that this recovery is also in part due to the strong growth that is seen in the servicing sector. In fact, the 8% growth in the GDP generated from the service industry offset the decrease in GDP generated from both the production (–13%) and construction industry (–8%) in 2023.


![Weighted GDP Growth Rate by Industry](/images/porfolio_of_work/20240122_gdp_wgr_by_region_03.png)
This outsized effect of the service industry on the overall regional economic growth is due to the major role the industry has on London's economy at baseline. Adjusted for the importance of the industry to the region's economy, the service sector contributed 7.57% point to the total GDP growth in the period. More interestingly, it also shows that the decrease in economic output from the production and manufacturing industry took a bigger toll on the GDP growth in the rest of England and Wales. After adjusting for the industry's weight on the aggregate GDP growth rate, the manufacturing and production industry pulled back the regional economic growth in the rest of England and Wales three times compared to that in London.

<span style="color:#8F8F8F">*Author's Note:<br>In this analysis, we have ignored the hit of COVID-19 on the GDP by sector. This should be addressed in the next revision of the analysis. Due to the constraint of data availability, quarterly GDP data is used and compared to the same quarter across different years to minimise the distortion of seasonability of the analysis of the data. We also only focused on Wales and England and ignored Scotland and Northern Ireland due to data availability constraints. The GDP index is converted into 2019 monetary value using the [GDP dataset](https://www.ons.gov.uk/file?uri=/economy/grossvalueaddedgva/datasets/nominalandrealregionalgrossvalueaddedbalancedbyindustry/current/regionalgrossvalueaddedbalancedbyindustryandallitlregions.xlsx). For detailed methodology, this could found in the respective [GitHub repository](https://github.com/cwtravisyip/ONS_Census2021).*</span>

