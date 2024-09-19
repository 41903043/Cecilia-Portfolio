| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Critique by Design with Tableau (MakeoverMonday)

## Step one: the visualization

![Original Graph](Original%20Graph.png)

Data Source: https://data.world/makeovermonday/2023w1

I chose to redesign this visualization of data for two main reasons. First, I am interested in environmental data, especially data that elucidates the effects of greenhouse gases over time, which is why I chose it. Second, the initial visualization of the graph presented a challenge to direct understanding due to its two-axis configuration and the lack of a clear explanation of the units of measurement on the y-axis. This complexity can obscure the important information and data insights it is supposed to convey, and is therefore the best candidate for redesign to improve clarity and accessibility.

## Step two: the critique

The strength of this chart is that it effectively communicates complex data in a straightforward manner, using clear, distinguishable lines to represent various data trends. This enhances its utility and realism, ensuring that key environmental data are accurately communicated. However, due to its dual-axis design, and the difficulty in understanding the data in vertical coordinates, the chart struggles with intuitiveness and perceivability, which may confuse viewers unfamiliar with this type of layout. While the chart maintains a clean aesthetic, it lacks an engaging element to appeal to a wider audience or encourage further interaction with the data.

## Step three: Sketch a solution

<img src="Draft.png" />

## Step four: Test the solution

Questions to ask: 

- Can you tell me what you think this is?

- Can you describe to me what this is telling you?

- Who do you think is the intended audience for this?

- Is there anything you're confused about or can't read in this chart?
  
- Is there anything you're surprised in this chart?

- Is there anything you would change or do differently?

Results: 

_Don't identify or share personally identifiable information (PII) about the people you spoke to._


| Question | Interview 1 (student, early 20's) | Interview 2 (student, mid 10's)|
|----------|-------------|-------------|
| Can you tell me what you think this is? | This is a graph showing the increase in different greenhouse gases over time | This is a colorful line chart |
| Can you describe to me what this is telling you? | Environment is getting worse | Greehouse Gases is increasing |
| Who do you think is the intended audience for this? | Environmental scientists, those who can read vertical coordinates | Teachers, students, people interested in the environment |
| Is there anything you're confused about or can't read in this chart? | The graphs are clear, but I'm confused as to whether this data is global or country or region specific. Also, what the vertical coordinate 'radiative forcing' means is not quite clear, and I would like a more detailed explanation of it | I don't quite understand what the letters representing the different colors in the chart mean, what the yellow and green represent respectively, and I don't know what the words and units on the left mean either |
| Is there anything you're surprised in this chart? | Surprised that the others don't seem to be too all over the place overall, but co2 and that very long name keep growing, and co2 actually almost doubled, I'd like to understand the reason for that | Greenhouse gases are increase continuously |
| Is there anything you would change or do differently? | I'll add more comments to explain the meaning and units of the vertical axis | To explain the colors? I don't know, I can't actually read the specifics of it |

Synthesis: 

A clear pattern from the feedback collected was that many people were confused about what the axes and colors of the charts indicated. This suggests that the charts may not be sufficiently visual in representing the data. In addition, some of the feedback noted that the text in the charts was not clear enough, which affected the efficiency of the information being conveyed. Also, the chemical equations were difficult for younger viewers to understand, which limited the breadth of information conveyed. This feedback helped me realize the charts' shortcomings in terms of readability and acceptability.

Based on this feedback, I made several changes in the final design:

1. Adding notes: To explain the meaning of the axes, I added a detailed note below the title explaining what “radiative forcing” means.
2. Adjusted font clarity: Based on feedback, I change the color of the words to ensure that they can be read clearly even from a distance or on a small screen.
3. Chemical Equations Converted to Text: In order to make it understandable to younger viewers, I converted chemical equations into simple text descriptions to make the information more accessible.
4. Color Adjustment: Many of my friends expressed confusion about the original colors and did not understand the meaning of different colors. Therefore, I chose gradient colors in the same color family to represent the growth of different gases, and purposely used yellow and brown colors that represent pollution to visually reinforce the negative impact of greenhouse gases on the environment.
5. Added a “global” label to the title of vertical scale: In order to remove uncertainty about the scope of the data, I explicitly labeled the vertical scale “global” to indicate that the data displayed are the radiative forcing of greenhouse gases on a global scale. This change helps to improve the clarity of the graph and the readability of the data.

With these design changes, I hope that the final chart will convey the key messages more effectively and inspire a wider audience, including teenagers, to care about and understand environmental protection. These adjustments not only increase the educational value of the chart, but also enhance its visual appeal, making it a more effective communication tool.

## Step five: build the solution

<div class='tableauPlaceholder' id='viz1726711812185' style='position: relative'><noscript><a href='#'><img alt='Caution: Rising Levels of Greenhouse GasesRadiative Forcing (W&#47;m²): This metric quantifies the effect of factors (like greenhouse gases) on Earth&#39;s energy balance,representing the amount of energy per unit area. It indicates warming (positive values) or ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;GreenhouseGases_17266292234010&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' style='display:none;'>
        <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
        <param name='embed_code_version' value='3' />
        <param name='site_root' value='' />
        <param name='name' value='GreenhouseGases_17266292234010&#47;Sheet1' />
        <param name='tabs' value='no' />
        <param name='toolbar' value='yes' />
        <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Gr&#47;GreenhouseGases_17266292234010&#47;Sheet1&#47;1.png' />
        <param name='animate_transition' value='yes' />
        <param name='display_static_image' value='yes' />
        <param name='display_spinner' value='yes' />
        <param name='display_overlay' value='yes' />
        <param name='display_count' value='yes' />
        <param name='language' value='en-US' />
        <param name='filter' value='publish=yes' />
    </object></div>
<script type='text/javascript'>
    var divElement = document.getElementById('viz1726711812185');
    var vizElement = divElement.getElementsByTagName('object')[0];
    vizElement.style.width = '100%';
    vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
    var scriptElement = document.createElement('script');
    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
    vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>


This project was a very interesting process because it gave me the opportunity to improve and present the data I was interested in through visualization. The starting point for this project was an observation of the raw data, I noticed that the data included a variety of different greenhouse gases so I decided to use a stacked line graph to display it. This type of chart not only shows the overall growth trend, but also provides a clear view of the breakdown of each different gas.

Initially, my chart contained seven sections, but I found this design to be overly complex and cluttered. To simplify and improve the readability of the chart, I chose to categorize three of the gases. In terms of color selection, I initially tried to use four completely different colors, but this made the chart look very confusing. Attempting to use similar colors, while providing a sense of visual unity, would again make it difficult to distinguish between different data. As a result, the choice of colors became a part of the process that I spent a lot of time and effort on.

This assignment also made me realize that the understanding of charts can vary greatly from one target audience to another. We need to take into account the characteristics and needs of our target audience when creating charts, such as the problem I encountered with the vertical scale. By collecting and integrating the opinions of people around me, I kept on revising the charts and finally got the current result. This process not only improved my data visualization skills, but also deepened my understanding of how to effectively communicate complex information.
