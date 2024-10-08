| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Assignment: Visualizing government debt using Tableau

## Part one: Working with web-based visualization tools and data
This bar chart shows government debt as a percentage of GDP for each country in 2022. In the chart, Japan has the highest government debt to GDP ratio at nearly 250%, much higher than any other country. Italy, France, and Portugal are next with debt ratios above 100%. The chart also includes the OECD average as a standard of comparison. Some countries, such as Luxembourg and South Korea, have lower debt-to-GDP ratios, close to or below 30%.
Date Source: “General Government Debt.” 2024. OECD. 2024. https://www.oecd.org/en/data/indicators/general-government-debt.html.

<img src="A1 Screenshot.png" width=500px />

## Working with Tableau
Using OECD data, I created a highlighted table via Tableau to show government debt as a percentage of GDP for each country from 1995 to 2003. I used time as the columns and debt ratios as the rows, and used colors to distinguish between different debt levels. Countries with ratios above 100% are shown in orange and those below 100% are shown in blue to visually compare changes in debt across countries. I also sorted the data, removed countries with missing data, and added data sources and citations to the chart.

Countries such as Japan, Greece, and Italy have seen their debt ratios rise significantly, especially after the financial crisis, while some countries such as Estonia and Luxembourg have consistently low debt ratios. The chart clearly shows the long-term changes in the debt levels of countries.

<div class='tableauPlaceholder' id='viz1725999398332' style='position: relative'><noscript><a href='#'><img alt='Government Debt to GDP Ratio by Country, 1995-2019Data source: “General Government Debt.” 2024. OECD. 2024. https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html.‌ ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17257743426070&#47;GovernmentDebttoGDPRatiobyCountry1995-2019&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='Book1_17257743426070&#47;GovernmentDebttoGDPRatiobyCountry1995-2019' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Bo&#47;Book1_17257743426070&#47;GovernmentDebttoGDPRatiobyCountry1995-2019&#47;1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1725999398332');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

## Part three: create your own visualization
This visualization highlights the top 5 and bottom 5 countries by their government debt-to-GDP ratios over the period from 1995 to 2003. The chart is designed to compare the countries with the highest and lowest average debt-to-GDP ratios, while also providing a visual representation of other countries in gray to emphasize the contrast. The Top 5 countries are shown in orange, the Bottom 5 in blue, and all other countries in gray, without labels for clarity.

<div class='tableauPlaceholder' id='viz1726000449285' style='position: relative'><noscript><a href='#'><img alt='Time Trend of Government Debt to GDP Ratio by Country, 1995-2019Data source: “General Government Debt.” 2024. OECD. 2024. https:&#47;&#47;www.oecd.org&#47;en&#47;data&#47;indicators&#47;general-government-debt.html.‌ ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ho&#47;homework1_17258303072560&#47;TimeTrendofGovernmentDebttoGDPRatiobyCountry1995-2019&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='homework1_17258303072560&#47;TimeTrendofGovernmentDebttoGDPRatiobyCountry1995-2019' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;ho&#47;homework1_17258303072560&#47;TimeTrendofGovernmentDebttoGDPRatiobyCountry1995-2019&#47;1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1726000449285');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

**Visualization Methods Comparison:**
Bar charts:
The bar chart helps to quickly determine which countries have the highest or lowest debt for that year. However, it provides a static snapshot and lacks insight into long-term trends.

Heatmap:
A heat map provides a broader view by showing each country's debt-to-GDP ratio over the years. It color-codes debt levels, using different color scales to highlight countries with very high or very low debt ratios. This visualization is great for spotting patterns over time and comparing different countries, but can be overwhelming when looking for specific trends.

Line Charts:
Focusing on the top 5 and bottom 5 countries, the line charts allow for a detailed comparison of trends over time. By highlighting only the extremes, the visualization reduces clutter and provides a clearer picture of the evolution of the debt ratios of these countries. Other countries are shown in gray, ensuring that the overall pulse is visible and not distracting. This approach is useful when focusing on outliers or important cases, while still maintaining an overview of the data set. However, they are easy to be visually confusing when dealing with a large number of categories, difficult to distinguish colors, and unable to visually display specific data, making it easy to ignore changes in intermediate values.

**Why I chose line chart?**
I chose the line chart as the third visualization because it provides a clear and focused comparison of the most important data points: the top 5 debt-to-GDP ratios and the bottom 5 countries. While heat maps and bar charts provide valuable insights, they either overwhelm the viewer with too much information or lack the ability to show changes over time. On the other hand, line charts strike a balance between clarity and detail. By limiting the focus to the most extreme cases and presenting trends over time, it allows viewers to easily track and understand how debt levels have evolved in these countries without being distracted by data from other countries. The use of color (orange for high debt and blue for low debt) further enhances the visualization and helps to quickly distinguish between extreme cases. Overall, the line charts tell a more focused and interpretable story.
